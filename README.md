# pi-ps2x

Hybrid module (Python + Cpp) for communicating with PS2 controller for Raspberry Pi. Ported from [Arduino-PS2X](https://github.com/madsci1016/Arduino-PS2X).

## Download

```bash
git clone https://github.com/minhan74/pi-ps2x.git
```

## How to install

- Give permission for shell script:

```bash
cd pi-ps2x/
sudo chmod +x ps2_setup.sh
```

- Run setup:

```bash
sudo ./ps2_setup.sh
```

- Now Raspbian is ready to use ps2. Run example:

```bash
sudo python3 example.py
```
