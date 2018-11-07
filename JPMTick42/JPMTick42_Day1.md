## UI Component Library 

### Purpose / Benifits 
* Need to define the purpose
  * UX Consistency 
  * Common patterns for build front-end applications like high-performance patterns and automatic testing 
  * Accellerate developers so that they can build apps quickly

### Goals
* Core Libraries 
* Standard Pattern Templetes
* Inventory Tracking
* Documentation
* Developer Support

### Anti-Goals
* Server-side solutions
* Generic solution to convert the styles of legacy apps

### Current Issues
* UX teams built protypes in Axure which looks very similar, but doesn't match the component library. This creates a lot of confusion with the develepers and users. Developers overides the standard components to match the high fidelity prototypes. Users start directing UX requirements. Ideally the prototype should not be high fidelity. Real HTML5 protypes should be created if high fidelity is required. UX requirements should be something that every user group directs. 

### Path to Converting Theme
* Happy Path:=> Use the UX Component Library. If you are already on this you just need to upgrade. You are not using the Component Library try to upgrade you UI to use the UX Libs
* Exception Process:=> Tatical force to restyle legency style sheets with technical debt. 

### Stategy
* Improve Compoments Libaries while using it real apps in parallel

### Packing the Component Library
* Will improve this with the new version

### GLUE TestFramework
* Windows API - use glue windows api to interact with windows
* Bionic - simulate keyboard & mouse interactions 
  * 	Currently only for windows mgmt
  * 	Needs capability For an e2e test need a way to interact with an app
     * 	Actions: There are multiple ways app level tests can be impleted (location, dom, glue methods)
* Soak - simulates continually usage
* Performance - records additional performance metrics
* Actions: Possiblities of running multiple modes in parallel 

### Dev Tools
* HTML5 Launcher
* Application Monitor 
  *  Performance Report
     *  Events
     *  Networks
     *  Console
     *  Issues
  *  Task Managers 
  *  Action: How do we detect memory issues in apps?
* Context Viewer
  * Can view and edit context
  * Action: New Feature - which app updated the context
  * 


