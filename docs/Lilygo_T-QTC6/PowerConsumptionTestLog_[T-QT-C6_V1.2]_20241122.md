www.lilygo.cc
# **T-QT-C6_V1.2 Power Consumption Test Log**

Date: 20241122

LastEditTime: 20241122
Test board: T-QT-C6_V1.2 (Engineering Prototype)(202405231700)
Testing organization: LILYGO Laboratory

**1. Test Environment Description**

1.1 测试环境
1.1 Test environment

|Test Tools|Sampling speed|Test Methodology|Input voltage|Test environment temperature|
|---|---|---|---|---|
|BLU939|100000 times/s|Battery Interface Measurement|+4.0V|25°C/77°F|



1.2 测试的器件型号
1.2 Test device model

|Test device|Power 3.3V|Screen|Touch|Charging chip|IMU|
|---|---|---|---|---|---|
|Corresponding<br>model|RT9080|N085-1212TBWIG06-C08|CST816T|SGM41562XG/TR|LSM6DSL|



**2. Modification Instructions**

NULL

**3. Test Physical Object Image**

www.lilygo.cc

**4. Program: Deep_Sleep.ino Power Consumption Test**

4.1 总电流变化测试图如下
4.1 The test chart depicting the variation of total current is as follows.

4.2 Current Test Status Diagram:

|ESP32-C6|Power 3.3V|Screen|Touch|Charging chip|IMU|
|---|---|---|---|---|---|
|Deep Sleep|ON|Sleep|Sleep|ON|Sleep|



Test result: average 172.61 μA



www.lilygo.cc

**5. Program: Light_Sleep.ino Power Consumption Test**

5.1 总电流变化测试图如下
5.1 The test chart depicting the variation of total current is as follows.

5.2 Current Test Status Diagram:

|ESP32-C6|Power 3.3V|Screen|Touch|Charging chip|IMU|
|---|---|---|---|---|---|
|Light Sleep|ON|Sleep|Sleep|ON|Sleep|



Test result: average 516.81 μA



