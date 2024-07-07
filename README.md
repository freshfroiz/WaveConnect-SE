# WaveConnect SE

![WC-SE Logo](https://github.com/freshfroiz/WaveConnect-SE/blob/main/App%20Splash.png?raw=true)

WaveConnect SE is a Python program that allows you to connect your MIDI keyboard into Scratch, using keyboard shortcuts.
At the moment, it is limited to note presses from MIDI note 48-72, however this will be changed in the full version.

# How to setup

1. Install the latest release [here](https://github.com/freshfroiz/WaveConnect-SE/releases/)
2. Load up the .PY file. It will automatically install the PIP packages. If it doesn't, open the command line and run
  `pip install requirements.py`
3. Now, open [this project](https://scratch.mit.edu/projects/1045527127/). Hitting keys on the keyboard should trigger the Activity LED, and will show up in the MIDI Monitor section.
4. If you want to add WaveConnect SE to your project, you need to backup the sprite, and drag it into your project. It will add the `MIDIActivity` broadcast, as well as the `LatestMIDINote` variable, which can be used to trigger custom notes.
