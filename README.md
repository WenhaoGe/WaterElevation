# VR_Project3
### Proposal Phase
## Descriptive Title:
  - Improved Water Elevation
## General Discription: 
  - We will autogenerate the terrain or add more cities. We will add the yearly saturated thickness data. We will add more prefabs to decorate the terrain. In addition, we will create new buttons to teleport to different wells. We will also add more facts about each city. In addition, we will also add music that people can hear while they are playing because that is an important aspect. The reason why VR is beneficial is that VR allows the user to get a firsthand perspective of the landscape of the city they choose, which fosters an immersive experience. In addition, users can feel a more real experience than looking at a 2D representation by using VR.
## Hardware platform we will use:
  - PC, Oculus rift, Google Cardboard
## Software we will use:
  - Unity
## Teammates:
  - Wenhao Ge, Lino, Kevon
  
### Work Distribution
   - Wenhao's role: He will use prefabs to decorate the terrain and add some animations to GameObjects. 
   - Kevon’s role: He will create several buttons to teleport to different wells and do other things.
   - Lino's role: He will do the terrain autogeneration
## Links to any datasets or libraries:
- Texas Water Development Board (https://www.twdb.texas.gov/groundwater/data/gwdbrpt.asp)
- iDataVisualizationLab at Texas Tech University (https://github.com/iDataVisualizationLab/SaturatedThickness)
- Terrain.party (www.terrain.party)
- Unity Asset Store
  
  
  
# CS 5331-002 - Virtual Reality Project 3
# Topic: Water Elevation


## Video Demonstration
   - On our current repository: https://youtu.be/hPab9evVa0s

## Screenshots
   - On our current repository: https://github.com/lvrg12/WaterElevation
   
## Project Report

### Project Description
- We autogenerated the terrain and added more cities. We added the yearly saturated thickness data. We added more prefabs to decorate the terrain. In addition, we created new buttons to teleport to different wells. We also added more facts about each city. In addition, we also added the background music that people can hear while they are playing because that is an important aspect. 


### Auto-Generation
As soon as the system starts, it starts reading, computing, and delivering data. Most of the objects in our scene are auto-generated by a couple of c-sharp scripts. These scripts gather data from various csv files. The c-sharp scripts generate the wells, their depth, their saturated thickness in different years, aerial markers, and a water layer that spans the whole terrain. These scripts use multiple math operations to math the real life measurements to the unity measurements. In this manner, we were able to accurately place the wells where they are in real life and replicate the measurements of the underground water layer. In addition, we also accurately placed the water fountain inside each of the well.


### Main Menu
This is the initial scene, a drop-down menu and three other buttons are in the main menu. The drop-down menu is called 'selection'. When people click it, there will be five options. After clicking the city people want to go, then click 'generate' button to go to the terrain.

### First Person Control
With a first person controller the user is able to navigate through the map; adding a realistic field experience. If the user aims the cursor to the auto-generated wells information is displayed. The user is also able to click on the provided bottons which are described in the next section.

### Functionality

### We learned...
- How to write Python code
- How to read CSV files
- How to calculate Water Elevation
- How Water Elevation, Saturated Thickness, and LSD relate to one another
- How to write script to make the panels appear and disappear according to some specific conditions
- How to write script to make slider call different functions
- How to make a drop-down menu
- How to add the background music
- How to write script to read the data from .csv files and display the information in the panels
- How to write script to show different years when people drag the slider


### Biggest Issues
- Autogeneration
- Script writing
- Csv files data generation
- Measurement type
- Measurement congruency
- Merging all the stuff in Github

## Contributors
- Lino Virgen, Wenhao Ge, Kevon Manahan

## Dynamic features/interactables
There's a main menu when you begin the game that allows the player to select which city will be used. Whenever you hover the mouse over the well from within the game, it will display the information about each well. Also there is a User Interface which allows the player to cycle between cameras(Main, Elevation, Aerial, Slider, ToggleTerrain, TEST RAIN, TEST DROUGHT) by clicking each button respectively.

### Work Distribution
- Wenhao Ge's part:
   - Wrote the phase proposal
   - Created a sider and wrote script to show different years when the slider is being slided
   - Wrote script to make slider control many functions. When people drag the slider, many functions will be called according to the value of the slider
   - Made a drop-down menu and created five choices in the drop-down menu
   - Wrote script to let two panels appear when the user hovers the mouse over the wells and let two panels disappear when the mouse leave the wells
   - Made two panels 
   - Wrote script to read the data from .csv files and display all these data in two panels 
   - Added the background music
   - Modified the terrain coordinates when they are generated
   
- Kevon's part:
    - Relearned Python
    - Wrote script to find Water Elevation for each year in each each city
    - Wrote script to find Saturated Thickness for each year in each city
    - Added lighting to all cities
    - Edited the Main Menu
- Lino's part:

### References
- Texas Water Development Board (https://www.twdb.texas.gov/groundwater/data/gwdbrpt.asp)
- iDataVisualizationLab at Texas Tech University (https://github.com/iDataVisualizationLab/SaturatedThickness)
- Terrain.party (www.terrain.party)
- Unity Asset Store
