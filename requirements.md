---
layout: page
title: Project Requirements
subtitle: Team 4
---

**Product Requirements Document (PRD)**

Summary of the project (1 Paragraph)- summarize your project proposal)

For this project, we will be creating a MagicMirror that will show a user’s reflection and information displayed on an internal computer monitor through a Raspberry Pi 3. There is an open-source repository on Github implemented in Javascript that we will be building on top on. The main feature that will be implemented is a user profile system that will be driven by an attached camera and OpenCV. A user will be able to stand in front of the mirror and have his face scanned. If the user has a previously made customized profile, the mirror will load that specific user’s profile. If not, the camera will take pictures in order to train the system for a new user and their profile. We will also build a web application that can be used to customize the profile of each user.

Deliverables (what are you going to show at the end)

* Web App for profile customization

* Profiles for MagicMirror saved/loaded through facial recognition

* Profile training system to create new user profiles

Critical Features

* Motion Gesture controlled

* Facial Recognition training to create a user profile

* Loading of MagicMirror profile

* Camera that detects face, takes picture, and compares to a previously saved photo

* Sync notes/reminders from phone/profile to display on mirror

* Proximity Sensor to control On/Off state using the camera

* Display basic information:

    * Time

    * Date

    * Weather

Performance Metrics

* Face/profile is recognized correctly 95% of the time

* User is logged on/out correctly

* User profile creation is automated correctly

* SmartMirror can run for 3+ hours without crashing

Milestones

* Week 3 (4/13):

* Week 4 (4/20): Facial Detection Implementation loads/saves profiles

* Week 5 (4/27): 

* Week 6 (5/4): Gesture Control customizes module placements

* Week 7 (5/11): Proximity Sensor through camera controls On/Off state

* Week 8 (5/18): Customization Web App implemented and connected

* Week 9 (5/25):

* Week 10 (6/1): Mount monitor and Raspberry Pi in the frame, finalize mirror

Team Member Responsibilities

* Brad:

* Brandon:

* Kurtis:

* Ryan:

Outside Help Needed

* Josh Fromm for Computer Vision help

Materials/Budget

* Camera: $34.80

* 2 Way Mirror Film: $26.76

* Acrylic Screen: ~$15

* Wooden Frame: ~$20

* Monitor (32"): FREE (thanks Ryan!)

* Approximate Total: ~$96.56

Risks

* Misidentification of face (viewing angle of camera)

* Misidentification of gestures (not enough contrast)

* Raspberry Pi 3 burnout

* Damage to monitor

* Exceeding usage of computational power for the Pi 3

Addressing Risks

* Assign a fixed placement for the camera so training is consistent with capture

* Simplify gestures

* Turn off Raspberry Pi 3 when not in use

* Take care while handling mirror

* Optimize program’s usage of processing power
