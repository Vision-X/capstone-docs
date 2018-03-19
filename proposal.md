# Project Proposal: CAPSTONE - VR BeatLab

---
[https://github.com/Vision-X/React-VR-Drums-WorkingModel] working model of objects and sound triggers in React-VR

## Project Description

#### VR BeatLab
-- Experience interactive drum machine basics through WebVR. Use your existing headset and supported controllers to be immersed inside a world of sound and visual feedback.
-- Don't just listen to music; make your own and feel it come alive in VR BeatLab.


## Problem Statement

Making use of expensive HMD VR headsets is all about finding the experience for you. With so much invested in their HMD it is imperative that 3-D modeled tools in VR are capable of giving the user an experience very similar to real-world music hardware - without having to invest tons of money - and with a lot more panache. VR BeatLab aims to serve those owners who love music and want to feel what it's like to make your own beats - in VR - and to visually and aurally experience this interaction.

## How will you solve this problem?

VR BeatLab is a simple interface within a VR framework that provides various sound triggers (pads). Interacting with these pads in VR will invite the user to explore visual and auditory feedback through these trigger pads. Interacting with the touch controller, the user is able to command sounds as they touch the triggers, visually see and feel the  audio play, and find themselves in a world full of color and sound. Advanced experience includes a 2-bar loop feature for recording small sequences of music and offering playback for the user to enjoy their composition(s).


## Map the user experience

1. Users will interact with the site using their preferred HMD unit (Oculus Rift). Using their controller, they will interact with 3-D objects presented to them and trigger sounds + visuals.
2. Users will select between sound libraries to render new sound sets to the 3-D objects, giving them some freedom to create with sounds they enjoy.
3. (Stretch) Users will enter a Record mode where they can live record their beat. When recording is finished, an option to playback their creation and experience 'additive' music building via playing along to their loop. The user can then choose to export their creation or save it to the DB.

## What technologies do you plan to use?

#### Hardware
-- Oculus Rift
-- Headphones

#### Front End
-- HTML/CSS
-- React / React-VR
-- A-Frame (WebVR/WebGL/THREEjs)

#### Back End
-- Node
-- Express
-- Knex
-- pSQL

#### A-frame Libraries/Resources
a. 3-D Dev Tools - https://www.npmjs.com/package/aframe-dev-components#npm
b. Location persistence - https://www.npmjs.com/package/aframe-location-persistance-component
c. Keyboard controls - https://www.npmjs.com/package/aframe-keyboard-controls
d. Audio Visualizer - https://www.npmjs.com/package/aframe-audioanalyser-component
e. Metronome - https://www.npmjs.com/package/aframe-metronome-component
f. GUI widgets - https://www.npmjs.com/package/aframe-gui
g. Oculus Control integration - https://www.npmjs.com/package/aframe-controller-cursor-component
e. BlockVR Asset Creation - https://vr.google.com/blocks/

## MVP
The Minimum viable product for this project is to have an interactive set of drum triggers on various objects. On trigger, the object and the larger panorama should display visual effects associated with the triggered sound. The user will be able to change between a few pre-made sound libraries that will be mapped to the trigger objects. A very minimal environment will be build around the user - with room for visualizer and a GUI for changing sound-sets.

(first iteration is click events, then keyboard events, then Rift controller interaction)

## STRETCH GOALS
By Order And Importance:
1. Custom room environment and 3-D models (built with BlockVR)
2. Step Sequencer / Live Recording for 2-bar loop
3. Loop playback environment
4. Save / Export loops
5. youtube "play-a-long"
6. Gameification - Guitar Hero clone? (so stretchhhhh)
