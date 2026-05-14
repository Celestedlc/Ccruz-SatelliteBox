# Ccruz SatelliteBox

The Ccruz SatelliteBox is a self-developed cyberdeck based on a Raspberry Pi Zero 2W focused on satellite simulation.
It consists on a ecosystem of three members (Two self contained, and one working externally) 

## Included capabilities

- Neovim
> Includes code suggestions (Intellisense)
- Tmux
- Git

## Supported Languages

- C
- C++
- Python
- Risc-V Assembly

## Workflow

- Capable (external) Workstation simulating the environment with SIMULUS
- Main board (Raspberry Pi Zero 2W) handling the telemetry and emulating the satellite sensors
- Raspberry Pi Pico 2 running RTEMS over it's RISC-V modules working as the satellite

## Material list

- Any capable workstation running SIMULUS software (In this case a Fedora 44 Linux machine)
- Raspberry Pi Zero 2W with soldered GPIO pins
- Raspberry Pi Pico 2 with soldered GPIO pins
- Female to female Dupont jumper cables
- USB-A to Micro-USB for programming the Pico 2 & alimentation for the Zero 2W.
- Case

> Only if you want to convert it into a standalone machine and not use ssh:
> - Keyboard (Bluetooth in my case as I want to keep a free USB input)
> - HDMI Screen
> - Power Solution


This cyberdeck is being developed following the ECSS E-ST-40C standards and it is a complete WIP, if you decide to try and make your own, you are doing it under your responsibility as the project is in a very primitive state and could change substantially while developing.

