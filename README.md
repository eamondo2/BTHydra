# BTHydra
A hub allowing for pairing of multiple bluetooth speakers to a single node, divisible by stereo channels.

The project is based on a raspberry pi, or any small form factor linux hardware that can handle multiple streams of audio. The plan is to have a monitoring script tied into a hardware button that will scrape for nearby bluetooth audio endpoints, pair to them (using one of the array of bluetooth adapters), create an audio endpoint, and then assign that speaker either left channel, right channel or mix. 

Theoretically, there would be an audio cue when a new speaker is connected, played over the speaker itself, prompting for user input on the hardware buttons. 

This project has almost no progress so far.

I plan to use Jack audio (or  JACK 2, whichever version works the easiest) along with python scripting to handle the pairing, and audio routing. Also, unless Jack has an option to filter stereo channels per stream, I will have to figure out to handle that within python. 

The end goal is to allow this single node (integrated into a speaker, to make it useful as is) to collect a number of satellite speakers, and effectively increase the sound output while keeping the cost of the individual speaker low. Cheap bluetooth speakers are easy to find, and generally sound okay at medium volume levels. However, if you try to get much more from them, they become tinny and distorted. If there is a network of five or six such speakers distributed in an area, all playing one synched audio track, the effective output volume over that area is increased without having to hit the upper limit of the speaker's capacity.
