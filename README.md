# Basic Ray Tracer Implementation in Unity

This project involves creating a basic ray tracer in Unity that renders a 3D scene with accurate lighting, shadows, reflections, and refractions. The ray tracer utilizes Unity's graphics capabilities to simulate realistic visuals, providing an immersive experience. 

---

## Table of Contents

- [Project Description](#project-description)
- [Features and Requirements](#features-and-requirements)
- [Implementation Strategy](#implementation-strategy)
- [Scene Setup](#scene-setup)
- [Tasks](#tasks)
- [Bonus Challenge](#bonus-challenge)
- [Screenshots](#screenshots)
- [Installation and Usage](#installation-and-usage)
- [Contact](#contact)

---

## Project Description

In this project, we created a ray tracer in Unity that renders a 3D scene with realistic lighting effects, including shadows, reflections, and refractions. This ray tracer was built using Unity's 3D development engine, with features like diffuse and specular reflection, ambient lighting, and shadow casting to enhance the scene's realism.

---

## Features and Requirements

The scene includes:
- A virtual camera positioned strategically to capture the 3D environment.
- Multiple 3D objects (spheres, cubes, capsules, and planes) with different positions, orientations, and material properties (color, reflectivity, transparency).
- Point or directional light sources to illuminate the scene with customizable intensities and colors.

---

## Implementation Strategy

The project was built in Unity, following a structured approach to create a 3D environment with ray tracing capabilities. The steps include:

1. **Camera Setup**: Positioning the camera to view the entire scene.
2. **Scene Layout**: Adding a plane for the ground and setting up walls and a roof to enclose the scene, resembling a room.
3. **Lighting Setup**: Adding light sources to illuminate the room and cast shadows.
4. **Object Placement**: Adding objects like a yellow sphere, blue capsule, red sphere, and green cube, with reflection probes for each.
5. **Reflection and Shadows**: Implementing ray tracing to simulate realistic lighting and reflections, visible especially when the light source is toggled on/off.

---

## Scene Setup

1. **Camera Positioning**: The camera is strategically positioned to capture the full scene.
2. **Room Setup**: A plane is set up as the floor, with walls and a roof added to complete the room's architecture. Each wall is customized with material properties for a realistic appearance.
3. **Lighting**: A primary light source is added to the room to illuminate objects and cast shadows.
4. **Object Addition**: 
   - A yellow sphere is placed and a reflection probe is set up for it.
   - Additional objects (blue capsule, red sphere, green cube) are added with reflection probes to simulate realistic reflections.
5. **Ray Tracing in Action**: When the light is toggled on/off, reflections and shadows are dynamically updated, demonstrating the ray tracing effect.

---

## Tasks

The key tasks for implementing the ray tracing project were:

1. **Set Up the Unity Project**: Create a new Unity project and set up a 3D scene.
2. **Ray Casting**: Implement a ray casting algorithm to trace rays from the camera through each screen pixel.
3. **Intersection Testing**: Check intersections between rays and scene objects to identify visible objects from the camera's viewpoint.
4. **Shading Calculations**: Determine shading for each object using its material properties (diffuse, specular, ambient reflection) and lighting conditions.
5. **Shadow Calculation**: Implement shadow rays to detect if objects are in shadow based on visibility to light sources.
6. **Reflections**: Support reflections by tracing reflected rays from reflective surfaces, combining the reflection with the surface color.
7. **Rendering**: Render the final image by combining the colors calculated for each pixel.

---

## Bonus Challenge

To further enhance realism, transparent materials and refraction effects can be implemented using Unity’s shader capabilities. This adds complexity to the ray tracing algorithm, requiring additional calculations for light refraction through transparent surfaces.

---

## Screenshots

> **Note**: Screenshots of the scene setup and final rendering results should be included here to illustrate the development process.

---

## Installation and Usage

1. **Clone the Repository**: Clone this project repository to your local machine.
2. **Open in Unity**: Open the project in Unity.
3. **Run the Scene**: Open the main scene and press the play button to see the ray tracing in action.
4. **Toggle Lighting**: Experiment with the lighting to observe real-time changes in shadows and reflections.

---

## Contact

For any inquiries, feel free to reach out:

**Usman Malik**  
- Email: [usman.malik051301@gmail.com](mailto:usman.malik051301@gmail.com)
- GitHub: [UsmanMalik13](https://github.com/UsmanMalik13)

---

This `README.md` provides a comprehensive guide for setting up and understanding the Unity ray tracing project. It covers all the tasks and challenges involved in creating a realistic 3D scene. Let me know if there’s anything you’d like to adjust!
