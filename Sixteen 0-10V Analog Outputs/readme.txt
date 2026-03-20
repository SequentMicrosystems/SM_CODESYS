This is the CODESYS Library for Sequent Microsystems Sixteen 0-10V Analog Outputs 8-Layer Stackable HAT for Raspberry Pi

VAR_INPUT
	out0_10Volt: ARRAY[0..15] OF REAL; // -> 0-10V output ports (V)
	
	reloadWdt: BOOL;
	clearWdtResetCount: BOOL;
	setWdtPeriod: UINT;
	setWdtInitPeriod: UINT;
	setWdtOffPeriod: UDINT;
	
	enableWdt: BOOL := FALSE;
END_VAR

VAR_OUTPUT
	boardTemperature: REAL; //-> card temperature (degC)
	button: BOOL; // -> Button state (False - not pressed, True - pressed)
	wdtResetCount: UINT; // Watchdog number of performed repowers;
	wdtPeriod: UINT; // Watchdog period in seconds, reload command must be issued in this interval to prevent Raspberry Pi power off.
	wdtInitPeriod: UINT; // Watchdog initial period in seconds. This period is loaded after power cycle, giving Raspberry time to boot.
	wdtOffPeriod: UDINT; // Watchdog off period in seconds (max 48 days). This is the time that watchdog mantain Raspberry turned off.
END_VAR