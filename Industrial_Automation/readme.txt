This is the CODESYS Library for Sequent Microsystems Industrial Automation HAT for Raspberry Pi

VAR_INPUT
	ledState: ARRAY[0..3] OF BOOL;  -> leds control
	out0_10Volt: ARRAY[0..3] OF REAL; -> 0-10V output ports (V)
	out4_20Ma: ARRAY[0..3] OF REAL; -> 4-20mA output ports (mA)
	outOdPwm:ARRAY[0..3] OF REAL; -> open drain output ports (%)

VAR_OUTPUT
	inOpto: ARRAY[0..3] OF BOOL; -> Opto isolated digital inputs
	in0_10Volt: ARRAY[0..3] OF REAL; -> 0-10V input ports (V)
	in4_20Ma: ARRAY[0..3] OF REAL; -> 4-20mA input ports (mA)
	inOWBTemp: ARRAY[0..15] OF REAL; -> temperature of one wire bus 18B20 sensors (degC)
	inOWBSensors: USINT; -> Number of 18B20 connected sensors
	boardTemperature: REAL; -> card temperature (degC)
	
	
	