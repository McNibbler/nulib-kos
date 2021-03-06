# nulib-kos

A library of useful stuff for KerboScript.

This will primarily include:

 - Math functions
 - Functions for orbital mechanics calculations

Pull request guidlines:

 - New functions/scripts should largely not directly change the steering
   or throttle of the ship.
 - Orbital manouver functions should return a manouver node that can be added to
   the manouver list by the user and executed with the exec_node script.
 - Orbital mechanics calculations should be factored out of manouver node
   creation functions into separate functions when possible.
 - Stuff in here should be usable as library functions / scripts and should
   not require editing to be useful.
 - Each thing (script / function) should have an Author statement and should provide
   attribution for any external code referenced / copied.

Currently unwanted scripts:

 - Launch
 - Land

Wanted scripts / functions:

 - Autowarp to time.
 - Time <=> True Anomaly, relative to periapsis
