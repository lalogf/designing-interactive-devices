# Video Doorbell, Lab 7

*A lab report by John Q. Student*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[Video](https://drive.google.com/file/d/1TaUpiAxsfIT9osG89MXE-CrgUAV4e7gE/view?usp=sharing)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

`pictureServer.js` makes a call using socket.io to a function call takePicture and creates a file name for storing the image and stores it on the public folder to later transfer the picture file to the client, which then will be rendered in the html.

**b. Include a video of your working video doorbell**

[Video](https://www.useloom.com/share/ecd667ea238b4f2d85a93dcca3c4ae29)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I used [bootstrap](https://getbootstrap.com/) to add styles and responsive design to the layout.

**b. Upload a video of your working modified project**

Also use css to add filters to the pictures.
[Video](https://www.useloom.com/share/7c6df5324b0e4b8193ddd30922115f9c)

* Final code of the lab can be found in master and development branches [here](https://github.com/lalogf/IDD-Fa18-Lab7) 