# CS330
cs330 snhu

# Final Reflection Journal – CS-330 

## How do I approach designing software?

I approach software design by breaking the system into reusable components and thinking in terms of responsibilities rather than single functions. In this project, I designed the scene around clear systems: texture management, material definitions, lighting setup, and object rendering.

Instead of building objects individually in isolation, I structured everything through a centralized `SceneManager`, which controls transformations, shader communication, and rendering flow. This helped me design the program as a coordinated pipeline where each part contributes to the final visual output.

---

## What new design skills has your work on the project helped you to craft?

This project strengthened my ability to design **modular graphics systems**. I learned how to separate concerns between:

* geometry (ShapeMeshes)
* rendering logic (SceneManager)
* shading (ShaderManager)
* visual appearance (materials + textures)

I also developed stronger skills in **scene composition**, especially how object placement, scale, and lighting interact to create realism. Working with Phong lighting and multiple light sources improved my understanding of how design decisions affect visual output.

---

## What design process did you follow for your project work?

My design process followed an iterative 3D pipeline:

1. Load basic meshes (plane, box, sphere, etc.)
2. Set up textures and bind them to tags
3. Define materials for realism (wood, metal, ceramic, etc.)
4. Configure lighting (directional + point lights)
5. Build scene objects one by one
6. Adjust transformations for proper placement
7. Refine lighting and scale for realism

This step-by-step process ensured that each layer (geometry → material → lighting → composition) was validated before moving forward.

---

## How could tactics from your design approach be applied in future work?

The same design strategy can be applied to game development, simulation systems, and UI/graphics applications. The key idea is **separation of systems and incremental construction**.

For example:

* SceneManager pattern → game engine architecture
* Material system → reusable asset pipelines
* Light configuration → real-time rendering engines
* Transform pipeline → physics and animation systems

This structured approach makes complex systems easier to debug, extend, and scale.

---

## How do I approach developing programs?

I approach programming by first building a minimal working version and then expanding functionality. In this project, I started by ensuring basic meshes rendered correctly, then added transformations, followed by textures, materials, and finally lighting.

I rely heavily on visual debugging—meaning I adjust values like scale, position, and light intensity based on what I see rather than only relying on logs.

---

## What new development strategies did you use while working on your 3D scene?

Several new strategies emerged during this project:

* Centralized transformation handling using `SetTransformations()`
* Tag-based texture and material lookup system
* Incremental object rendering (adding one scene object at a time)
* Shader-driven debugging for lighting issues
* Reusable material definitions instead of hardcoding colors repeatedly
* Layered rendering (base plane → table → objects → detail items)

These strategies improved both efficiency and scene consistency.

---

## How did iteration factor into your development?

Iteration was essential to the success of the project. Almost every object required multiple adjustments in:

* position (especially 3D placement on the desk)
* scale (to maintain realism between objects)
* lighting balance (to avoid overexposure or flat shading)
* texture repetition (UV scaling like wood tiling)

For example, objects like the monitor, mug, and keyboard required repeated repositioning until they visually aligned with the desk surface. Each iteration improved realism and spatial accuracy.

---

## How has your approach to developing code evolved throughout the milestones, which led to the project’s completion?

At the beginning, I focused mainly on getting objects to render correctly. As the project progressed, I shifted toward structure and organization.

Early milestones were about functionality (drawing shapes), while later milestones emphasized:

* clean transformation logic
* reusable materials
* proper lighting setup
* scene realism and composition

By the final stage, my focus moved from “making it work” to “making it look correct and realistic,” especially through lighting and material tuning.

---

## How can computer science help me in reaching my goals?

Computer science helps me develop structured problem-solving skills that apply to many fields beyond programming. It teaches me how to break complex systems into manageable components and implement solutions systematically.

In this project, I applied mathematical concepts (vectors, matrices, transformations) directly into visual output, which strengthened both my analytical thinking and technical creativity.

---

## How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?

Computational graphics improved my understanding of linear algebra and spatial reasoning by applying them in a visual environment. Concepts like transformation matrices, scaling, and lighting models became more intuitive when seen in real time.

This experience prepares me for more advanced topics such as:

* simulation systems
* game engines
* physics-based modeling
* scientific visualization

It also strengthens my foundation for future courses involving math-heavy computing.

---

## How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?

Professionally, this project builds skills relevant to:

* game development (Unity/Unreal-style architecture thinking)
* simulation software
* AR/VR environments
* real-time rendering systems

I gained experience working with shader pipelines, lighting models, and structured scene management. These are directly transferable to industries involving interactive graphics, visualization tools, and immersive environments.


