# water-quality-monitoring

This is my water quality monitoring based on ESP32 chip using ESP-IDF development framework.
implementing 5 type of sensor (temperature, tds, turbidity, pH, dissolve oxygen)

### TO DO
#### ADC (Analog to Digital)
- [ ] Connect to ADS1115 through I2C
- [ ] Create ADS function for ADS1115
- [ ] Connect Sensor to ADS1115
    - [ ] temperature
    - [ ] TDS
    - [ ] Turbidity
    - [ ] pH
    - [ ] dissolve oxygen
- [ ] Calibrate the sensor
#### UART
- [ ] implement uart protocol
- [ ] communicate with NEXTION
- [ ] Create interactive display
- [ ] Adding feature to communicate with atmega attiny85
#### WiFi
- [ ] Connect to wifi
- [ ] Implement core 1 to handle network
#### MQTT
- [ ] Implement MQTT pub over TCP connection
- [ ] let core 1 to handle mqtt
- [ ] Implement MQTT sub to have control over the power source
#### Power Efficiency
- [ ] Implement Sleep mode
- [ ] Create BMS module based on attiny85
- [ ] Implement some power mode
