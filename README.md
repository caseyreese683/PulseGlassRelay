# PulseGlassRelay

PulseGlassRelay captures and reflects API heartbeat pulses while validating content consistency and timing drift between mirrored services.

## Features
- Transparent POST relay with reflection to secondary endpoint.
- Response diffing with optional JSON validation.
- Timestamp drift detection.
- Configurable mirror pairs.

## Usage
```bash
git clone https://github.com/your-org/PulseGlassRelay.git
cd PulseGlassRelay
python pulserelay/relay_server.py
