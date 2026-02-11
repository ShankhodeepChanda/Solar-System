# Solar System Simulation


**A fully animated Solar System built using pure HTML, CSS and Javascript**

This project demonstrates advanced CSS techniques such as:

* Absolute positioning
* Transform centering
* CSS animations and use of keyframes 
* Pseudo-elements
* Scalable layout using em units
* Orbit simulation using rotation
* Use of Javascript to make the starry background

# Live Demo

[⬤ View Demo](https://ogsolarsystem.netlify.app)

<img width="1920" height="1080" alt="Screenshot 2026-02-11 232605" src="https://github.com/user-attachments/assets/cdc024e0-9364-4d1e-95e3-9876bfff7a96" />


# The entire solar system uses:

.container {
    font-size: 8px;
    width: 40em;
    height: 40em;
}

**Why em?**

**1em = font-size of container**

**Changing one value (font-size) scales the entire universe**

This creates a clean, scalable coordinate system.

# Orbit Creation Trick

Orbits are not drawn using circles directly.
They are created using:

border-style: solid;
border-color: white transparent transparent transparent;
border-width: 0.1em 0.1em 0 0;
border-radius: 50%;

**How this works:**

* Create a square (width + height)

* Turn it into a circle (border-radius: 50%)

* Make only the top border visible

* Rotate the element

This creates the illusion of a rotating orbit path.


