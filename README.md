# Everything You Love (demo)
A demo of the "Everything You Love Will One Day Be Taken From You" software from the Book of Knowledge of Impractical Musical Devices project. This patch slowly destroys the sound that is contained within it.

This is a desktop-friendly version of a standalone instrument. For more background about it: http://www.impracticaldevices.com/volume-3/

How does it work?
This patch contains a sound that you can listen to.
The sound playback is done through two wavetables, one for each channel. Click the toggle to play loops the sound. Each time the sound is looped a random "glitch" is written into the wavetables, glitching the playback of the sound, which then overwrites the original sound in the array (with a short delay to account for the current playback). The patch is automatically saved on each loop. 
I'm not entirely sure why the sound ends up disappearing, I suspect this has to do with the delay that I'm using to offset the overwriting of the sound. The wavetable glitching method makes the glitches recognisable as part of the original sound, and it is relatively easy to adjust the parameters of the random numbers that are being sent to the wavetable to change how quickly the sound deteriorates.
