This is the CODESYS Library for Sequent Microsystems Eight MOSFETS 8-Layer Stackable HAT for Raspberry Pi
Change your thermocouples type with command line 
VAR_INPUT
	mosState: ARRAY[0..7] OF BOOL;  -> Mosfets ON/OFF control
	mosPWM: ARRAY[0..7] OF REAL; -> Mosfet PWM fill factor (0-100%)
	pwmFreq: REAL; -> PWM frequency in Hz
	

VAR_OUTPUT
	