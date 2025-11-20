# How to compile

You have to build on a Linux device. For Ubuntu >=20.04 do the following steps:

```bash
sudo apt install gcc-arm-none-eabi
```
```bash
sudo apt install openocd
```
```bash
sudo apt install git-lfs
```
```bash
sudo apt install tup
```
```bash
sudo apt install python3 python3-yaml python3-jinja2 python3-jsonschema
```

Then run `make` in the `Firmware` directory. Now you can flash the new firmware to your ODrive.

More information in the [ODrive development guide](https://docs.odriverobotics.com/v/0.5.6/developer-guide.html).
