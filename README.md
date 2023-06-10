# Ex No :06

## <p align="center">  Implement the AI random movement </p>

### Aim:
To create a Unreal project That have AI character To Chase the Player

### Procedure:
Open Unreal Engine and create a new Blueprint project.
Create a Blueprint class for your character: 
• Right-click in the Content Browser and select "Blueprint Class." 
• Choose "Character" as the parent class. 
• Name the Blueprint as desired.
Create a Blueprint class for the AI controller: • Right-click in the Content Browser and select "Blueprint Class." • Choose "AI Controller" as the parent class. • Name the Blueprint as desired.
Open the AI controller Blueprint: • In the Event Graph, right-click and search for "Blackboard." • Add a "Blackboard" node to the graph and name it "MyBoard."
Open the Blackboard: • Create a new Key named "TargetLoc" with the Vector data type.
Create a Behavior Tree (BT) Blueprint: • Right-click in the Content Browser and select "Blueprint Class." • Choose "Behavior Tree" as the parent class. • Name the Blueprint as desired.
Open the Behavior Tree Blueprint: • Create a sequence node by dragging and dropping it from the palette onto the graph. • Connect the sequence node to the root node.
Add a "Move To" task to the sequence: • Drag and drop the "Move To" task from the palette onto the graph. • Connect the output of the sequence node to the input of the "Move To" task.
Add a "Wait" task after the "Move To" task: • Drag and drop the "Wait" task from the palette onto the graph. • Connect the output of the "Move To" task to the input of the "Wait" task.
After completing all the steps, place the AI character in the viewport: • Drag and drop the AI character Blueprint into the viewport to place it. • Ensure that the third-person character is also present in the scene for the AI character to chase.
OUTPUT:
Content browser:
image

Third_Person character:
image

AI character:
image

AI Controller Event graph:
image

MY Black Board:
image image

MY Behavior tree:
image

Service:
image

Prethi>ee

AI Movement:
image

Results:
Thus we successfully created a Unreal project That have AI character To Chase the Player
