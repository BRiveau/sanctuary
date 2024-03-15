# Source Code

## Pre-Development Features

* Wireframing / Prototyping
  * Should allow for the creation of wireframes and prototypes
  * Should allow for the creation of 2D and 3D wireframes and prototypes
  * Should allow for the creation of wireframes and prototypes for all other features
* Project Management
  * Will have an integration with `git` for version control

## Development Features

### Objects

* Static Mesh Creation / Editing
  * Work with vertexes, edges, and faces
  * UV/Texture Mapping
  * Create LODs
* Texture Creation / Editing
  * Allows for creation of normal maps, height maps, etc.
  * Dynamically create textures using various algorithms
  * Closely integrated with Material Creation / Editing
  * Should take advantage of the static mesh UV/Texture Mapping
* Material Creation / Editing
  * Allow for the creation of PBR materials
  * Should take advantage of the static mesh UV/Texture Mapping
  * Should allow for usage of dynamically generated materials
  * Can be created using pre-created textures
  * Will be created using a node-based system
  * Changes can be viewed in real-time
  * Meshes can be imported to see how the material will look on the mesh

### Characters

* Animation Creation / Editing
* AI Behavior Creation / Editing

### World

* Level Creation / Editing
  * Should support both 2D and 3D levels
  * Should allow for basic dynamic level generation
  * Should be able to create and edit terrain
  * Allow for the creation of water, sky, and other environmental effects
* Lighting Creation / Editing
  * Should support both 2D and 3D lighting
  * Should allow for ray-traced, dynamic, static, and stationary lighting
* Physics Creation / Editing
  * Should support both 2D and 3D physics
  * Should allow for the creation of rigid bodies, soft bodies, and other physics objects
  * Should allow for real-world physics simulations
* Particle Effect Creation / Editing

### Systems

* Sprite Creation / Editing
* Sound Creation / Editing
* UI Creation / Editing
* Sequence Creation / Editing
* Logic Creation / Editing
  * Default language will be custom block-based language built using Rust
    * Will also support programming in Rust, C, and C++
* Adding support for proprietary features
  * Will allow for easy integration of NVIDIA, AMD, and Intel features
  * Will allow for easy integration of console-specific features
* Performance Profiling
  * Should allow for the collection of data from the game
  * Should allow for the analysis of the collected data
* Performance Optimization Recommendations
  * Should generate recommendations for performance optimization based on the collected data in performance profiling

## Post-Development Features

* Analytics
  * Should allow for the collection of data from the game
  * Should allow for the analysis of the collected data
* Monetization
  * Should allow for the integration of in-app purchases
