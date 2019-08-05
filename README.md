**regex** : a regular expression is a template that is used to determine if a string has certain characteristics.

## important session points
1. install `ack`:
	1. `curl https://beyondgrep.com/ack-v3.0.2 > ~/bin/ack && chmod 0755 ~/bin/ack`
	2. [Install](https://beyondgrep.com/install/)
1. Set up `$HOME/.ackrc`:
```bash
--with-filename
--pager=less -RFX
--color
```
1. create temporary bash function - regex() { echo $1 | ack $2 - ; }

## topics
1. Simple word matching:
	1. use shell vars:
```bash
foo = something
echo "some string" | ack "$foo" -
```
	1. metacharacters: `{}[]()^$.|*+?-#\`
		1. Escaping metacharacters
		1. Escaping escape sequences


## helpful links
1. [ack man page](https://beyondgrep.com/documentation/ack-v3.0.2-man.html)
2. [perl regex documentation](https://perldoc.perl.org/perlretut.html)
