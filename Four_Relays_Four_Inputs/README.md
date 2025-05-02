# SM_4RELAY_4IN

[Four Relays four HV Inputs 8-Layer Stackable HAT for Raspberry Pi](https://sequentmicrosystems.com/products/four-relays-four-inputs-for-raspberry-pi) CODESYS library.
We include the source code library in the package so everyone can modify. Note that it is an open source library with absolutely no warranty.
## Install
For easy install downoad the .package file and open it on your computer, Codesys installer will know what to do with it.
## Usage
Checkout our example project for guidance.

For using multiple card in the same time you need to set the card stack lever from jumpers and modify the "I2C address" parameter of the  device, below you find the correspondence between stack level and hardware address:

| Stack Level | I2C address |
| --- | --- |
| 0 | 16#0e |
| 1 | 16#0f |
| 2 | 16#10 |
| 3 | 16#11 |
| 4 | 16#12 |
| 5 | 16#13 |
| 6 | 16#14 |
| 7 | 16#15 |
