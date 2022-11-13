# SimplestIMUCalibration
Simple calibration process of the MEMS IMU suite.

The program reads the data stream from the serial port and provides visualization of the measurements and the offset calibration calculation.
Next, we will subtract these values for each data sample of sensor data.

The calibration proccess using Python is described in the folowing interactive [Jupyter notebook](Mag_Gyro_Acc_Calibration.ipynb).

### Accelerometer
For accelerometer calibration slowly rotate the module multiple times in all axis. Be sure to rotate the sensor slowly.

https://user-images.githubusercontent.com/21182465/201548314-fe4ac1df-9672-46b9-b53e-8b3ff8a4fa5c.mov

### Magnetometer
For the magnetometer calibration wave the module in a figure eight until done and make sure it's not near any strong magnets.

https://user-images.githubusercontent.com/21182465/201548333-0c531864-4acd-444d-909f-66b76d2269a9.mov


### Gyroscope

For Gyro calibration put down the module and do not touch or move it.
