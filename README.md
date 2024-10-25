# DJ System using OSC Controller and PureData

## Team Members
- Emmanuel Collazos
- Isaac Escobar

## Project Description
This project uses the **OSC Controller app** (Open Sound Control) and **PureData (PD)** to create a DJ system. The system allows for the creation of electronic music by mapping various user interactions in the OSC app (such as sliders and buttons) to different audio responses in PureData. Each widget interaction from the OSC app generates a corresponding sound effect in PD, enabling live electronic music performances.

## Features
- **OSC and PureData integration**: The project leverages OSC communication to control sound in real-time through PureData patches.
- **Widget interaction**: All widgets from the OSC layout (sliders and buttons) are used, each controlling specific parameters in the sound synthesis or effects in PureData.
- **Electronic music creation**: The system allows users to generate and manipulate sounds as a DJ would, using various controls to adjust the mix and effects.
- **Demo video**: A demonstration video has been uploaded to YouTube, showcasing the system in action with a 5-minute electronic music piece.

## How it works
- **Sliders**: These are used to control different aspects of the sound, such as volume, pitch, or filter frequencies.
- **Buttons**: Each button triggers different sound effects or switches between audio tracks in PureData.
- **PureData patches**: Custom PD patches were created to receive OSC messages and process them to create sound manipulations in real-time.

## Justification
We chose to implement this system using **OSC Controller and PureData** due to their flexibility in live audio manipulation and real-time control. OSC is ideal for transmitting control data over networks, while PureData allows for powerful audio synthesis and effects processing. This combination provides the creative freedom required for live DJ performances and interactive music creation.

## Demo
Watch our demo video on YouTube [here](your-video-link).

## Code and Repository
The full source code for this project can be found in this repository. The code follows clean coding principles, making it easy to read and understand. 
