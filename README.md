# BTHydra
A hub allowing for pairing of multiple bluetooth speakers to a single node, divisible by stereo channels.

The project is based on a raspberry pi, or any small form factor linux hardware that can handle multiple streams of audio. The plan is to have a monitoring script tied into a hardware button that will scrape for nearby bluetooth audio endpoints, pair to them (using one of the array of bluetooth adapters), create an audio endpoint, and then assign that speaker either left channel, right channel or mix. 

Theoretically, there would be an audio cue when a new speaker is connected, played over the speaker itself, prompting for user input on the hardware buttons. 

This project has almost no progress so far.

I plan to use Jack audio (or  JACK 2, whichever version works the easiest) along with python scripting to handle the pairing, and audio routing. Also, unless Jack has an option to filter stereo channels per stream, I will have to figure out to handle that within python. 


