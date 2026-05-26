# Smart Rehabilitation Glove

![Smart Rehabilitation Glove full prototype](https://cdn.discordapp.com/attachments/1507256945277403216/1508934563747856466/IMG_3741.png?ex=6a175852&is=6a1606d2&hm=d95a78d24a30068d7d7d0b722a70cc8aab534a16a7ce8493b32acf85b03a2190&)

Wearable rehabilitation prototype that combines glove-mounted motion sensors, custom electronics, embedded acquisition, and a visualization workflow for tracking hand-recovery data outside of a clinic.

## Project Snapshot

- **Role:** Mechanical / mechatronics contributor for wearable integration, sensor mounting, CAD, housing design, wiring integration, and project documentation.
- **System:** Glove-mounted flex sensors, IMUs, force sensing, pulse/SpO₂ sensing, ESP32-based data acquisition, Raspberry Pi / Node-RED visualization, and 3D-printed housings.
- **Purpose:** Capture repeatable hand/finger motion and physiological feedback during rehabilitation sessions.
- **Current repo state:** Portfolio-ready scaffold with project photos and documentation structure. Additional code/CAD/report materials can be added as they become shareable.

## Build Gallery

| Full wearable system | Open electronics bay |
|---|---|
| ![Full wearable Smart Rehabilitation Glove system](https://cdn.discordapp.com/attachments/1507256945277403216/1508934563747856466/IMG_3741.png?ex=6a175852&is=6a1606d2&hm=d95a78d24a30068d7d7d0b722a70cc8aab534a16a7ce8493b32acf85b03a2190&) | ![Open electronics enclosure with embedded board and wiring](https://cdn.discordapp.com/attachments/1507256945277403216/1508934563420966932/IMG_3742.png?ex=6a175852&is=6a1606d2&hm=30b1a1479a44546557998b0bed13242a03b7c4ffb365201ebbae38c25f7fea92&) |

| Custom PCB boards | Worn prototype test |
|---|---|
| ![Custom PCB boards for sensor acquisition](https://cdn.discordapp.com/attachments/1507256945277403216/1508934562774777886/IMG_3744.png?ex=6a175852&is=6a1606d2&hm=7f9e0f5f53e781520d7f56d098151b9f9ecaa441567712ddb81b7d4c0ca953d2&) | ![Smart Rehabilitation Glove worn during lab testing](https://cdn.discordapp.com/attachments/1507256945277403216/1508934563106132132/IMG_3743.png?ex=6a175852&is=6a1606d2&hm=f12977c96729f6bf13432545fb86d0126552dab13466dd6dcf95304448ba1627&) |

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
