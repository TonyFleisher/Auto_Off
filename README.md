# Auto_Off

A Clone and Update of Mattias Fornander's Auto Off App for Hubitat, with acknowlegement of his original work.

This version converted Mattias Fornander's Auto Off to be a Parent/Child app instead of multiple instance. Once converted, features of Parent/child became possible, such as allowing a single "Debug" option to be distributed throughout the entire set of Children.

One major difference was that the original polls every minute looking for devices to turn off. This new version starts a timer when the switch turns On.

<ul>
<li>Auto_Off_c <i>is the child app that uses a Delay vs Poll for switches.</i></li>
<li>Auto_Off_o <i>is the child app that uses a Poll vs Delay for switches, for backwards compatability.</i></li>
<li>Auto_Off_d <i>is the child app that uses a Delay vs Poll for dimmers and is somewhat redundant because dimmers are switches too.</i></li>
</ul>
