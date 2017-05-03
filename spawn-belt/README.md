Spawn belt
=============

Spawn a fully compressed belt of any item, configurable by chest and/or circuit network.

With chest
-------------
Place a chest behind the spawn belt and it will spawn the item type that was last found in the first slot of the chest

With circuit network
-------------
Connect the spawn belt using a red or green wire and send a signal to it, it will spawn the item with the highest signal count, regardless of green/red color.

# Changelog
### 1.0.0
* Added circuit network listeners for spawn belt and performance improvements
### 1.0.1
* Fixed a occasional crash when placing a belt after you've removed all others.
### 1.0.2
* Fixed error caused by scripting change in 0.13.11, this version may not work with older versions of factorio
### 1.0.3
* Changed factorio version to 0.14
### 1.0.4
* Support for 0.15
* Added item descriptions