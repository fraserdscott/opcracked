# OPCracked

This OPCraft fork slightly modifies the [official client](https://github.com/latticexyz/opcraft/tree/main/packages/client) to make you a omnipotent, flying, insta-mining god. 

Specifically, it: 

- Changes the max number of `airJumps` to from 2 to 999. Repeatedly press space to fly!
- Pauses the day/night cycle by setting the sun's `progress` to a fixed 0.25. Your client is perpetually midday :)
- Sets the `MINING_DURATION` to 10 milliseconds. No more holding down left click - mine blocks almost instantly.
- Removes the maximum "interaction" range by setting the `blockTestDistance` to 7100. Build and mine blocks any distance from your player.

Simply clone the repo and run `yarn start`, and it should sync with the official game instance. To play with your existing account, you will need to copy the private key into your localhost storage. 

Feel free to clone this client and hack it to your hearts desire!

_A [past commit](d3bec7eb78f52d8e30fe4ae263afea4a0bc21758) included x-ray vision (where all blocks render as glass, except Iron, Gold, and Diamonds), but ultimately I prefer to view the world normally._
