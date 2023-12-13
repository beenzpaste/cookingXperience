# Cooking Xperience - A Cooking Simulation

CPE Unity VR Project, Fall 2023

Sheena Chiang, Nada Beltagui, Razan Lakis, Assia Ben El Barguia

### About this project:
The creators of this game aimed to create an educational game-like simulation that familiarizes the user in the kitchen by guiding the user through basic tasks and warning against common dangers in the kitchen.

### Simulation Objective:
Following four crucial steps, learn to cook a healthy vegetable dish from start to finish, familiarizing yourself with basic equipment, tasks, and safety considerations in the kitchen in the process

## User Manual
- Load the VR simulation file onto the Meta Quest headset
- Read the instructions in the black box before the user as the user spawns. A series of similar instructions will guide the user through the simulation.
- **Task One:** Retrieve the carrot by grabbing it with the left or right controller. Navigate to the sink on the far right of the kitchen.
- **Task Two:** Turn on the faucet by touching the right controller to the faucet knob on the right. Once water begins flowing, bring the carrot from the fridge under the running particles of water.
- **Task Three:** Navigate to the cutting board. Grab the carrot with the left controller and the knife with the right. This can be reversed. Touch the knife to each segment of the carrot. The carrot pieces will fall. Retrieve the carrot pieces by touching the right controller to each piece. Each piece will appear in the pan on the right.
  - Note: If the knife touches the left hand, a warning sign will pop up, and the environment will turn red. After 5 seconds, the warning sign will vanish and the environment will revert back to normal.
- **Task Four:** Navigate to the pan. Retrieve the celery pieces in the plate on the left by touching the right controller to each piece, and each piece will appear in the pan. Turn on the stove by touching the right controller to the stove knob on the right. The stove will turn red to indicate that the heat is on. Grab the spatula on the right with either controller, then maneuver it to stir the vegetable pieces around in the pan.
  - Note: If the right hand touches the pan while the heat is on (as indicated by a red stovetop), a warning sign will pop up, and the environment will turn red. After 5 seconds, the warning sign will vanish and the environment will revert back to normal.
 
## Challenges Encountered
- Minor Bugs
  - The cut vegetables did not respawn at the correct coordinates after being retrieved
  - Vegetables rolled off the pan
  - The spawned inside the fridge due to an unexpected camera
  - The running water sound would start playing when the simulation began
- Inconsistencies in actions
  - At times, the carrot does not appear in the pan after being retrieved
- Implementing a starting scene
- Implementing instructions that appear in the user's peripheral vision
  - Repository files commented as "NOT USED" was a result of attempts to implement this

