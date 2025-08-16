# SM_BAS

[Sixteen 0-10V Analog Outputs 8-Layer Stackable HAT for Raspberry Pi ](https://sequentmicrosystems.com/collections/all-io-cards/products/sixteen-0-10v-analog-outputs) CODESYS library.
We include the source code library in the package so everyone can modify. Note that it is an open source library with absolutely no warranty.
## Install
For easy install downoad the .package file and open it on your computer, Codesys installer will know what to do with it.
## Usage
Checkout our example project for guidance.

For using multiple card in the same time you need to set the card stack lever from jumpers and modify the "I2C address" parameter of the  device, below you find the correspondence between stack level and hardware address:

| Stack Level | I2C address |
| --- | --- |
| 0 | 16#72 |
| 1 | 16#73 |
| 2 | 16#74 |
| 3 | 16#75 |
| 4 | 16#76 |
| 5 | 16#77 |
| 6 | 16#78 |
| 7 | 16#79 |
