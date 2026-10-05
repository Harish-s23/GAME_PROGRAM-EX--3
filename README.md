# GAME_PROGRAM-EX--3

## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure
Import New Character Mesh and Animations:

In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files).
Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).
Replace Character Mesh:

Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
Select the Mesh component.
In the Details Panel, change the Skeletal Mesh to the newly imported mesh.
Set Animation Blueprint:

If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
If not available, create one:
Right-click in the Content Browser → Animation → Animation Blueprint.
Choose the correct skeleton.
In the AnimGraph, set up state machines or direct animation nodes.
Compile and save.
Preview and Test:

Place the character in the level.
Press Play to test idle, walk, and run animations based on character movement.

## Output:

<img width="1036" height="700" alt="Screenshot 2026-10-05 202505" src="https://github.com/user-attachments/assets/8d2ca993-ffb1-40f1-9c2c-154a59173695" />

<img width="582" height="512" alt="Screenshot 2026-10-05 202513" src="https://github.com/user-attachments/assets/337ef2d5-54d2-40cc-ac66-12e05535b6e6" />
<img width="1045" height="615" alt="Screenshot 2026-10-05 202528" src="https://github.com/user-attachments/assets/9aad6928-9ff3-4b97-a730-f422145e3081" />


## Result:

Thus Changing the third-person character mesh and adding animations is implemented Successfully.
