# Water-Reservoir-Protection-Project
Integrates multiple STM32 peripherals into a real-time water monitoring prototype:

- Ultrasonic sensor (HC-SR04): Determines water level.

- ADC1: Reads analog sensors (e.g., pressure/quality).

- Timers: Coordinate ultrasonic pulses and flow counting.

- UART: Reports water level + sensor readings.

- Clock: Tracks hours/minutes/seconds for timestamping.
