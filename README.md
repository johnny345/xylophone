# xylophone - this is a 7 note keyboard that uses Javascript for the music, a div container for the layout, and CSS for the design.  
Web Audio API.  
This code creates an audio context and a map of note names to frequencies.
It then adds a click event listener to each note, which creates an oscillator node,
 sets its frequency to the note's frequency, creates a gain node,
 and connects the nodes to the audio context's destination. 
It also adds an active class to the note to show that it's active, and stops the oscillator after .75 seconds.
