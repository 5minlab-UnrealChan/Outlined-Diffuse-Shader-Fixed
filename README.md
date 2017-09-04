# Outlined Diffuse Shader Fixed for Unity 5.6
This is a fixed version of diffused outline shader from http://wiki.unity3d.com/index.php/Outlined_Diffuse_3
(If the link is still broken, try cache:http://wiki.unity3d.com/index.php/Outlined_Diffuse_3 )
It should is working fine in Unity 5.6.
There are two main versions of the shader, I use them for different objects, sometimes the custom one works best and sometimes the regular one. Just try out both of them :)


# Shaders:                         
**RegularOutline.shader** - Just an updated version of the shader from the wiki page, may still work in weird ways => if so, use custom one.
![Regular Outline](/images/standard.PNG?raw=true "Regular Outline")
**Usage**: Curved shapes/thin outlines.
**Problems**: Weird shapes on hard edges.

---

**CustomOutline.shader** - My personal take on the outline shader. It increases the scale of the vertices instead of working with normals. 

---

**CustomOutline-CameraIndependent.shader** - Same as custom one, but the outline is the same width despite the distance to the camera.      

---

**CustomOutline-ConstantWidth.shader** - Same as custom one, but the outline is constant width despite the camera zoom.

---


*UPDATE 03.09.2017 - Added camera independent version of custom shader.*
