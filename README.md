SPECLOG

This repository contains tools for interacting with and logging data<br>
from instruments in the SpecLab.

Example usage:

&nbsp;&nbsp;This will eventually work something like this:<br>
&nbsp;&nbsp;`$ speclog -d mb -i 5 -t 3600 outputfile.log`

Options:<br>
&nbsp;&nbsp;-d name &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; device to log<br>
&nbsp;&nbsp;-i seconds &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; interval between log entries<br>
&nbsp;&nbsp;-t seconds &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; total time to log <br>

To clone this repository:<br>
&nbsp;&nbsp;hg clone https://bitbucket.org/tjcrone/speclab

To update to a certain tag (version):<br>
&nbsp;&nbsp;hg pull && hg update v0.1

Requirements:


Author:<br>
&nbsp;&nbsp;Timothy Crone (tjcrone@gmail.com)
