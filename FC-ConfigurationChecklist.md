## Firmware Configuration Checklist (Flight Controller)

  

### 1. Firmware Installation

- [ ] Download correct firmware (e.g., INAV for SpeedyBee F405 Wing)

- [ ] Verify target board matches hardware

- [ ] Flash firmware using configurator (USB or Wi-Fi if supported)

- [ ] Confirm successful flash and reboot

  

### 2. Initial Setup

- [ ] Set correct airframe type (Fixed Wing)

- [ ] Configure mixer (AIL, ELE, RUD, THR channels)

- [ ] Assign motor outputs and servo outputs

- [ ] Enable required features (GPS, Compass, OSD, VTX control if supported)

  

### 3. Sensor Calibration

- [ ] Accelerometer calibration (level surface)

- [ ] Compass calibration (rotate in all axes away from metal)

- [ ] Verify sensor status in configurator

  

### 4. GPS & Navigation

- [ ] Connect GPS module to correct UART

- [ ] Set baud rate and protocol (UBlox recommended)

- [ ] Verify GPS lock (>8 satellites)

- [ ] Configure home position and failsafe behavior (Return-to-Home altitude)

  

### 5. Radio Setup

- [ ] Bind receiver to transmitter (ELRS protocol confirmed)

- [ ] Map channels correctly (Roll, Pitch, Yaw, Throttle)

- [ ] Set endpoints and midpoints

- [ ] Configure failsafe (Throttle cut or RTH)

  

### 6. Flight Modes

- [ ] Enable ARM, ANGLE, ACRO, PASSTHRU, RTH

- [ ] Assign modes to switches on transmitter

- [ ] Test mode switching in configurator

  

### 7. PID & Rates

- [ ] Load preset for trainer aircraft or start with defaults

- [ ] Set RC rates and expo for smooth control

- [ ] Verify servo limits and throws

  

### 8. OSD & Telemetry

- [ ] Configure OSD layout (battery voltage, GPS, flight mode)

- [ ] Enable telemetry to radio if supported

- [ ] Verify data updates in goggles or display

  

### 9. VTX Settings (Optional)

- [ ] Configure VTX channel and power via FC (SmartAudio or Tramp)

- [ ] Lock VTX settings to prevent accidental changes

- [ ] Verify video feed and OSD overlay

  

### 10. Safety & Final Checks

- [ ] Confirm failsafe triggers correctly (bench test)

- [ ] Verify throttle cut works

- [ ] Save and backup configuration