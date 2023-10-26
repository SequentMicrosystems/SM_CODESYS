# SM_HOME

[Home Automation V4 8-Layer Stackable HAT for Raspberry Pi](https://sequentmicrosystems.com/collections/all-io-cards/products/raspberry-pi-home-automation-card) CODESYS library.
We include the source code library in the package so everyone can modify. Note that it is an open source library with absolutely no warranty.
## Install
For easy install downoad the .package file and open it on your computer, Codesys installer will know what to do with it.
## Usage
Checkout our example project for guidance.

For using multiple card in the same time you need to set the card stack lever from jumpers and modify the "I2C address" parameter of the  device, below you find the correspondence between stack level and hardware address:

| Stack Level | I2C address |
| --- | --- |
| 0 | 16#28 |
| 1 | 16#29 |
| 2 | 16#2a |
| 3 | 16#2b |
| 4 | 16#2c |
| 5 | 16#2d |
| 6 | 16#2e |
| 7 | 16#2f |
