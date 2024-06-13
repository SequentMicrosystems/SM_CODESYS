# SM_MIO

[Building Automation 8-Layer Stackable HAT for Raspberry Pi](https://sequentmicrosystems.com/collections/all-io-cards/products/building-automation-8-layer-stackable-hat-v4-for-raspberry-pi) CODESYS library.
We include the source code library in the package so everyone can modify. Note that it is an open source library with absolutely no warranty.
## Install
For easy install downoad the .package file and open it on your computer, Codesys installer will know what to do with it.
## Usage
Checkout our example project for guidance.

For using multiple card in the same time you need to set the card stack lever from jumpers and modify the "I2C address" parameter of the  device, below you find the correspondence between stack level and hardware address:

| Stack Level | I2C address |
| --- | --- |
| 0 | 16#48 |
| 1 | 16#49 |
| 2 | 16#4a |
| 3 | 16#4b |
| 4 | 16#4c |
| 5 | 16#4d |
| 6 | 16#4e |
| 7 | 16#4f |
