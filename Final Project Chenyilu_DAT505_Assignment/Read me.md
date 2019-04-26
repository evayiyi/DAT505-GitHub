Name:Chen yilu Student ID:B161006061
Description
This work aims to provide a simple three-dimensional scene, through friendly human-computer interaction (rotation, zooming, object capture), to show the progress of the development of modern programs.

1. Firstly, six images are provided to simulate the real sky and its surroundings.



2. Then, according to certain rules and random number algorithm, some small squares with random positions and colors are obtained.


3. Next, light is added to the three-dimensional scene so that we can see these objects and provide alternate shades of light and shade.


4. Finally, a camera is put in to simulate human eyes and observe these objects from different angles and positions. It also provides a series of control effects, enabling us to control the position of the camera (rotation and zooming), while the camera is also automatically rotated around the central axis.


5. Browser renders each frame at the same time, add the mouse position judgment (object capture), if there are small blocks, it will become red, at the same time, make the last red box back to its own color.

6. The browser loads audio and plays it.


Usage
The folder root directory has the following structure:




1. Index. html is the page we visited.

2. Backgroundsound. wav is background music for direct loading of HTML

Because the browser's security restriction policy does not allow browsers to access local files, it is necessary to install software to build the server.



1. Double-click nginx.exe

2. Browser input localhost