# About Me
## Bio
<img src="assets/Best_Kevin.jpg" alt="headshot" width="200"/>

I am a Ph.D. candidate in the Robotics Department at the University of Michigan. My research focuses on the control algorithms of robotic knee-ankle prostheses and their effects on user outcomes. In general, I am interested in dynamics, the control of robotic systems, optimization, and the human motor control. 

# Projects

## Core Research
The list below highlights some of the core research projects that I have worked on during my time at Michigan Robotics. For my full list of publications, please reference my [Google Scholar](https://scholar.google.com/citations?user=P5lqq8YAAAAJ&hl=en). 

### Data-Driven Impedance Control For Knee-Ankle Prostheses
The prevailing paradigm in lower-limb robotic prosthesis control is to use hand-designed controllers with heuristically tuned behaviors. While these approaches can be very effective, they are labor-intensive in both the design of the behaviors and in individualizing them to each individual at the point-of-care. In this work, we instead developed a data-driven control architecture that allowed the prosthesis to work over continuums of tasks without requiring manual tuning. 

Learn more about our work in this video:

[![Controlling a Powered Knee-Ankle Prosthesis with Automatic Adjustments to Walking Speed and Incline](http://img.youtube.com/vi/Iin6UqeT14A/0.jpg)](https://www.youtube.com/watch?v=Iin6UqeT14A "Controlling a Powered Knee-Ankle Prosthesis with Automatic Adjustments to Walking Speed and Incline")

The main publication detailing this work can be found [here in the IEEE Transactions on Robotics](https://ieeexplore.ieee.org/document/10017125). We've also extended this approach to [sit/stand](https://ieeexplore.ieee.org/document/10268252) and [stair traversal](https://ieeexplore.ieee.org/document/10302427).

During the development of the controller, we also created a treadmill-based simulation of a local hiking trail to highlight the incline-adaptability of our controller. Here is the video:

[![A Virtual Dog Walk with a Robotic Prosthetic Leg](http://img.youtube.com/vi/ozBN2ZxVxxQ/0.jpg)](https://www.youtube.com/watch?v=ozBN2ZxVxxQ "A Virtual Dog Walk with a Robotic Prosthetic Leg")


### The Open-Source Leg (OSL)

The Open-Source Leg project aims to accelerate research in the field of lower-limb robotic prostheses by providing a common research platform to the field. [Senthur Ayyappan](https://senthurayyappan.github.io/), a rockstar mechanical designer and software engineer currently maintains and leads the project along with PI Elliott Rouse at the University of Michigan. Full CAD design files, software libraries, and other resources are available to the public to use free of charge.  See [www.opensourceleg.org](https://www.opensourceleg.org/) for more information. 

In addition to helping Senthur with the [OSL library development](https://github.com/neurobionics/opensourceleg), I've worked on creating controllers for the OSL. [This paper](https://ieeexplore.ieee.org/document/10807510) details a control approach I developed that accounts for some of the inherent drivetrain dynamics of the OSL, allowing to perform accurate impedance control. 
We've also released the Data-Driven Impedance Controller discussed above for public download from the [OSL Website](https://www.opensourceleg.org/control/research) so that other researchers can use it, benchmark against it, and build upon it. 

### Technology Commercialization in Partnership with Össur
We have worked with Össur, who is one of the leading manufacturers in prosthesis technology, to test our control algorithms on their commercial hardware. The video below shows our data-driven variable impedance controller deployed on the Össur Power Knee. A key feature of our controller is its phase variable that synchronizes the leg's behavior to the user's intent. This allows Andrew to volitionally control the leg and kick the ball: 

[![Kickball with user-synchronized control of the PowerKnee, a robotic prosthetic leg](http://img.youtube.com/vi/KYwz9VPTB7s/0.jpg)](https://www.youtube.com/watch?v=KYwz9VPTB7s "Kickball with user-synchronized control of the PowerKnee, a robotic prosthetic leg")


## Academic Class Projects
These are class projects that are outside my core research area that I created during grad school. 

### Contact-Implicit Differential Dynamic Programming
Coming soon

### Control of a Planar Ballbot with Obstacle Avoidance
![Ballbot animation](https://github.com/tkevinbest/Ballbot/blob/main/Documentation/gifs/TestMS_MPC_obstacle_AdobeExpress.gif)