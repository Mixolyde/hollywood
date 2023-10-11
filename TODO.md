# Features 
* Ensure no module fails if the command is not installed
* Always create windows greater than a minimum size
  (many ncurses programs will complain if the window is too small)
* Factorize 'trap' commands into a common function
* Don't depend on $RANDOM (so that we can use $SHELL)
* Convert usage of locate to find
* Cleaner shutdown

# Bugs
* Use named tmux session to avoid collisions

# Modules To Improve
- [ ] Random colors for cmatrix

# Modules To Add
 - dnstop	- _requires root to run_
 - ethstatus
 - glances
 - htop
 - ifstat
 - iotop
 - iptotal
 - iptraf-ng
 - itop
 - jnettop
 - kerneltop
 - latencytop
 - logtop
 - netmrg
 - nload
 - nmon
 - ntop
 - powertop
 - sagan
 - slurm
 - snetz
 - top
 - tiptop
 - vnstat

