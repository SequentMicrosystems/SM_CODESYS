# SM_CODESYS

[![SM_CODESYS](res/sequent.png)](https://www.sequentmicrosystems.com)


### CODESYS Libraries for Sequent Microsystems Cards

This repository includes CODESYS device libraries and packages for Sequent Microsystems Cards for Raspberry Pi. Each board has its own subfolder with a `.package` file and a usage guide.

## Supported Cards

| Card | Product page | CLI / Python / Node-RED |
|------|-------------|-------------------------|
| [Eight Relays](Eight%20Relays) | [product page](https://sequentmicrosystems.com/products/eight-relays-stackable-card-for-raspberry-pi) | [8relind-rpi](https://github.com/SequentMicrosystems/8relind-rpi) |
| [Sixteen Relays](Sixteen%20Relays) | [product page](https://sequentmicrosystems.com/products/sixteen-relays-8-layer-stackable-hat-for-raspberry-pi) | [16relind-rpi](https://github.com/SequentMicrosystems/16relind-rpi) |
| [Four Relays Four Inputs](Four_Relays_Four_Inputs) | [product page](https://sequentmicrosystems.com/products/four-relays-four-inputs-for-raspberry-pi) | [4rel4in-rpi](https://github.com/SequentMicrosystems/4rel4in-rpi) |
| [Eight HV Digital Inputs](Eight%20HV%20Digital%20Inputs) | [product page](https://sequentmicrosystems.com/products/eight-hv-digital-inputs-for-raspberry-pi) | [8inputs-rpi](https://github.com/SequentMicrosystems/8inputs-rpi) |
| [Sixteen Universal Inputs](Sixteen%20Universal%20Inputs) | [product page](https://sequentmicrosystems.com/products/sixteen-analog-digital-inputs-8-layer-stackable-hat-for-raspberry-pi) | [16univin-rpi](https://github.com/SequentMicrosystems/16univin-rpi) |
| [Sixteen LV Digital Inputs](SM_16LVIN) | [product page](https://sequentmicrosystems.com/products/sixteen-lv-digital-inputs-card-for-raspberry-pi) | [16inpind-rpi](https://github.com/SequentMicrosystems/16inpind-rpi) |
| [Multi-IO](Multi_IO) | [product page](https://sequentmicrosystems.com/products/multi-io-hat-8-layer-stackable-hat-for-raspberry-pi) | [multiio-rpi](https://github.com/SequentMicrosystems/multiio-rpi) |
| [Eight MOSFETs](SM_8MOS) | [product page](https://sequentmicrosystems.com/products/eight-mosfets-8-layer-stackable-card-for-raspberry-pi) | [8mosind-rpi](https://github.com/SequentMicrosystems/8mosind-rpi) |
| [RTD Data Acquisition](RTD%20Data%20Acquisition) | [product page](https://sequentmicrosystems.com/products/rtd-data-acquisition-card-for-rpi) | [rtd-rpi](https://github.com/SequentMicrosystems/rtd-rpi) |
| [Thermocouple DAQ](Thermocouple%20DAQ) | [product page](https://sequentmicrosystems.com/products/eight-thermocouples-daq-8-layer-stackable-hat-for-raspberry-pi) | [smtc-rpi](https://github.com/SequentMicrosystems/smtc-rpi) |
| [Home Automation](Home%20Automation) | [product page](https://sequentmicrosystems.com/products/raspberry-pi-home-automation-card) | [ioplus-rpi](https://github.com/SequentMicrosystems/ioplus-rpi) |
| [Industrial Automation](Industrial_Automation) | [product page](https://sequentmicrosystems.com/products/industrial-automation-for-raspberry-pi) | [megaind-rpi](https://github.com/SequentMicrosystems/megaind-rpi) |
| [Building Automation](Building%20Automation) | [product page](https://sequentmicrosystems.com/products/building-automation-8-layer-stackable-hat-v4-for-raspberry-pi) | [megabas-rpi](https://github.com/SequentMicrosystems/megabas-rpi) |
| [Sixteen 0-10V Analog Outputs](Sixteen%200-10V%20Analog%20Outputs) | [product page](https://sequentmicrosystems.com/products/sixteen-0-10v-analog-outputs) | [16uout-rpi](https://github.com/SequentMicrosystems/16uout-rpi) |

---

## Installation

1. Clone or download this repository
2. Navigate to the subfolder of your card
3. Double-click the `.package` file — CODESYS will handle the rest

Each subfolder contains a `README.md` with board-specific wiring, I²C address configuration, and function block usage.

---

## Requirements

- CODESYS Development System v3.5 or later
- Raspberry Pi with I²C enabled
- Sequent Microsystems card