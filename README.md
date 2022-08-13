# PacMen Exercise
> This project uses Object Orientation, Loops, Arrays, DOM Manipulation and Timers to:
> 1) Add PacMen to the screen.
> 2) Make them move in random directions, within the screen window.


## Table of Contents
* [Setup](#setup)
* [Usage](#usage)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)


## Setup
- On Github, navigate to the main page of this repository.
- On the top right of the list of files, click the green button, titled 'Code'.
- Copy the URL by clicking on the clipboard button.
- Open Gitbash.
- Change the current working directory to where you want the cloned directory.
- Type:  $ git clone https://github.com/Mitsananikone/Pacmen.
- Press 'Enter' to create your local clone.
- Run index.html.

## Usage
Once index.html is open, you will see a blank screen with 2 buttons in the top left corner.
- <b>Add PacMan:</b>  
This button creates an 'img' element, a 'PacMan object', and appends it to the div class 'game'. <br />
It also randomly initializes the PacMan object with values such as 'Direction', 'Velocity', 'Focus'.
More PacMen are created every time the button is pressed. <br />
The PacMen are currently stationary. <br />
- <b>Start Game:</b><br />
This button animates the Pacmen. <br />
Using the values given to the PacMen, the image(s) move along their pre-defined trajectories.  <br />


## Room for Improvement
One feature I added to the original exercise was making the PacMen face the direction they are moving towards. <br />
Another feature was using the 4 PacMen images to open and close his/their mouth(s). <br />
There was a challenge in getting ALL PacMen to turn around individually, instead of as a group. 


Room for improvement:
- Make all individual PacMen turn around once they bounce back against the wall. <br />
To do:
- Add some "wakka wakka" sound effects when the Pacmen "chomp"


## Acknowledgements
- This project was inspired by Week 3 of the M.I.T Fullstack Developer Bootcamp


## Contact
Created by [@mitsananikone(https://mitsananikone.github.io/) - feel free to contact me!


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
