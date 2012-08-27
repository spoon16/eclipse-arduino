There is [a very thorough tutorial](http://arduino.cc/playground/Code/Eclipse) on getting your Arduino and Eclipse to play nicely together.  This repository represents the results of my following that tutorial and may save you a lot of time.

I tested this on OSX Mountain Lion running Eclipse Indigo with an Arduino Uno... so... ship it!

- Install Eclipse
- Install AVR Eclipse Plugin (I did it via the Marketplace)
- Install the [CrossPack for AVR Development](http://www.obdev.at/products/crosspack/index.html)
- Clone this repo locally
- Use the 'workspace' directory in this repo as the Eclipse workspace, or merge the contents with your existing workspace
- Import 'ArduinoCore' and 'Blink' directories as projects
- Build All from the Project menu
- Plug your Arduino in
- With 'Blink' selected in the project list click on the AVR button in the tool bar to make sure that firmware can be loaded to your board

#### Troubles?

- The port in the AVR configuration may be off.  Double check Blink Project -> Properties -> AVR -> AVRDude -> Edit -> Override Default Port
- [RTFM](http://arduino.cc/playground/Code/Eclipse)

#### Ideas?

I'm happy to accept pull requests if anyone thinks this is useful and wants to make it beter.