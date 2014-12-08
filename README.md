cs16_server Dockerfile
===========

CounterStrike 1.6 Dedicated Server Docker Image

This dockerfile uses the Daniel Gibbs' [linuxgameservers scripts](https://github.com/dgibbs64/linuxgameservers) to start an instance of Valve's CounterStrike 1.6 linux server. Settings passed onto the server during runtime (such as defaultmap and servername) are environment variables that can be overriden when creating the Docker instance.

TODO:
* Instructions
* A mechanism to copy maps and deeper config files into the new instances. (probably through ADD commands)
