# xtal-medusa

Data Bending: Video Steganography/Steganalysis for high compressed video files in C++ using DCT and Pixel Value Differencing. 

xtal-medusa hides any binary data inside of a video file using steganography. Changes to the video are undetectable and do not alter the video's file size. Stronger embedding strengths result in a scotoma-like blur in the video stream.

Features functionality for basic error checking.

Performs statistical detection using K-means.

I'm in the process of refactoring this in C++ since there will probably be an upcoming lack of support for Delphi for Linux/BSD, 
(and those are primarily Windows Languages)

TODO:

Write a tutorial with screenshots.

I also need to make it more "user friendly".

Requirements:

Requires Windows and an IDE that can build C# Applications ofc..
Requires ffmpeg to be in the same directory as the executable.
The video input format has to be in raw YUV.

Once video steganography is performed, you can re-convert the video to a secondary format MPEG-4, H.264/265, WebM, even upload to YouTube and recover the hidden file with no error.

It works and runs  but it is not user friendly. I'm sorry, if you have questions:
Email network (dot) succubus (at) gmail (dot) com
