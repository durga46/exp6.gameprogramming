# Ex No :06

# <p align="center">  Implement the AI random movement </p>

## Aim:
To create a Unreal project That have AI character To Chase the Player

## Procedure:
1.Open Unreal Engine and create a new Blueprint project.

2.Create a Blueprint class for your character: • Right-click in the Content Browser and select "Blueprint Class." • Choose "Character" as the parent class. • Name the Blueprint as desired.

3.Create a Blueprint class for the AI controller: • Right-click in the Content Browser and select "Blueprint Class." • Choose "AI Controller" as the parent class. • Name the Blueprint as desired.

4.Open the AI controller Blueprint: • In the Event Graph, right-click and search for "Blackboard." • Add a "Blackboard" node to the graph and name it "MyBoard."
Open the Blackboard: • Create a new Key named "TargetLoc" with the Vector data type.

5.Create a Behavior Tree (BT) Blueprint: • Right-click in the Content Browser and select "Blueprint Class." • Choose "Behavior Tree" as the parent class. • Name the Blueprint as desired.

6.Open the Behavior Tree Blueprint: • Create a sequence node by dragging and dropping it from the palette onto the graph. • Connect the sequence node to the root node.

7.Add a "Move To" task to the sequence: • Drag and drop the "Move To" task from the palette onto the graph. • Connect the output of the sequence node to the input of the "Move To" task.

8.Add a "Wait" task after the "Move To" task: • Drag and drop the "Wait" task from the palette onto the graph. • Connect the output of the "Move To" task to the input of the "Wait" task.

9.After completing all the steps, place the AI character in the viewport: • Drag and drop the AI character Blueprint into the viewport to place it. • Ensure that the third-person character is also present in the scene for the AI character to chase.

### OUTPUT:

### Content browser:


### Third_Person character:
![a2](https://github.com/durga46/exp6.gameprogramming/assets/75235704/bb16ee9f-1be3-4b9b-b444-2bae091dbecd)


### AI character:
![a3](https://github.com/durga46/exp6.gameprogramming/assets/75235704/84893d52-666c-4932-baa1-22d4e7508c0d)


### AI Controller Event graph:
![a4](https://github.com/durga46/exp6.gameprogramming/assets/75235704/9a0f40a9-b438-4cbc-b2d1-732adef0105a)


### MY Black Board:
![a5](https://github.com/durga46/exp6.gameprogramming/assets/75235704/0e68dd7f-2f98-4108-8a8b-1b5e5d54f6ec)


### MY Behavior tree:
![a6](https://github.com/durga46/exp6.gameprogramming/assets/75235704/ff68c589-ce48-4a32-957f-c254e99934fb)


### Service:
![a7](https://github.com/durga46/exp6.gameprogramming/assets/75235704/9b326852-0577-4659-bef5-b5003f59549f)




### AI Movement:
![WhatsApp Image 2023-06-08 at 5 56 38 PM (2)](https://github.com/durga46/exp6.gameprogramming/assets/75235704/c03b3479-189f-4520-8812-3f0677278b88)


### Results:
Thus we successfully created a Unreal project That have AI character To Chase the Player
