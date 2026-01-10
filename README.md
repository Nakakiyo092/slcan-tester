# SLCAN Tester
Python test scripts for SLCAN device with CAN FD support.


## Requirements
- Python 3.13
- pyserial library (`pip install pyserial`)


## Standard test cases

1. Connect the host and the device
2. The device should not be connected to another CAN device
3. Search the device and get the device name (ex. COMX or ttyACMX)
4. Update test scripts with the device name (test/device_under_test.py)
5. Run the test script from the root directory

Windows
```
.\test\test_std_case.bat
```
Linux
```
./test/test_std_case.sh
```


## Individual test cases

1. Connect the host and the device
2. Set up CAN network following instructions for the individual test case
3. Search the device and get the device name (ex. COMX or ttyACMX)
4. Update test scripts with the device name (test/device_under_test.py)
5. Run the test script from the root directory

Windows
```
python .\test\test_slcan.py
```
Linux
```
python3 ./test/test_slcan.py
```
