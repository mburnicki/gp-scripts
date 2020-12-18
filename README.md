# gp-scripts Collection

A collection of 'gnuplot' scripts that can be used to plot data from
various log file formats, e.g. the `loopstats` files created by ntpd.

See the top of the individual script files for details.


## Installation

Run `./install` from the base directory to create symbolic links
in `/usr/local/bin/` that point to the individual scripts.
Afterwards, the scripts can be called from within any directory,
e.g. the directory where the data files are located.

Please note that `sudo` or `su` may be required when running
the `install` script because `root` permissions may be required
to create the symbolic links.

----

(c) Martin Burnicki <martin.burnicki@meinberg.de>
