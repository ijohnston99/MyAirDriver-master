radioThermostatDriver
=====================

This driver interfaces is design to interface with the Advantage Air MyAir 3. 
It's a first attempt based on theminor radiothermostatdriver

To get the thermostat modes working, you need to add a "state" for each possible operating mode in each "device" created. To do this, after installing the driver, log into your "classic" dashboard (that is, not the beta dashboard) and first find the "radioThermostatDriver - Thermostat Operating Mode" device. Click the little configure menu and "Add New State". Do this to add these states:

<ul>
<li>Thermostat Mode Off</li>
<li>Thermostat Heat Mode</li>
<li>Thermostat Cool Mode</li>
<li>Thermostat Auto Mode</li>
<li>Thermostat Mode Unknown</li>
</ul>
Next, add these states to the "radioThermostatDriver - Thermostat Fan Operating Mode" device:
<ul>
<li>Thermostat Fan Auto Mode</li>
<li>Thermostat Fan Mode On</li>
<li>Thermostat Fan Auto/Circ</li>
<li>Thermostat Fan Unknown</li>
</ul>
And for "radioThermostatDriver - Thermostat Hold Mode", add:
<ul>
<li>Thermostat Hold Disabled</li>
<li>Thermostat Hold Enabled</li>
<li>Thermostat Hold Unknown</li>
</ul>
