This is the CODESYS Library for Sequent Microsystems Sixteen Universal Inputs 8-Layer Stackable HAT for Raspberry Pi

VAR_INPUT
	resetContactCnt: ARRAY[0..15] OF BOOL; // -> Set to TRUE if you want to reset the counter, goes back to FALSE when done	

	setRtc: RTC_STRUCT;
	edgeCfg: ARRAY[0..15] OF USINT; // -> o none, 1 - rising
	
	enableRtc: BOOL := FALSE;
END_VAR

VAR_OUTPUT
	inContact: ARRAY[0..15] OF BOOL; // -> Opto isolated digital inputs
	inContactCnt: ARRAY[0..15] OF UDINT; // -> Opto isolated cumulative counter (set edge to use this)
	in0_10Volt: ARRAY[0..15] OF REAL; //-> 0-10V input ports (V)
	in1k: ARRAY[0..15] OF REAL; //-> 1k thermistor input in ohms
	in10k: ARRAY[0..15] OF REAL; //-> 1k thermistor input in ohms
	boardTemperature: REAL; //-> card temperature (degC)
	rtc: RTC_STRUCT; // -> rtc year, month, day, hour, minute, second struct
END_VAR