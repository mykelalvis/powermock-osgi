# 1.5.6.0 #
  * Updated powermock to 1.5.6 version.
  * Replaced custom JUnit with the bundle from Orbit - manifest is ok now
  * Replaced custom Hamcrest Core with the bundle from Orbit - manifest is ok now

# 1.5.4.1 #
Still based on Powermock 1.5.4
### Fixes ###
[#2](https://code.google.com/p/powermock-osgi/issues/detail?id=2) the Hamcrest Core library now exports org.hamcrest as split package
### Notes ###
Ugly way the hamcrest bundle version and remained the same, so please cleanup the Tycho and Eclipse bundle pools.


# 1.5.4 #
Initial release based on Powermock 1.5.4