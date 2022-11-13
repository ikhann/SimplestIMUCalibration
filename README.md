# SimplestIMUCalibration
Simple calibration process of the IMU suite

The program reads the data stream from the serial port and provides visualization of the measurements and the offset calibration calculation. 
Next, we will subtract these values for each data sample of sensor data.

The calibration proccess using Python is described in the folowing interactive [Jupyter notebook](Mag_Gyro_Acc_Calibration.ipynb).

### Magnetometer

![](images/mag.gif)

For the magnetometer calibration wave the module in a figure eight until done and make sure it's not near any strong magnets.



For accelerometer calibration slowly rotate the module multiple times in all axis. Be sure to rotate the sensor slowly


For Gyro calibration put down the module and do not touch or move it.