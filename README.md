# Landslide-Early-Warning-Inclinometer
The Landslide Early Warning Inclinometer is an ESP8266-based monitoring system designed to detect ground or surface tilting that may indicate potential landslide movement. The system uses the HW-290 (GY-87) sensor module, including the MPU6050 accelerometer/gyroscope, HMC5883L magnetometer, and BMP180 pressure/temperature sensor.

After a 15-second baseline calibration, the system continuously measures pitch, roll, and relative tilt. When the tilt reaches 8°, it enters a WARNING state, and at 15°, it enters a DANGER state with a faster buzzer alarm.

The ESP8266 also creates its own Wi-Fi hotspot and hosts a real-time monitoring webpage at 192.168.4.1, displaying tilt, pitch, roll, heading, temperature, pressure, sensor status, and warning level. This provides a simple, low-cost prototype for monitoring slope movement and providing an early local warning of potentially dangerous ground displacement.
