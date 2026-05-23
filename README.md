# Smart Rehabilitation Glove

Wearable rehabilitation system integrating multi-sensor data acquisition, embedded control, ergonomic mechanical design, and real-time visualization.

> Capstone project repository scaffold. Add final code, CAD, diagrams, photos, and reports as project materials become shareable.

## Project Summary
The Smart Rehabilitation Glove is designed to capture hand/finger motion and physiological feedback for rehabilitation monitoring. The system combines flex sensors, IMUs, pulse sensing, embedded data acquisition, and a Raspberry Pi-based visualization interface.

## System Goals
- Measure finger/joint motion through flex sensors and IMUs.
- Collect sensor data using an ESP32-based acquisition architecture.
- Visualize joint angle and pulse data through a Raspberry Pi GUI.
- Improve sensor placement repeatability through ergonomic mechanical design.
- Support calibration/testing to map raw sensor values to meaningful motion data.

## System Architecture

| Subsystem | Purpose | Example Hardware/Tools |
|---|---|---|
| Wearable glove | ergonomic sensor mounting and repeatability | glove, 3D-printed mounts/enclosures |
| Sensor layer | motion and physiological data capture | flex sensors, IMUs, pulse sensor |
| Embedded acquisition | sensor sampling and communication | ESP32, I2C/SPI/ADC/GPIO |
| Visualization | real-time user feedback | Raspberry Pi GUI |
| Calibration/testing | validate sensor-to-motion mapping | test procedures, plots, comparison data |

## My Contributions
- Led mechanical design for glove ergonomics, sensor placement, and repeatability.
- Architected ESP32-based multi-sensor acquisition approach.
- Developed Raspberry Pi GUI concepts for real-time visualization.
- Designed 3D-printed enclosures/mounts for sensor integration.
- Performed calibration testing to correlate sensor outputs with physical joint motion.

## Planned Repository Structure
```text
cad/        CAD models, mounts, enclosures, and exports
code/       ESP32 firmware and Raspberry Pi GUI code
docs/       reports, design notes, test plans, and diagrams
media/      photos, screenshots, demo videos, and renders
data/       calibration/test datasets if shareable
```

## Development Roadmap
- [ ] Add system block diagram
- [ ] Add glove photos/renders
- [ ] Add ESP32 firmware
- [ ] Add Raspberry Pi GUI screenshots/code
- [ ] Add calibration method and sample plots
- [ ] Add final report/presentation if shareable

## Skills Demonstrated
- Mechatronics system integration
- Embedded sensor acquisition
- Ergonomic mechanical design
- Calibration and validation testing
- Human-centered electromechanical system design
- Technical documentation
