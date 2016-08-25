# KinectHolographic
Holographic effect for use with KinecV2 with ms sdk package in Unity3d

Video -https://www.youtube.com/watch?v=4s51IIjSQsw

Code adapted from - https://en.wikibooks.org/wiki/Cg_Programming/Unity/Projection_for_Virtual_Reality
Kinect v2 with MS-SDK - https://www.assetstore.unity3d.com/en/#!/content/18708
Dimples(used in video) - https://www.assetstore.unity3d.com/en/#!/content/19735

**Important before adding file from here to your project  you will have to have the package Kinectv2 with MS-SDK 
otherwise you will end up with errors

If you wish to use the script in your own scene, then first setup the scene as you wish,
then in front of the camera create an 'Plane' make sure the plane fits exactly in front of the camera covering the entire game view. then put off the renderer of the plane.

Next create an empty at the position of the camera and set it as the parent of the camera.
Drop the projection matrix script on the camera and add the 'Plane' as the 'projection screen'.

Put the Headtrack.cs script on the parent that was created for the camera. you will not have any control over the parameter of the camera at this point. it will adjust itself. so all modifications to transform have to happen on the empty parent.

And yes, you need the Kinect Manager script.
