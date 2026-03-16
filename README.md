# SOUND-DRIVEN VISUAL DELAY

**Yutong Du**  
Workshops in Creative Coding  

---

## Project Overview

SOUND-DRIVEN VISUAL DELAY explores how sound can influence visual delay effects within an audiovisual system. Instead of using audio as a compositional layer, the project treats sound as a control signal that shapes the temporal behaviour of visuals. Audio data is generated and analysed in Max/MSP and transmitted to TouchDesigner through OSC. In TouchDesigner, these values are mapped to parameters related to delay and feedback, allowing sound intensity to influence how the visual response appears over time.

During the presentation, the visual output was transmitted through NDI from TouchDesigner and projected onto a large wall surface. This allowed the visual delay effects to be experienced at an architectural scale, turning the work into a spatial audiovisual environment rather than a small screen-based interface.

---

## Concept

This project explores the relationship between sound and visual delay. Audio signals are generated and analysed in Max/MSP, where key sound parameters are extracted and transmitted to TouchDesigner using OSC. These values are then mapped to visual delay parameters rather than traditional visual attributes such as colour or position.

By mapping sound intensity to visual latency, the system makes temporal relationships visible. Changes in sound affect how late the visual response appears, turning delay into a perceptible visual phenomenon. The system therefore focuses on translating audio behaviour into temporal visual dynamics.

---

## System Structure

The project consists of two main components.

**Max/MSP**

Max generates and analyses sound data. Audio signals are processed to extract key values that represent sound intensity and spectral behaviour. These values are sent to TouchDesigner through OSC communication.

**TouchDesigner**

TouchDesigner receives OSC data from Max and maps it to visual delay parameters. Instead of controlling colour or movement directly, the sound data controls delay and feedback effects within the visual system. This produces distorted and time-shifted images that reveal the temporal behaviour of the audio input.

The final visual output can also be transmitted through NDI and projected into a physical space, expanding the visual experience beyond the screen.

---

## Reflection

A key aspect of this experiment was the way the visual output was transmitted and displayed. During the class presentation, the visuals created in TouchDesigner were sent through NDI output and projected onto the studio walls. NDI allows video signals to be transmitted across devices and software environments in real time, making it possible to extend the visual system beyond a single screen.

Through projection, the delayed visual effects became more noticeable and spatially distributed across the surrounding architecture. The distortions and motion trails appeared as enlarged layers of temporal traces across the walls of the room, allowing the delay effects to be experienced at a larger scale.

Observing the work in this projected environment helped me understand how the final presentation of a digital system can significantly influence the audience’s experience. While the visuals can function on a monitor, projection transforms the work into a spatial media environment where viewers are surrounded by the moving images. In future development, the project could further explore how sound input, visual delay and spatial projection interact to create a more immersive audiovisual installation.


---

## Tools

- Max/MSP  
- TouchDesigner  
- OSC communication  
- NDI output  

---

## Reference

TouchDesigner NDI documentation  
https://docs.derivative.ca

---

## Video

Project demonstration video:

https://youtu.be/POxPrq3jfEA  
https://youtu.be/aHNlSsM8YsI?si=Jbz3OicQPx3W0Z
