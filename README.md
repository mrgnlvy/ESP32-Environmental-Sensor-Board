# ESP32-Environmental-Sensor-Board

4-layer ESP32-C3 IoT PCB with USB-C charging and data transfer, along with environmental sensors, a battery charge manger,  an OLED display, and SD storage for remote data logging capabilities.

### Features

- **Microcontroller**: ESP32-C3-02 for Wi-Fi/BLE
- **Power Inputs**:
  - USB-C connector for charging and data transfer.
  - LiPo battery connector with onboard charging circuitry.
- **Sensors and Modules**:
  - BME280 for temperature, humidity, and pressure sensing.
  - Ambient light and sound sensors.
  - Mini SD card reader for data storage.
  - Flash memory for additional storage.
- **Power Management**: TP4056 IC for single-cell Li-ion battery charging with thermal regulation.
- **Battery Protection**: Integrated under-voltage lockout and trickle charging.
- **Display**: I2C OLED for real-time data visualization.
- **Indicators**: LED indicators for charge status (charging and full).

### Design

4-layer design:
- **Top**: Signals
- **Inner 1**: Ground Plane
- **Inner 2**: Power Plane
- **Bottom**: Signals

### Applications

- IoT edge devices for environmental monitoring.
- Battery-powered data logging systems.
- Prototyping platform for ESP32-based projects.

<img width="1689" height="920" alt="image" src="https://github.com/user-attachments/assets/096d91fe-435e-46ed-99f8-3c67fa8e6fee" />

