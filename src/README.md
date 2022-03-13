# InfraRed Arbitrary Toolbox

**iret** is an acconym for **InfraRed Arbitrary Toolbox**.

The infrared arbitrary toolbox is a combination a a piece of MCU hardware with 
attached infrared sender and infrared receiver and a
software/firmware installed on the MCU. implemented in Rust.

The whole project is splitted accross multiple repositories:

* [This repository](https://almedso.github.io/irat/) -
  The documentation of the system (hardware and software)
* [Firmware](https://github.com/almedso/nucleo-stm32g071rb) -
  Embedded firmware specifically to Nucleo-STM32G071RB board
* [Manchester Code](https://github.com/almedso/manchester-code) -
  Rust library to support manchester code encoding/decoding

This project is an experiment

* To use mddoc for hardware/software technical documentation "as code"
* To have a overarching repository that links several contributing
  repositories losely by a documentation as code
* In software to turn an exploration project into something that
  can be reused according to the CRP (common reuse principle)
