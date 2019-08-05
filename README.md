## important session points
1. install `ack`:
	1. `curl https://beyondgrep.com/ack-v3.0.2 > ~/bin/ack && chmod 0755 ~/bin/ack`
	2. [Install](https://beyondgrep.com/install/)
1. Set up `$HOME/.ackrc`:
		```
		--with-filename
		--pager=less -RFX
		--color
		```
1. create temporary bash function - regex() { echo $1 | ack $2 ; }

## helpful links
1. [ack man page](https://beyondgrep.com/documentation/ack-v3.0.2-man.html)
2. [perl regex documentation](https://perldoc.perl.org/perlretut.html)
