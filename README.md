# Real-time Intrusion Detection System
## About
* AI based Real-time Intrusion Detection System. 

* We combine Supervised learning (RF) for detecting known attacks from CICIDS 2018 & SCVIC-APT datasets, and Unsupervised Learning (AE) for anomaly detection.

* System descriptive diagram:


## Requirements:
1. Windows OS.

2. Python 3.9:
    * link 64-bit: https://www.python.org/ftp/python/3.9.13/python-3.9.13-amd64.exe 
    * link 32-bit: https://www.python.org/ftp/python/3.9.13/python-3.9.13.exe

     <b> Note: select "Add Python 3.9 to PATH" in installation procedure.</b>

3. Npcap 1.71:
    https://npcap.com/dist/npcap-1.71.exe

## Download project folder & environment setups:
<code>git clone https://github.com/HoangNV2001/APT_Detection
    cd APT_Detection
    # Create a virtual environment
    python3.9 -m venv venv
    # Activate that virtual environment
    source venv/bin/activate
    # Install the project requirements.
    python -m pip install -r requirements.txt
    # or: pip install -r requirements.txt</code>

Run program:

<code>python application.py</code>

Web app address: [http://localhost:5000](http://localhost:5000)

## Demo GUI
* Main page, overview of real-time captured flows:


![Screenshot 2024-11-26 065927](https://github.com/user-attachments/assets/9c1bf486-ac1b-4642-b8db-e8eb2fe01012)

* Flow detail page:


![Screenshot 2024-12-12 151758](https://github.com/user-attachments/assets/b35304ef-90e6-4e73-9c89-f92a24b924fc)

![Screenshot 2024-12-12 151739](https://github.com/user-attachments/assets/374496fc-0542-4919-b111-536bd2e3983c)

