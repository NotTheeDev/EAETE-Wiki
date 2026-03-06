<UPDATE VERSION="0.3.0">
+ Translated most of the valves (if missing report them)
+ Fixed LSd + LSc stucked after activating
+ Added jump delay between jumps
+ Added UT system for pneumaticly operated valves in PC
+ Added isolation valves for SG continuous and sludge blowdown
+ Added continous blowdown for SG
	> Technicly should prevent high water levels during start-up
+ Added TG systém (spent fuel pools)
	> Preaty much just fun to watch, but without circulation small amount of heat is 
		generated ;)
+ Valves with regulation, show setpoint and actual position
+ AZR added for TK pumps
	> AZR - Automaticky switch between pumps when working pump switches off
+ Fixed reverse power protection actuating as soon as turbine trips
+ Reworked signal system backend (May cause few bugs)
<UPDATE VERSION="0.2.17">
+ Fixed 1RM55D001 name
+ Fixed PZR temperature mode
+ Fixed LSa,b,c,d signals block not working
+ Fixed YP10W01,02 + YP13S02 PID controller
+ Fixed initial conditions not setting PZR heaters to AUT
+ Added TK10B01 automatics
+ WestNet command output rework
+ Fixed switches locations not replicating
+ Until signals can be user block moved LSa GEN not closed to 55%
<UPDATE VERSION="0.2.15">
+ Fixed links for MCP
+ Fixed switches broke after 1 use / snap switches stays at location
+ Fixed controls light set trying to index function with number
+ Fixed AZR index nil with number
<UPDATE VERSION="0.2.14">
+ Fixed BD voltage indicators
+ Control rod drive mechanism / AC or DC power loss annunciator fixed
+ Control rods unit now shows only decimal
+ Fixed indicator name CX01.UV1 -> CW01.UV1
+ PZR labels translated
+ Turbine rundown is now 80 minutes