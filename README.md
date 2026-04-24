# Ccruz SatelliteBox

The Ccruz SatelliteBox is a self-developed cyberdeck based on a Raspberry Pi Zero 2W focused on satellite simulation.
It consists on a ecosystem of three members (Two self contained, and one working externally) 

## Included capabilities

- Vim
> Includes CoC extension (Better known as Intellisense)
- Tmux

## Supported Languages

- C
- C++
- Risc-V Assembly

## Workflow

- Capable (external) Workstation simulating the environment with SIMULUS
- Main board (Raspberry Pi Zero 2W) handling the telemetry and emulating the satellite sensors
- Raspberry Pi Pico 2 running RTEMS (?) over it's RISC-V modules working as the satellite

## Material list

- Any capable workstation running SIMULUS software (In this case a Linux machine)
- Raspberry Pi Zero 2W with soldered GPIO pins
- Raspberry Pi Pico 2 with soldered GPIO pins
- Female to female Dupont jumper cables


This cyberdeck is being developed following the ECSS E-ST-40C standards and it is a complete WIP, if you decide to try and make your own, you are doing it under your responsibility as the project is in a very primitive state and could change substantially while developing.

