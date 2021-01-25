# uavcan v0.1 fake gps publisher

## Preparation

1. Clone repo

2. Install python packages:
```
pip3 install -r requirements.txt
```

3. Make scripts as executable
```
chmod +x detect_tty.sh
chmod +x fake_gps.py
```

## Before run

1. Insert a sniffer device to your computer
2. Detect your dev port using detect_tty.sh
3. Modify fake_gps.py (constant DEV_PORT) script and run it

![alt text](https://github.com/PonomarevDA/uavcan_0_1_fake_gps_publisher/blob/master/img/example.png?raw=true)
