UV coordinates (also known as texture coordinates) are two-dimensional coordinates used to map a 2D texture onto a 3D object in computer graphics. The "UV" nomenclature comes from the axes names: U represents the horizontal axis, and V represents the vertical axis.

Every point on the surface of a 3D object has its corresponding UV coordinates, and these coordinates define which part of the 2D texture image will be applied to that point during rendering. The UV coordinates define how the texture wraps around the 3D geometry, determining which parts of the texture image are visible on different parts of the object.

In the UV coordinate system, the bottom-left corner of the texture is typically assigned the coordinate (0, 0), and the top-right corner is assigned (1, 1). So, UV coordinates usually range from 0 to 1 in both dimensions.

Here's a simple explanation of how UV coordinates work:

1. A 2D texture image is created, typically stored as a bitmap or an image file (e.g., PNG, JPEG).

2. When applying the texture to a 3D object, each vertex of the object is assigned a UV coordinate. These UV coordinates are interpolated across the surface of the object to determine the texture coordinates for each point on the surface.

3. For each point on the surface of the 3D object, the renderer looks up the corresponding UV coordinate in the texture. The renderer then samples the color of the texture at that UV coordinate and applies it to the corresponding point on the object's surface.

4. By mapping the texture's colors to the object's surface based on UV coordinates, the 3D object appears to be covered with the texture image, providing visual details and realism to the rendered scene.

UV coordinates play a crucial role in texturing 3D models, as they allow artists and developers to control how textures wrap around and align with the geometry, giving the illusion of intricate details and materials on the surface of 3D objects.