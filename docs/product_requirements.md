# Problem Description
There are not many driving simulators/games that utilize ADAS features. We want students to build one so that it can teach people about these features, while providing an opportunity to develop a real game that people can play.

## Scope
Our scope will be limited to a single-driver vehicle with simulated AI traffic, and a number of Advanced Driver Assistance Systems features. These will include (but are not limited to):
- Automatic braking
- Lane departure warning
- Blind spot detection
- Collision detection
- Rear-view camera
- Wrong-way warning
The user will be able to drive around a map and complete objectives. The setting for the game will be a downtown city with other cars powered by AI. ADAS features will be implemented to prevent the user from crashing or colliding with other cars.

## Use Cases
A use case for navigating this simulated environment would be for someone to get a general sense of what it would be like to have these ADAS features activated as someone who has never had them in their car before.
A more general use case could be for users that are either new to driving altogether or are not used to what it’s like driving in America. This program can somewhat familiarize these users with typical traffic conditions.
The user will be able to control the vehicle around a 3D map.

The user will be able to collide with other, AI-driven vehicles.

The user will watch as traffic responds to the user’s vehicle driving on the map.

The user will be able to complete objectives by driving around the map.

# Purpose and Vision (Background)
Our purpose is to develop a realistic driving game that uses ADAS features to teach people more about driving systems, while providing an enjoyable gaming experience and teaching college students about game development. We want to be able to show this project off at the engineering expo for people to try and learn about ADAS features in a realistically simulated driving environment.

## Stakeholders
- Users
- Interested people at the expo
- People who like games
- People interested in ADAS
- Game developers
- Game engine developers
- College professors

# Preliminary Context
## Assumptions
We are assuming that the users would be able to run the product on a sufficiently powerful PC.
We are assuming that there are free-to-use models/textures that we can use for 3D assets in the environment, so I don’t have to model too many of my own.
We are assuming that there will be assistance, in person or online, in the use of the platform that we will be developing on.

## Constraints
We are a small team of inexperienced game developers, and only have a limited number of months to complete the game.

We have no budget to work with, so we must utilize free software/information whenever possible.

## Dependencies
We need physics algorithms and calculations with regard to driving before we can complete the driving simulation.
We need 3D models and a working game environment before we can begin work on realistic textures/graphics.

# Requirements
## User Stories and Features (Functional Requirements)
As a user, I want to be able to turn the car so that I can complete objectives or otherwise maneuver around the world as one would with a real car

As a visitor at the expo, I want smaller objectives so that I have time to fully complete an objective during the short amount of time I have to demo the game.

As a new driver, I want to be aware when my vehicle collides with another object so I can be better aware of my performance and the safety of my driving.

As a driving student, I want a car that brakes realistically so that I can practice driving and braking from my room.

As a new driver, I want the game to emulate weather events such as rain and snow complete with new obstacles, so that I know what I might run into in these unpredictable conditions.

## Non-Functional Requirements
The product should not require an internet connection.
The product should be able to run smoothly at 60FPS without the need of a high end machine.
Code should have well-kept version control to track issues and keep track of progress.
There should be negligible input delay between the controller and the game response.

## User Interaction and Design
The user will start on a title screen with a button to Start and a button to Quit. The Start button leads to a screen with a Day button and a Night button, as well as a Back button. Selecting either Day or Night will lead to another screen with Map Selection, which will be 3 buttons with previews of the associated map. Pressing on any map will load in the game.

Wireframe for main menu:
https://www.figma.com/proto/YD9642CJRpLyHGVTNYEd6a/Capstone-Main-Menu-Prototype?type=design&node-id=1-2&t=8HrKPyfMKqh7UVIf-1&scaling=contain&page-id=0%3A1&mode=design

# Milestones and Timeline
- Establishing the 3D environment - constructing the town, obstacles, and the roads in it. This should also help us get familiar with the development space.
- Simulating car movement - this might start with just moving the camera, but input should have the weightiness and “feel” of a car as it accelerates, brakes, and turns.
- Simulating car presence - This includes physics and collision checks. This might also be the place where we can integrate the ADAS features.
- Simulating traffic - This is where other cars come in and act as moving obstacles of their own, with behavior emulating a real car. Collectively, these cars will “behave” like real traffic that one would expect in certain settings.

A timeline will be created once development officially begins.

# Goals and Success Metrics
- Have users engaged in product.

- Create a realistic driving experience.

# Open Questions
Are we allowed to use premade assets? If so, how much of the game can be made of premade assets?
# Out of Scope
We will not be making a settings menu. We will not have multiple drivable vehicles.
