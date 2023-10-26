This is the CODESYS Library for Sequent Microsystems Home Automation V4 8-Layer Stackable HAT for Raspberry Pi

VAR_INPUT
	relayState: ARRAY[0..7] OF BOOL;  -> Relays control
	out0_10Volt: ARRAY[0..3] OF REAL; -> 0-10V output ports (V)
	outOdPwm:ARRAY[0..3] OF REAL; -> open drain output ports (%)

VAR_OUTPUT
	inOpto: ARRAY[0..7] OF BOOL; -> Opto isolated digital inputs
	in0_3Volt: ARRAY[0..7] OF REAL; -> 0-3.3V input ports (V)
	inOWBTemp: ARRAY[0..8] OF REAL; -> temperature of one wire bus 18B20 sensors (degC)
	inOWBSensors: USINT; -> Number of 18B20 connected sensors
	boardTemperature: REAL; -> card temperature (degC)
	
	
	