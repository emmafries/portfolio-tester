---
layout: post
title: Heart Valve Visual Inspection System
# description: Developed a proof-of-concept **prototype** to demonstrate the utility and feasibility of an automated inspection process

skills: 
- SolidWorks
- 3D Printing (FDM)
- Prototyping
- Manual Machining (Mill)
main-image: /Sapien 3.jpeg
---

---
<div style="display: block; clear: both;">
  {% include image-gallery.html images="Sapien 3.png" height="250" align="left" %}
  <p>
    This is your paragraph text that will now wrap next to your left-aligned image. By containing both the Jekyll include tag and the paragraph element inside this custom layout div block, we break the theme's vertical flex column limits and allow the text to flow smoothly into the empty space right next to the picture.
  </p>
</div>

<div style="clear: both;"></div>

<style>
  /* Forces the template to allow side-by-side elements */
  .image-gallery-container {
    display: inline-block !important;
    width: auto !important;
  }
</style>
{% include image-gallery.html images="Sapien 3.png" height="300" align="right" %}
## Goals: 
Improve "subjective and tedious" inspection while maintaining accuracy and repeatability
- 100% inspection of metal frame
- "Lights Out" inspection
- Minimize inspection time
<div style="clear: both;"></div>
<span style="font-size: 15px">Edwards SAPIEN 3 Ultra transcatheter heart valve</span>
<span style="font-size: 12px">Design proprietary under NDA - generic substitute image from https://www.edwards.com/healthcare-professionals/products-services/transcatheter-heart/transcatheter-sapien-3-ultra</span>




## How?
- Designed pneumatic fixtures, motion control for a Meca500 robot arm, and camera assembly for inspection cycle

- Utilized **SolidWorks** to model assembly and create custom components with technical drawings with **GD&T**

- Manufactured components using **3D printing** and manual mill

{% include image-gallery.html images="SrProjectImage2.jpeg" height="500" %} 
<span style="font-size: 12px">Meca 500 Robot from https://iptech1.com/product/meca500-robot/</span>




## Results
Implemented robot motion and pneumatic control using RoboDK and Mecademic software and configured Basler Pylon image acquisition system to generate inspection images{% include image-gallery.html images="SrProjectImage3.jpg" height="400" %}
<span style="font-size: 12px">Design proprietary under NDA - generic substitute image from https://www.sciencedirect.com/science/article/pii/S0014305723009096</span>

Produced detailed and precise images using the automated process in testing and created a detailed framework of how to produce inspection images for whole frame in manufacturing

Design Strengths: 
- Single camera
- Successful move to capture full outer frame


## The Team
{% include image-gallery.html images="team.jpeg" height="500" align="right" %} 
<span style="font-size: 15px">Timothy, Jack, Elliot and me.</span>