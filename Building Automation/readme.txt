This is the CODESYS Library for Sequent Microsystems Building Automation HAT for Raspberry Pi

VAR_INPUT
	triacState: ARRAY[0..3] OF BOOL;  -> triac control
	out0_10Volt: ARRAY[0..3] OF REAL; -> 0-10V output ports (V)

VAR_OUTPUT
	inContact: ARRAY[0..7] OF BOOL; -> Opto isolated digital inputs
	in0_10Volt: ARRAY[0..7] OF REAL; -> 0-10V input ports (V)
	in1k:ARRAY[0..7] OF REAL; -> 1k thermistor input in ohms
	in10k:ARRAY[0..7] OF REAL; -> 1k thermistor input in ohms
	inOWBTemp: ARRAY[0..15] OF REAL; -> temperature of one wire bus 18B20 sensors (degC)
	inOWBSensors: USINT; -> Number of 18B20 connected sensors
	boardTemperature: REAL; -> card temperature (degC)
	
	
	