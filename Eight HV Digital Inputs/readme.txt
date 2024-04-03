This is the CODESYS Library for Sequent Microsystems Multi-IO 8-Layer Stackable HAT for Raspberry Pi
Change your thermocouples type with command line 
VAR_INPUT
	relayState: ARRAY[0..1] OF BOOL;  -> Relays control
	ledState: ARRAY[0..5] OF BOOL; -> Led's control
	out0_10V: ARRAY[0..1] OF REAL; -> 0-10V output ports (V)
	out4_20mA:ARRAY[0..1] OF REAL; -> 4 - 20mA output ports (mA)
	servo:ARRAY[0..1] OF REAL; -> servo position [-140..140]
	motor: REAL; -> motor pwm [0..100]
	

VAR_OUTPUT
	in0_10V: ARRAY[0..1] OF REAL; -> 0-10V inputs ports (V)
	in4_20mA:ARRAY[0..1] OF REAL; -> 4 - 20mA inputs ports (mA)
	inOpto: ARRAY[0..3] OF BOOL; -> opto inputs
	inRTDTemp: ARRAY[0..1] OF REAL; -> temperature of RTD sensors (degC)
	boardTemperature: REAL; 
	