python-auto-switcher
====================

## What's this?

It make you a happy if you tired to a problems python3/python2 incompatible.

## Switching Method

This is a very simple shell script. 

    python3 $1 $2 $3 $4 $5 $6 $7 $8 $9 || python2 $1 $2 $3 $4 $5 $6 $7 $8 $9

It's try execute python3 first. And try python2 if failed python3.

## How to Install(to your System)

1. you need get super user permission.
2. remove your python symbolic link.(maybe: /usr/bin/python)
3. copy or symbolic link to /usr/bin/python from this packages "bin/python.sh".

## How to Uninstall(from your System)

1. you need get the super user permission.
2. remove "/usr/bin/python"
3. (symbolic link to /usr/bin/python from python3 or python2 if you want.)

## License

- MIT/X11 <http://www.opensource.org/licenses/MIT>

## Contact

- GitHub <https://github.com/usagi/python-auto-switcher>
- Usagi Ito <usagi@WonderRabbitProject.net>
- Wonder Rabbit Project <http://WonderRabbitProject.net/>

