# Capstone Project

Note: abstract can be found [here](http://www.ece.neu.edu/sites/default/files/pdfs/ece/capstone_design_abstracts_spring_2016_0.pdf) under "Eos Link". Neil took some pictures throughout the project shown [here](http://www.neildave.org/#/pneumatic-augmented-reality-tactile-feedback-system/)

Teddy, Sasha, Sean, Neil, Amery

### Developer Setup Instructions

Install [Processing 3](https://processing.org/download/?processing) preferably for all users

Clone this repository to your processing sketchbook location (File --> Preferences --> Sketchbook Location)

Clone the [Leap Motion Processing Library](https://github.com/nok/leap-motion-processing) to your sketchbook location's libraries folder

Create a symbolic link from "leap-motion-processing" to "LeapMotionForProcessing"

Windows Symbolic Link Command:
```
mklink /j ...\libraries\LeapMotionForProcessing ...\libraries\leap-motion-processing
```

#### Additional Instructions for Sublime Text

Install [Sublime Text 3](http://www.sublimetext.com/3)

Launch Sublime Text 3 and go to (Preferences --> Settings - User) and add the following lines to the hash
```
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "spell_check": true
```
Next type ctrl and ` to open the Sublime Console

Enter the Sublime Text 3 [Package Control](https://packagecontrol.io/installation) text into the console

After the installation of the Package Controller is done restart Sublime

Then install the Sublime Text Processing Package (Preferences --> Package Control --> Install Package --> Processing)

Add Processing 3 folder to your System's PATH as shown [here](https://github.com/b-g/processing-sublime)

Restart Sublime one more time

Open the Capstone repository in Sublime and build the project (Tools --> Build)

### Other Resources

Processing Serial Documentation:

https://processing.org/reference/libraries/serial/index.html
