# PLUTO-SDR

Repo for experiments with the ADI ADALM PLUTO SDR

## TODO

- [ ] Look at [multi-device sync](https://wiki.analog.com/resources/eval/user-guides/ad-fmcomms5-ebz/multi-chip-sync)

## Getting Started w/Stock Device

- [Install `libiio` Linux packages and `iio-oscilloscope`](https://wiki.analog.com/resources/tools-software/linux-software/iio_oscilloscope#linux)
  + **NOTE:** if seeing error `./osc: error while loading shared libraries: libosc.so: cannot open shared object file:` while loading `./osc`, launch from the build directory and set library path to `export LD_LIBRARY_PATH=./:$LD_LIBRARY_PATH`
- When plugged in to PC w/middle USB connector, the default firmware shows up as a USB storage device. In there, an `info.html` file has getting started info, as well as methods to update the FW of the PLUTO.

## References

* [Introduction to the ADALM-PLUTO SDR](https://youtu.be/05nLPVJW9Uo)
* [ADALM-PLUTO Overview](https://wiki.analog.com/university/tools/pluto)
  - [Developers Wiki](https://wiki.analog.com/university/tools/pluto/developers): HW, FW, SW info and how to build/add base image
    + [SW/Device Drivers](https://wiki.analog.com/university/tools/pluto/device_drivers)
