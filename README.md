# fronius-mqtt-bridge

Python script to fetch power flow realtime data from a fronis data manager and pubish it to a mqtt broker.

# Requirements
* Tested with Python 3.5

# Usage
Create, activate and setup venv:

```
cd fronius-mqtt-bridge
python3 -m venv ./venv
source venv/bin/activate
pip install -r requirements.txt
```

Then set the right hostnames or ip addresss and ports in fronius-mqtt-bridge.py and run

```
python3 fronius-mqtt-bridge.py
```