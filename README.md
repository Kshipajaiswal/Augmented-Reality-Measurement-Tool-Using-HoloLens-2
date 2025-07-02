# Augmented-Reality-Measurement-Tool-Using-HoloLens-2
An augmented reality tool for measurement in machine doors, combining 3D-printed hardware with HoloLens 2 and Unity to visualize and interact with CAD models in real-time.

## Table of Contents

1. [Introduction](#introduction)  
2. [Objectives](#objectives)  
3. [Tools & Technologies](#tools--technologies)  
4. [Key Features](#key-features)
5. [Use Case](#use-case)
6. [How to Run (HoloLens)](#how-to-run-hololens)   
7. [Future Scope](#future-scope)  
8. [Author](#Author)

## Introduction
This project explores the integration of physical prototyping and augmented reality to enhance machine maintenance and inspection tasks. A custom-designed **3D-printed chisel tool** was developed to measure gaps in machine doors more accurately and safely. To complement this, a **HoloLens 2 application** was built using **Unity Hub**, enabling real-time visualization of CAD models in augmented reality (AR).

By combining physical tools with digital overlays, the system allows users such as maintenance engineers and technicians to:
- Inspect 3D machine parts in the real environment,
- Rotate, zoom, and interact with CAD models,
- Reduce measurement errors,
- And improve understanding of mechanical assembly tolerances.

This innovative approach supports smarter maintenance workflows and offers a glimpse into the future of **Industry 4.0** and **spatial computing** in manufacturing environments.

## Objectives

- Design and 3D print a chisel tool to assist in precise gap measurement for machine doors.
- Enhance visibility and understanding of mechanical assemblies using 3D CAD model visualization.
- Integrate the physical chisel tool with digital AR overlays for better alignment and inspection.
- Develop a HoloLens 2 application using Unity Hub to interact with 3D models in real-world environments.
- Enable real-time interaction with models (zoom, rotate, inspect) for more intuitive technical assessments.
  
## Tools & Technologies

- **Fusion 360** – For 3D modeling of the chisel tool.
- **3D Printing** – Physical fabrication of the tool prototype.
- **Unity Hub + Unity 3D** – To build AR experiences and import CAD models.
- **Microsoft HoloLens 2** – For real-time visualization and interaction.
- **Mixed Reality Toolkit (MRTK)** – To handle interactions (zoom, rotate, drag) on HoloLens.

## Key Features

- Designed and 3D-printed a custom chisel for gap testing in machine assemblies.
- Projected 3D CAD models onto physical space using HoloLens 2.
- Allowed users to interact with models—zoom, rotate, and inspect components with gestures.
- Enhanced precision and usability in mechanical validation workflows.

## Use Case

This tool helps engineers during the design review phase by letting them visualize and validate spatial tolerances and part fits using an AR overlay. It eliminates the need for screen-based CAD checks and enables immersive inspections on the factory floor.

## How to Run (HoloLens)

1. Open the Unity project using Unity Hub (ensure MRTK is installed).
2. Connect and configure HoloLens 2 in Developer Mode.
3. Build the Unity scene to UWP platform.
4. Deploy the solution using Visual Studio.
5. Launch the app on HoloLens to interact with the imported CAD models.

## Future Scope

- Integrate real-time gap measurement data using IoT sensors.
- Add voice control and gesture tutorials for smoother interaction.
- Enable live collaboration between multiple HoloLens users.
- Explore AI-assisted part recognition for inspection.

## Author

**Kshipa Jaiswal**  
- [kshipajaiswal@gmail.com](mailto:kshipajaiswal@gmail.com)  
- [LinkedIn](www.linkedin.com/in/kshipa-jaiswal-ab7055220)  
- [GitHub](https://github.com/Kshipajaiswal)
