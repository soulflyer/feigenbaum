# Feigenbaum experiments

After the work of Mitchell Feigenbaum. See https://en.wikipedia.org/wiki/Feigenbaum_function

## Setup

Download and install pd from https://puredata.info/downloads/pure-data

requires the Modal_Object_Library written by Vincent Joseph Manzo which is included here in the lib directory. Check out the licence agreement therin if you want to make use of it. Install this library in a copy of vanilla pd and you should be good to go.
Just dragging all the files in lib to the `externals` folder specified in the Pd path settings works.
It also needs the cyclone library installing. This can be installed using the find externals entry on the help menu.

Open the file feigenbaum-experiment.pd

Just below the keyboard is a number entry box that takes a value to set the note length. 200 works ok.
Select a mode. (Should see the numbers below the modal-change box change from 0) You may need to click on reset too, and the green button to start it. Drag the slider across to the right to introduce some chaos. 

Note that this generates midi notes, not sounds, so you will also need to connect it up to a midiplayer of some kind. That's a whole can of worms. Once you have something running that will take midi input, select it in `Pd:Preferences:Midi`
