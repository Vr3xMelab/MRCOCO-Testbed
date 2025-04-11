**MRCOCO Testbed**
===============================

This repository extends the official OculusUnity "**Unity-SharedSpatialAnchors v63**" by unity at this link: https://github.com/oculus-samples/Unity-SharedSpatialAnchors/tree/47c26521e7711c3d9ac9dc2bd27951e12f29226c demo with a set of custom components that enable a co-located dual-user collaborative configuration experience in Mixed Reality (MR).

The project was developed as part of a research prototype focused on collaborative decision-making and co-presence, using Meta Quest 3 devices and the Unity engine.

---

Custom Component
----------------

 - Toggle.cs: Enables UI toggle on/off via index finger gestures.
 - DraggableSphere.cs: Allows drag & drop of color spheres via pinch gesture. Applies color in real-time to 3D model parts using collision triggers and Unity tags.

---

Setup
-----

This project use Unity version 6000.0.37f1
 Create an account on Photon Engine "https://www.photonengine.com/" go to create new app ->  choose FUSION -> and give a name -> copy the APP ID and paste on unity

----

***This part is copied from the github page of UnitySSA***
----------------------------------------------------------


**Unity-SharedSpatialAnchors** was built to demonstrate how to use the Shared Spatial Anchors API, available in the Meta XR Core SDK for the Unity game engine.

The sample app showcases:

    Spatial Anchor Creation, Saving, Loading, and Sharing

This app uses Photon Unity Networking to share anchor data and support interaction with networked objects in a colocated space.

This codebase is available both as a reference and as a template for a project that utilizes shared spatial anchors. Unity-SharedSpatialAnchors is under the license found here unless otherwise specified.
SETUP

You must follow these instructions first: https://developer.oculus.com/documentation/unity/unity-ssa-sf/
Documentation

Sample App Architecture: https://developer.oculus.com/documentation/unity/unity-ssa-sf/

Scene Sharing: https://developer.oculus.com/documentation/unity/unity-shared-scene-sample/

Health & Safety: https://developer.oculus.com/resources/unity-ssa-hs-app/

See the CONTRIBUTING file for how to help out.
