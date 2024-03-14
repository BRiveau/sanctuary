# Design Document

## I. Goals and Vision

* Should include items such as, who the intended audience is, and what the overall goal of the project will be.

### Business Goals

1. What is the long term vision of your business?

The long term vision for this application is to provide users with an open source alternative to popular game engines like Unreal Engine and Unity. This will allow developers to create games without the need to pay for expensive licenses, while also lowering the skill requirements for new video game developers by providing them the opportunity to develop games in a way that best suits their needs.  

2. Why are you building this? What problem are you solving?

I am building this application to solve the problem of memory unsafe languages being used in game development. This is a problem as memory unsafe languages cause a lot of bugs and security vulnerabilities in games. By using a memory safe language like Rust, we can avoid these issues and provide a more secure and stable game development environment.

### Business Needs

1. Who are the user personas? (make sure to include motivations, pain points, etc.)
2. How will you define success for this project? (include all metrics you will be using to define success)

## II. Requirements / System Overview

* The main purpose of the application is to provide video game developers with all of the tools that they need for game development in a single package, while also ensuring memory safety and security.
* Some possible failure scenarios include:
  * The application crashing
  * The application failing to compile
  * The application failing to run
  * The application failing to save
  * The application failing to load
* At first execution, the application will ask the user to select a directory to save their projects in, as well as ask the user which tools they would like to install.
* The user will be able to create as many projects as they can fit on their storage device, but the given instance of the application will only allow for a single project to be open at a time.

### User Requirements

* Write user stories in the following format:
  * As a `<user type>`, I want to `<some goal>` so that I can `<some reason>`.

### Functional Requirements

* List all of the behaviors that the application should provide or support
  * Include integrations with other application/products, online/offline modes, dependencies, etc.

## III. User Interface

* Include wireframe for each page
  * Should include descriptions of the following:
    * Each control, including states (enabled/disabled/highlighted) and operations.
    * Supported orientations and transitions among them.
    * Functionality that’s being represented.
    * Error handling.
    * Dimensions and constraints.

## IV. Milestones and Prioritization

### Milestones

* Should include deadlines for completion and expected deliverables

### Prioritization

* Prioritize features into the following categories:
  * Include in MVP (High impact, high urgency)
  * Revisit (Low impact, high urgency)
  * Don’t Include in MVP (Low impact, low urgency)
  * Debate (High impact, low urgency)
