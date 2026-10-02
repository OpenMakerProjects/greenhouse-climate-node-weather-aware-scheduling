# Greenhouse Climate Node Weather-Aware Scheduling

Build a smart agriculture prototype that uses solar charger, capacitive soil sensor to adapt actions using local weather readings. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 109 |
| Category | Smart Agriculture |
| Platform | STM32 |
| Difficulty | Advanced |
| Estimated build time | 40 hours |
| Connectivity | Wi-Fi |
| Core components | solar charger, capacitive soil sensor |
| Control mode | closed loop control |

## Repository layout

- `firmware/greenhouse-climate-node-weather-aware-scheduling/greenhouse-climate-node-weather-aware-scheduling.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/greenhouse-climate-node-weather-aware-scheduling/greenhouse-climate-node-weather-aware-scheduling.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **STM32**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Weather-Aware Scheduling demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
