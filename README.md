# evcc-controller

## Setup S3 Mini Pro

See: [VIEWESMART/UEDX24240013-MD50ESP32_1.3inch-Knob](https://github.com/VIEWESMART/UEDX24240013-MD50ESP32_1.3inch-Knob)

### Enable flash mode

1. `Press + hold` the `0` button
2. `Click` the `Reset` button
3. `Release` the `0` button 

### Flash the firmware

```bash
cd config
esphome run lolin-s3-mini-pro.yaml
```

## Setup viewe C3 Rotary Encoder

### Firmware

```bash
cd config
esphome run viewe-s3-rotary.yaml
```