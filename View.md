
# Views

## Navigation Shortcuts 

- Middle Mouse for rotation
- Shift + Middle Mouse for strafing
- Mouse Wheel or Ctrl Middle for Zooming
- N -> View can be used to lock camera to viewport
- Ctrl Alt 0 can also be used to bring Camera to viewport

## Viewport Details
- Numpad 1 for Front View / Ctrl Numpad 1 for Back View
- Numpad 3 for Right View / Ctrl Numpad 2 for Left View
- Numpad 7 for Top View / Ctrl Numpad 7 for Bottom View
- Numpad 9 for Opposite View 
- Bigger Squares represent 1 meter and smaller squares represent 10 cm
- Numpad 5 is used for Orthographic view and Perspective view switching
-  Orthographic View keeps the sizes relatively same while Perspective makes the sizes relative to distance
- Numpad 0 is used for Camera View
- Wireframe can be used to see the edges of the objects and X-Ray can be used to select objects behind
- Solid view shadows aren't affected from light objects
- Material View lighting is affected from and HDRI which can be viewed in shading window
- Render View uses realtime lighting
- F12 can be used to render image from camera view
- ViewPort Overlays (next to X-Ray) we can enable statistics to see the count of vertices,edges and faces

## Rendering & Lighting
- Render Properties can be used to select between Eevee (Simple) and Cycles (RayTracing) for lighting
- In the Render Properties The Ambient Occulusion setting can be used to increase shadow details on the crevices
- Ambient Occulusion happens when the rays of the the light can't reach small sections of the objects
- Surface reflections can also be enabled in the Render Properties to create reflections
- In the shader editor we can change the material of the world and add Environment Texture under Texture as an HDRI
- When Focusing on a light object in the Light Properties we can change the light color,power and style from Point, Sun, Spot, Area