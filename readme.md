# hollywood
runs a bunch of noisy shell scripts like what hollywood hacking looks like

Launch Byobu
Open a random number of splits, random sizes
In each split, run a noisy text app

## Rules:
 - Must work as a non-root user
 - Must display information indefinitely (a la "watch", or cmatrix)
   + Can use a while/true + a timeout
 - Must not OOM a system
 - Must not over load a system
 - Must not be too egregious with I/O
 - Must not require outbound internet access

## Sample Apps:
 - atop		# xxx Root
 - bmon		# DONE
 - cmatrix	# DONE
 - dnstop	# xxx Root
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
