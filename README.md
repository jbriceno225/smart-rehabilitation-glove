# Smart Rehabilitation Glove

![Smart Rehabilitation Glove full prototype](media/hero-smart-rehab-glove.jpg)

Wearable rehabilitation prototype that combines glove-mounted motion sensors, custom electronics, embedded acquisition, and a visualization workflow for tracking hand-recovery data outside of a clinic.

## Project Snapshot

- **Role:** Mechanical / mechatronics contributor for wearable integration, sensor mounting, CAD, housing design, wiring integration, and project documentation.
- **System:** Glove-mounted flex sensors, IMUs, force sensing, pulse/SpO₂ sensing, ESP32-based data acquisition, Raspberry Pi / Node-RED visualization, and 3D-printed housings.
- **Purpose:** Capture repeatable hand/finger motion and physiological feedback during rehabilitation sessions.
- **Current repo state:** Portfolio-ready scaffold with project photos and documentation structure. Additional code/CAD/report materials can be added as they become shareable.

## Build Gallery

| Full wearable system | Open electronics bay |
|---|---|
| ![Full wearable Smart Rehabilitation Glove system](media/full-system-tabletop.jpg) | ![Open electronics enclosure with embedded board and wiring](media/open-electronics-lit.jpg) |

| Custom PCB boards | Worn prototype test |
|---|---|
| ![Custom PCB boards for sensor acquisition](media/custom-pcb-boards.jpg) | ![Smart Rehabilitation Glove worn during lab testing](media/worn-prototype-lab.jpg) |

## What the System Demonstrates

### Wearable mechanical integration
- 3D-printed finger segments and mounts for sensor placement.
- Forearm-mounted electronics enclosure with strap interface.
- Cable routing from glove sensors into the control enclosure.
- Iterative fit, serviceability, and prototype packaging decisions.

### Embedded and sensor hardware
- Custom PCB boards for sensor/acquisition organization.
- ESP32-style embedded controller integration inside the forearm housing.
- Multiple glove-mounted sensor modules across fingers.
- Active wiring harness and enclosure-level integration for bench testing.

### Rehabilitation-data workflow
- Captures finger/joint movement inputs and physiological signals.
- Supports calibration and validation work for raw sensor-to-motion mapping.
- Designed around post-session review and real-time visualization concepts.

## System Architecture

| Subsystem | Purpose | Example Hardware / Tools |
|---|---|---|
| Wearable glove | Repeatable sensor placement and human-interface fit | Glove, 3D-printed mounts, straps |
| Sensor layer | Motion and physiological data capture | Flex sensors, IMUs, force sensing, pulse / SpO₂ sensing |
| Embedded acquisition | Sensor sampling, wiring, and communication | ESP32-class controller, custom PCBs, GPIO/ADC/I2C/SPI-style interfaces |
| Electronics enclosure | Wearable packaging and service access | 3D-printed forearm box, removable lid, switch, battery/wiring |
| Visualization | User/session feedback | Raspberry Pi / Node-RED dashboard workflow |
| Calibration/testing | Convert raw signals into useful motion data | Calibration procedures, test reports, plots, session review |

## Repository Structure

```text
cad/        CAD models, mounts, enclosures, and exports
code/       ESP32 firmware and Raspberry Pi / dashboard code when shareable
docs/       reports, design notes, test plans, diagrams, and presentation material
media/      project photos, demo visuals, screenshots, and renders
data/       calibration/test datasets if shareable
```

## Skills Demonstrated

- Mechatronics system integration
- Wearable electromechanical prototyping
- Embedded sensor acquisition
- Custom PCB / wiring-harness integration
- Ergonomic mechanical design and 3D-printed packaging
- Calibration and validation planning
- Technical documentation for a capstone-scale engineering system
