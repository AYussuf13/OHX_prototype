# Prototype Development

## Week 1 – Hardware Setup

- Purchased the core hardware components:
  - ESP32 microcontroller
  - BME688 gas sensor
  - Disposable mouthpieces
- Successfully connected and configured the TFT display.
- Established the initial hardware platform for prototype development.

## Week 2 – Sensor Integration

**Objective:** Establish communication between the BME688 gas sensor and the ESP32 before beginning breath sensing experiments.

### Progress

- Connected the BME688 to the ESP32 using I²C communication.
- Successfully displayed temperature, humidity, pressure, and gas resistance readings in the Serial Monitor.
- Confirmed stable communication between the sensor and microcontroller.

## Week 3 – Initial Breath Detection

**Objective:** Determine whether the prototype could detect changes in human breath.

### Progress

- Built an initial breath sampling setup.
- Successfully detected changes in gas sensor readings following breath exposure.
- Displayed real-time sensor readings on both the TFT display and the Serial Monitor.
- Achieved the first proof-of-concept that the prototype responds to breath.
