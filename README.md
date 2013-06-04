vio
===

VIO provides an extremely simple C++ API to 

- Read video sources, including files, cameras and http streams,  frame by frame
- Write video to output sinks, including screen and files 
- Do quickly some simple things such as scaling, tiling and superimposing text.


VIO relies heavily in other libraries that "do the job", including:

- ffmpeg
- freeglut
- boost_multiarray

Frames are accesible as three dimensional boost_multiarray objects. This enables 
- direct access of elements through a simple one-dimensional pointer
- indexed-based access
- complex views access of parts of the frame









