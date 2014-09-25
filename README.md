Battery Operated Arduino Thermometer (B.O.A.T.)
==============

Similar to Moteino/Anarduino, an Arduino-compatiblish uC board with onboard
RFM69CW, SMA edge connector, and i2c thermometer chip. Powered by CR2032
batter. No onboard voltage regulation, so don't plug into 5V unless you need a
doorstop (the ATMega will be fine, but the wireless card and thermometer are
only specced for 3.6V max).

Yes, there are many Arduino-based wireless sensor projects out there. Most use
2.4GHz radios, however, and that's getting to be an awful crowded band,
especially if one lives in an apartment building. To avoid making that even
worse, I choose to use one of the other ISM bands, specifically 433MHz. This is
normally used for stuff like garage door openers and the like. (Also military
radar, which makes for some hilarious anecdotes).

Anyway, I decided to build my own board for this, even if other designs exist
that are probably better in just about every way. But this one is my own
special snowflake. It even has a cow on it! (Don't judge me.)

Licensed under the Creative Commons Attribution-ShareAlike License
(CC-BY-SA-4.0)
