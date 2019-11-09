# zoomToMouse
[Live Demo](http://seafirefly.com/zoomToMouse/zoomToMouse.html)

Prompt:
Construct a Three.js scene with a variety of geometric primitives of different sizes and colors. Use the OrbitControls class from Three.js [1] to provide navigation around the scene by orbiting, panning and zooming. Note that the zooming works independently of where the mouse pointer is positioned inside the browser window - OrbitControls always zooms in and out using a point in the center of the window. Modify the OrbitControls class so that it zooms in to where the mouse pointer is located on the screen (this is how zooming in works in Blender, for example [2]).

[1]: https://threejs.org/docs/#examples/en/controls/OrbitControls
[2]: https://www.youtube.com/watch?v=RNBYuYRFQe0

# parametric pasta
[Live Demo](http://seafirefly.com/zoomToMouse/farfalloni.html)

Prompt: 
You're going to add procedurally generated geometry to the scene you created. The geometry is going to be generated from a set of parametric equations (see attachment farfalloni.jpg). The sections in the attached document are as follows:

_ranges - a range is a series of numbers used in the equations. There are two ranges, arbitrarily named i and j.
_equations - Named after (pi, theta and kappa), three letters from the Greek alphabet, these three equations form the 'genetic code' of the shape you're going to generate. Because the shape is 3D, we need three equations to describe each of the 3 dimensions of the shape: width, length and depth. These equations feature mathematical functions that use the ranges described above to plot the form.

Below the equations is the 3D shape that you're going to recreate using Three.js. Each dot combines the solutions of all three equations for a given value of ranges i and j.

You can render this geometry using either a point cloud or a mesh with MeshPhongMaterial. You can place as many instances of this geometry in the scene as you wish, but more importantly it should be noticeably larger than the primitives you already have in the scene. For extra credit, you can make the shape rotate slowly around any of its 2 axes with the center of its mass as the centerpoint, or make any other additions/modifications that you think would make the scene more visually interesting.
