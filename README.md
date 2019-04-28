x2grbl
======

This software represents a frontend to the famous grbl cnc controller.


### Remarks

To make this software work you need a slightly modified version of grbl.

You can find this at:
    http://server3.9mal6.de:3000/wilhe_jo/Grbl2.5d


You'd want to set a start-up-script for grbl:
<pre>
CONTROL-X
$H
G10 L20 P1 X-50y-50z25
G0X0Y0Z0F1000
$$
</pre>

This resets grbl, home the cnc and sets 50,50,-25 to the new origin of the machine.

### License

This work is licensed under the
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/.


If you want to use this software in a commercial product please contact the maintainer.
# Ultimaker2CloneFFF
# lukastest
