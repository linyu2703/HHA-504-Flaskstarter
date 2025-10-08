<h1>Deploying a Flask App on a Cloud VM</h1>
<p>Student Name: yu lin</p>
<p>Cloud Provider: Google Cloud</p>
<h2>Part A: VM setup</h2>
<img src="/images/vm-running.png">
<h2>Part B: Networking: Port 5003</h2>
<img src="/images/port-open.png">
<h2>Part C: OS Update and Python Install</h2>
<img src="/images/os-update.png">
<img src="/images/python-install.png">
<p>To update os: sudo apt update && sudo apt upgrade -y</p>
<p>To instll python3 and pip: sudo apt install git python3 python3-pip python3.13-venv -y</p>
<p>To activate virtual environment: python3 -m venv venv</p>
<p>source venv/bin/activate</p>
<p>To install dependences: pip install requirements.txt</p>
<p>To run app: python3 app.py</p>
<h2>Part D: Flask App Running</h2>
<img src="/images/flask-running.png">
<img src="/images/flask-browser.png">
<h2>Public IP Address</h2>
<p>URL: http://34.135.196.78:5003</p>
<img src="/images/external-ip.png">