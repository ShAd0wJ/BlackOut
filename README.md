This document serves as an example file executable to extinguish all services around the user. All wifi, cell service (3G/4G/5G) will cease to function
and will return to normal if the target has moved out of range of the user or the user exits the program. The program will need to be run as root
as it needs root privilages to run certain operational functions such as the Airmon-ng suit. The Program is called BlackOut for the time being
but would be percieved as a malicious program if spotted, so should be renamed if you intend to use as a malicious tool. To give the executable functionality
run "sudo chmod u+x BlackOut", at which point you should run "ls -l" to see if the file has indeed gained the privaliges that it needs. You can
run BlackOut by typing "./BlackOut" in the console.

If you run Blackout without any arguments, it will continuously kill all networks in the area around you. 


Additional arguments(optional)
-r --router	kill all routers and hotspots, ignore cellphones
-c --cell	kill all cellphones, ignore routers and hotspots
-lr --list	lists all routers around you
-lc --listc	lists all cellphones around you
-l --list	list all available networks, cellphones included, around you

