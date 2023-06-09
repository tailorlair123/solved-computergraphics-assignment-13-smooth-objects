Download Link: https://assignmentchef.com/product/solved-computergraphics-assignment-13-smooth-objects
<br>
5/5 - (1 vote)

Smooth objects

The goal of the application contained in index.html, is to create 4 objects: a cube, a functional surface, a cylinder, and a sphere. As for assignment 10, the surface defined by equation y = sin(x) * cos(z) with -3 &lt;= x &lt;= 3 and -3 &lt;= z &lt;= 3. A fifth model, a pyramid, is already included in the application, just as an example to code the other primitives. Models are created in file models.js. In particular, the procedure addMesh()receives as parameters the vertex buffer (an array of six elements with the coordinates of the vertices and the direction of the associated normal vectors), the index buffer (an array of indices in the vertex buffer), and an RGB color (a three-elements array, with the value of the red, green and blue components of the color, each one in the 0-1 range). Primitives are encoded as indexed triangle lists.

All meshes, except the cube, should be generated by an algorithm (which requires at least two nested loops are required). Below you can see a picture of the expected result. The cube might instead be manually defined. Below you can see a picture of the 4 objects. For what concerns the surface, this tutorial:

https://www.khanacademy.org/math/multivariable-calculus/integrating-multivariable- functions/flux-in-3d-articles/a/unit-normal-vector-of-a-surface

might help in finding the correct normal vector direction.