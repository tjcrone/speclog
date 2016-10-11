SPECLOG

This repository contains a tool for interacting with and logging data
from cameras and instruments in the SpecLab.

Example usage:

  This will eventually work something like this:
  > speclog -i ir -t 3600 outputfile.log

Options:
 -i name         instrument to log
 -t seconds      time to log	

To clone this repository:
 hg clone https://bitbucket.org/tjcrone/speclab

To update to a certain tag (version):
 hg pull && hg update v0.1

Requirements:


Author:
 Timothy Crone (tjcrone@gmail.com)
