# **vertical furnace manual**
UNLV\
the new version is available on [GitHub](https://github.com/hanc4-git?tab=repositories).

## OTF-1200X-125-VT *(Split Vertical Tube Furnace)*
```
MTI = 
	OTF-1200X-125-VT(2.5*KW, 220-240*VAC, 50/60*Hz, 1200*C, ~20*C/min)
				Tube(130*mm, 120*mm,. 1400*mm,
					quartz, 880*mm, Fe-Cr-Al alloy doped by Mo)
```
> its power, voltage, max temperature, max heating rate\
> at (OD, ID, Length)\
> its materials, heating zone length, heating element

## temperature control program
1. **power (black)** on
2. set control program
```
	Furnace zone(left, central, right)						//its zone 1, 2, 3
	Touch key arrow1_leftwards->enter the stage of temperature(“A/M”)
			C01->celcius*C									//its temperature
			T01->time*min									//its time
		Touch key arrow2_upwards->increase the value to be set(“STOP”)
		Touch key arrow2_downwards->decrease the value to be set(“RUN/HOLD”)
		Touch key arrow2_leftwards->move the point(“A/M”)
		Touch key arrow2_clockwise open circle->get in next segment
	Program end = -121										//output power off
															//for negative, decrease number to make 0 first
```
Run control program
	Heater on
		green->heating ready
		red->heating stop
	Touch key arrow1_downwards = push key for two seconds
Check indicator lights red

//
// vacuum
//
	// VPS-200(“Air_Admiral_Vacuum_Pump_Station”)
	//
	Cole-Parmer = 
	EW-79202-00(0.37*cfm, 21.3*inch Hg,						//its free-air capacity, max vacuum
		0.25*inch, 115*VAC, 1.6*amps, 60*Hz)				//its port size, power
	EW-79202-30(0.37*cfm, 21.3*inch Hg,						//its free-air capacity, max vacuum
		0.25*inch, 120*VAC, 4.6*amps, 60*Hz)				//its port size, power

	// tube vacuum
	Close valve1_top										//top flange valve
		Option to Close valve2_bottom						//bottom flange valve
	Turn on vacuum pump
	Open valve2_bottom slowly
	Wait when close to -0.05*MPa

	// tube vacuum locked in
	Close valve2_bottom										//tube vacuum locked in
	Turn off vacuum pump

	// break vacuum
		Turn off vacuum pump								//if needed
	Open valve1_top											//purge with air
	Wait when close to ~0*MPa
	Able to open top outer flange

//
// closing
//
Close furnace door
Power off
	black->power

//....oooOO0OOooo........oooOO0OOooo........oooOO0OOooo........oooOO0OOooo......
