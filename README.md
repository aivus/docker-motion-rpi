# Motion for RPi

This repository provides a docker images for [Motion](https://github.com/Motion-Project/motion) built for Raspberry Pi.

Images for the next platforms currently available on Docker Hub:
- linux/arm/v7
- linux/arm64

#### Supported Raspberry Pi models

| Model | Architecture | Platform |
| --- | --- | --- |
| Pi 2 B (v1.1) | ARMv7 | `linux/arm/v7` |
| Pi 2 v1.2, Pi 3 / 3+, Zero 2 W | ARMv8 | `linux/arm64` or `linux/arm/v7` |
| Pi 4 / 400 | ARMv8 | `linux/arm64` or `linux/arm/v7` |
| Pi 5 | ARMv8.2 | `linux/arm64` |

> **Note:** The original Pi 1, Pi Zero, and Pi Zero W are **not supported**. They are
> ARMv6, and the Debian base image has no ARMv6 (`linux/arm/v6`) build.

#### Links

* Docker Registry @ [aivus/motion-rpi](https://hub.docker.com/r/aivus/motion-rpi)
* GitHub Repository @ [aivus/docker-motion-rpi](https://github.com/aivus/docker-motion-rpi)
