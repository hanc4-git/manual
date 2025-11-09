# **vertical furnace manual**
UNLV\
the new version is available on [GitHub](https://github.com/hanc4-git?tab=repositories).

## OTF-1200X-VT-III-5 *(CE Certified Three Zone Split Vertical Tube Furnace)*
```
MTI = 
	OTF-1200X-VT-III-5(2.5*KW, 208-240*VAC, 50/60*Hz, 1200*C, ~20*C/min)
				Tube(130*mm, 120*mm, 1400*mm,
					quartz, 880*mm, Fe-Cr-Al alloy doped by Mo)
```
> its power, voltage, max temperature, max heating rate\
> at (OD, ID, Length)\
> its materials, heating zone length, heating element

## temperature control program
1. **power (black)** on
2. set control program
	- **Furnace zone(left, central, right)**
	> its zone 1, 2, 3
 
	- **Touch key arrow1_leftwards**->enter the stage of temperature *(A/M)*\
		**C01**->celcius (C)\
		**T01**->time (min)
   		> its temperature\
		> its time
   
	- **Touch key arrow2_upwards**->increase the value to be set *(STOP)*
	- **Touch key arrow2_downwards**->decrease the value to be set *(RUN/HOLD)*
	- **Touch key arrow2_leftwards**->move the point *(A/M)*
	- **Touch key arrow2_clockwise open circle**->get in next segment
	- Program end = **-121**
	> output power off\
	> for negative, decrease number to make 0 first

4. **heater (green)** on\
	**green**->heating ready\
	**red**->heating stop

5. **Touch key arrow1_downwards**->push key for two seconds
6. check indicator lights flashing

## vacuum
### [VPS-200 *(Air_Admiral_Vacuum_Pump_Station)*](https://www.coleparmer.com/p/cole-parmer-vps-200-series-air-admiral-vacuum-pumps/48670)
```
Cole-Parmer = 
	EW-79202-00(0.37*cfm, 21.3*inch Hg, 0.25*inch, 115*VAC, 1.6*amps, 60*Hz)
	EW-79202-30(0.37*cfm, 21.3*inch Hg, 0.25*inch, 120*VAC, 4.6*amps, 60*Hz)
```
> its free-air capacity, max vacuum, port size, power\
> its free-air capacity, max vacuum, port size, power

### tube vacuum
1. close **valve1_top** *(top flange valve)*

	- option to close **valve2_bottom** *(bottom flange valve)*

2. turn on **vacuum pump**
3. open **valve2_bottom** *(bottom flange valve)* slowly
4. wait when close to **-0.05*MPa**
5. close **valve2_bottom** *(bottom flange valve)*
> tube vacuum locked in

6. turn off **vacuum pump**

### break vacuum
1. turn off **vacuum pump** if needed
2. open *valve1_top** *(top flange valve)*
> purge with air

3. wait when close to **~0*MPa**
4. able to unscrew **lid** *(top outer flange)*

## closing
1. close furnace door
2. **power (black)** off
