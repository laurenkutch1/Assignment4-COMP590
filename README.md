# Assignment4-COMP590
For this assignment, I built and deployed a small VR game to the Meta Quest 3. 
The scene has a pedestal with a ball on it and a pyramid of six cubes standing about three meters away. 
The goal is simple: pick up the ball and throw it at the pyramid to knock the cubes down.

## Demo Video: [https://drive.google.com/file/d/1UNEzSIVkU6FsKjALt1Tbno-ELbONrjW8/view?usp=sharing](https://drive.google.com/file/d/1UNEzSIVkU6FsKjALt1Tbno-ELbONrjW8/view?usp=sharing)
The video shows the project running on the Quest. Please skip ahead to 1:20 for times sake to see the bowling ball in action.
This is also my apk, the file was so big it wouldnt upload on here so I uploaded it as a release, not sure if that is right
https://github.com/laurenkutch1/Assignment4-COMP590/releases/tag/Assignment4APK


## How to Play: 
Reach out with a controller and hold the grip button to pick up the ball. 
Swing your arm toward the pyramid and let go of the grip partway through the swing to throw it. 
The ball and cubes use Unity's physics, so how hard and how accurately you throw changes how the cubes fall.


## Logistics:
The project uses Unity 6.5 with the Universal 3D (URP) template and the Meta XR All-in-One SDK. 
I used Meta's Building Blocks to add the camera rig, controller tracking, and grab interaction, and gave the ball and cubes Rigidbody components so they react realistically. 
I developed on a Mac, so there was no Link mode, and every test was a full build and deploy to the headset.
I followed Meta's Quest Unity setup tutorial from the assignment and the Meta developer documentation: https://developers.meta.com/horizon/develop
