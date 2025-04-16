# Team Information

| **Sl. No** | **Name** | **Roll No** | **USN**      |
|------------|----------|-------------|--------------|
| 1          |Parvatappa| 9           | 01fe24bcs142    |
| 2          |Tejas     | 11          | 01fe24bcs144    | 
| 3          |Subhash   | 24          | 01fe24bcs094    |
| 4          |Ankit     | 25          | 01fe24bcs095    |
| 5          |Prithvi   | 57          | 01fe24bcs021    | 

Team Guide Name---------Dr.Prasanth Sir



## Problem Statement

# Objectives

- **SEMI-AUTOMATIC**: The bot should perform the majority of the fruit plucking process with minimal human intervention.
- **USER FRIENDLY**: Easy to operate, with a simple interface for the user to control.
- **PORTABLE**: The bot should be lightweight and easy to transport.
- **OPERATES WITH MODERATE VELOCITY (RPM)**: The bot should operate at a moderate speed to avoid damaging the fruit.
- **SECONDARY BATTERY**: The bot should be equipped with a secondary battery to ensure longer operation time.
- **LESS OR NO DAMAGE**: The bot should pluck the fruits with minimal or no damage to them.

## Statement:

Design and develop a semi-automatic fruit plucking bot that is user-friendly, portable, and operates at a moderate velocity, working with a secondary battery, with less or no damage to the fruit.

---

# Constraints

- **LESS THAN ₹4000**: The total cost of the bot should not exceed ₹4000.
- **360° ROTATING ARM**: The bot must be equipped with a 360-degree rotating arm to reach fruits from all directions.
- **DIMENSION (30CM x 30CM x 30CM)**: The bot should be compact in size (30cm x 30cm x 30cm) to ensure ease of movement and usability in different environments.
- **FRUIT DETECTING RANGE OF 7M**: The bot should be able to detect fruit within a range of 7 meters.
- **FRUIT PLUCKING SPEED OF 6 FRUITS PER MINUTE**: The bot should be able to pluck fruits at a rate of 6 fruits per minute.

## Statement:

Design and develop a semi-automatic fruit plucking bot that is user-friendly, portable, and operates at a moderate velocity, working with a secondary battery, with less or no damage to the fruit. The bot should adhere to a budget of ₹4000. It should feature a 360° rotating robotic arm and be compact in size (30CM x 30CM x 30CM) for ease of movement in different harvesting environments. The bot must be able to detect fruit within a range of 7 meters, and pluck fruit at a rate of 6 fruits per minute.

---

# Functions

- **OBSTACLE DETECTING**: The bot should be able to detect and avoid obstacles in its path.
- **HOLDING THE FRUIT**: The bot should have a mechanism to securely grip the fruit once detected.
- **STORING THE FRUIT**: The bot must have a storage system to collect the plucked fruits.
- **DIFFERENT DIRECTION OF MOVEMENTS**: The bot should be able to move in multiple directions to navigate the environment and reach the fruits.

## Statement:

Design and develop a semi-automatic fruit plucking bot that is user-friendly, portable, and operates at a moderate velocity, working with a secondary battery, with less or no damage to the fruit. While adhering to a budget of ₹4000, the bot should feature a 360° rotating robotic arm. It should be compact (30CM x 30CM x 30CM), able to sense fruits within 7m, and pluck fruits at a speed of 6 fruits per minute. The bot should also be capable of detecting obstacles, securely holding the fruit, plucking it efficiently, and storing the harvested fruit. It should move in different directions to navigate its environment. The solution should balance cost-effectiveness, functionality, and automation to make fruit plucking more efficient and accessible.








| No. | Questions                                              | Answers                                            | Objective | Function | Constraint |
|-----|--------------------------------------------------------|----------------------------------------------------|-----------|----------|------------|
| 1   | What it will pluck                                     | Fruits                                             |           | Yes      |            |
| 2   | What will be the budget of the project                 |                                                    |           | Yes      |            |
| 3   | What will be the type of automation of the bot         | Semi automatic                                     | Yes       |          |            |
| 4   | Will it detect the different types of fruits           | Yes                                                | Yes       |          |            |
| 5   | At what angle the bot arm will rotate                  | 360                                                |           | Yes      |            |
| 6   | What is the source of power supply                     | Secondary battery                                  | Yes       |          |            |
| 7   | Is it easily able to carry (portable)                  | Yes                                                | Yes       |          |            |
| 8   | Is the bot ecofriendly                                 | Yes                                                | Yes       |          |            |
| 9   | What is the dimension of the bot                       |                                                    |           | Yes      |            |
| 10  | What range can it identify the fruit                   |                                                    |           | Yes      |            |
| 11  | What is the arm rotation speed                         |                                                    |           | Yes      |            |
| 12  | Will the bot contain obstacle detecting                | Yes                                                | Yes       |          |            |
| 13  | Will the robotic arm contain grip to hold and rotate   | Yes                                                | Yes       |          |            |
| 14  | Will the bot contain any storage facilities            | Yes                                                | Yes       |          |            |
| 15  | Will the bot have any sensing of storage overload      | Yes                                                | Yes       |          |            |
| 16  | Frequency of the fruit plucking per minute             |                                                    |           | Yes      |            |
| 17  | What will be the damage quality of the fruit           | Minimize                                           | Yes       |          |            |
| 18  | Will the arm be adjustable according to the fruit size | Yes                                                | Yes       |          |            |
| 19  | Will the bot move sideward based on fruit detection    | Yes                                                | Yes       |          |            |


# Activity 1: Functions from User and Designer Perspectives

The following table outlines the functions from both the **User Perspective** and the **Designer Perspective** for **TEAM5**.

| **SL. No.** | **Functions from User Perspective** | **Functions from Designer Perspective**     |
|-------------|------------------------------------|----------------------------------------------|
| 1           | Plucking the fruit                 |Fruit Detection                               |
| 2           |                                    |Fruit Storage                                 |
| 3           |                                    |Obstacle Sensing                              |
| 4           |                                    |Movement of the bot                           |
| 5           |                                    |Grip to hold the fruit                        |
| 6           |                                    |RPM of the rotating arm                       |
| 7           |                                    |Adjustment to fruit size                      |






| Serial No. | Subfunctions            | Means 1              | Means 2              | Means 3               | Means 4                    |
|------------|-------------------------|----------------------|----------------------|-----------------------|----------------------------|
| 1          | FRUIT DETECTION         | ULTRASONIC SENSOR    | FORCE SENSOR         | RGB CAMERA            | USER CONTROL               |
| 2          | OBSTACLE SENSING        | IR SENSOR            | TIME OF FLIGHT SENSOR| PHYSICAL CONTACT      | USER CONTROL               |
| 3          | MOVEMENT OF THE BOT     | WHEELED BOTS         | COUNTERWEIGHT SYSTEM | AERIAL DISPLACEMENT   | TRACKED MOTION             |
| 4          | STORAGE                 | BASKET               | TRAILER/CART         | SOFT PADDING          | CLIMATE CONTROLLED STORAGE |
| 5          | GRIP                    | SUCTION PULL         | CUTTING AND HOLDING  | ROTATING AND HOLDING  | TWO FINGER PULLING         |
| 6          | ROTATION OF ARM         | FINGERED GRIPPERS    | VACUUM GRIPPERS      |                       |                            |
| 7          | ARM ADJUSTMENT          | ROTATIONAL MOTION    | ANGLE ADJUSTMENT     | LINEAR ACTUATORS      | HEIGHT ADJUSTMENT          |


# Concept Design

| Serial No. | Subfunctions              | Concept 1             | Concept 2             | Concept 3             | Concept 4              |
|------------|---------------------------|-----------------------|-----------------------|-----------------------|------------------------|
| 1          | FRUIT DETECTION            | FORCE SENSOR          | ULTRASONIC SENSOR     | RGB CAMERA            | RGB CAMERA             |
| 2          | OBSTACLE SENSING           | PHYSICAL CONTACT      | IR SENSOR             | IR SENSOR             | USER CONTROL           |
| 3          | MOVEMENT OF THE BOT        | WHEELED BOTS          | TRACKED MOTION        | WHEELED BOTS          | COUNTERWEIGHT SYSTEM   |
| 4          | STORAGE                    | BASKET                | SOFT PADDING AND CUSHIONING | BASKET          | CLIMATE CONTROLLED STORAGE |
| 5          | GRIP                       | TWO FINGER PULLING    | CUTTING AND HOLDING   | TWO FINGER PULLING    | ROTATING AND HOLDING   |
| 6          | ROTATION OF ARM            | FINGERED GRIPPERS     | VACUUM GRIPPERS       | FINGERED GRIPPERS     | VACUUM GRIPPERS        |
| 7          | ARM ADJUSTMENT             | ANGLE AND ORIENTATION ADJUSTMENT | HEIGHT ADJUSTMENT  | ROTATIONAL MOTION      | ROTATIONAL MOTION      |


# Activity 2 - Function Tree

![](https://sigmawire.net/i/03/7lfRaE.jpg)







| **Design Objectives**     | **Weights** | **Design 1** | **Design 2** | **Design 3** | **Design 4** |
|---------------------------|-------------|--------------|--------------|--------------|--------------|
| **Safety**                | 9           | 0            | ++           | DATUM        | ,+           |
| **Ease of use**           | 7           | --           | +            | DATUM        | -            |
| **Portability**           | 5           | +            | +            | DATUM        | -            |
| **Use of standard parts** | 6           | -            | -            | DATUM        | -            |
| **Cost**                  | 6           | --           | -            | DATUM        | -            |
| **Score (+)**             |             | 5            | 30           | 0            | 9            |
| **Score (-)**             |             | -32          | -12          | 0            | -22          |
| **Total**                 |             | -27          | 18           | 0            | -13          |



# Justification for the Scores Given

The table below explains the scores assigned to each design based on specific objectives such as Safety, Ease of Use, Portability, Use of Standard Parts, and Cost. The justifications for the scores are also provided for each design.

|Design No.| Objective             |Score| **Justification for the Score**                                                                                                                                            |
|--------- |-----------------------|----|----------------------------------------------------------------------------------------|
|Design 1  | Battery Indicator     |6/10| The battery indicator is clear and easy to read. It provides accurate feedback, but might be slightly bulky in design.|
|          | Ease of Use           |7/10| The design is simple, but could benefit from clearer instructions or a more intuitive interface.|
|          | Portability           |5/10| Very portable with a compact design that makes it easy to carry and store. It’s lightweight and fits well in small spaces.                                                              |
|          | Use of Standard Parts |8/10| Standard parts are used, which makes the design reliable and easy to replace or repair. However, a couple of custom parts were required.                                               |
|          | Cost                  |8/10| The cost is slightly higher than expected due to the use of some custom components and materials. It could be more affordable with more standardization.                             |
|Design 2  | Safety                |9/10| This design incorporates excellent safety features, including overload protection and proper insulation, reducing risk.                                                               |
|          | Ease of Use           |8/10| The design is functional but requires more user interaction and some prior knowledge to operate efficiently.                                                                            |
|          | Portability           |9/10| The design is moderately portable; however, it's slightly larger and bulkier than other designs, making transportation a little more challenging.                                       |
|          | Use of Standard Parts |8/10| Uses predominantly standard parts, making it easy to repair and maintain. The use of non-standard parts was minimal.                                                                  |
|          | Cost                  |8/10| The use of high-end safety components raised the cost, making this design less affordable compared to others.                                                                          |
| Design 3 | Safety                |8/10| The design has adequate safety features but could be improved by adding more advanced fail-safe mechanisms.                                                                            |
|          | Ease of Use           |7/10| This design is user-friendly, with straightforward controls and minimal setup required.                                                                                               |
|          | Portability           |6/10| Compact and easy to transport. The lightweight structure and foldable components add to its portability.                                                                               |
|          | Use of Standard Parts |8/10| Standard parts are used, but a few custom components could make repairs or replacements more challenging.                                                                              |
|          | Cost                  |6/10| Reasonably priced, though slightly more expensive due to custom parts and premium materials.                                                                                           |
|Design 4  | Safety                |7/10| The design includes basic safety features, but lacks advanced safety mechanisms like automatic shutoffs or protection against extreme conditions.                                      |
|          | Ease of Use           |8/10| Moderately user-friendly, though it could benefit from more intuitive controls and clearer user guidance.                                                                              |
|          | Portability           |6/10| The design is bulkier, making it harder to transport. The size limits its overall portability.                                                                                        |
|          | Use of Standard Parts |5/10| Very high use of standard parts, ensuring ease of repairs and replacement. Few non-standard components.                                                                                |
|          | Cost                  |8/10| The cost is low compared to other designs due to the reliance on standard, inexpensive materials.                                                                                    |


Activity 2.1   Functional Clustering


![](https://sigmawire.net/i/03/YAx2r7.jpg)

# Activity 2.2 : Subsystem List

| SL. No. | Subsystem      |
|---------|----------------|
| 1       | Sensing unit   |
| 2       | Navigation unit|
| 3       | Storage unit   |
| 4       | Mechanics unit |


# Activity 3: Interaction Details

This activity focuses on the interaction details, including how the system components or subsystems communicate with each other and how the bot interacts with its environment.

Duration: 15 mins


#

| Identifying Unit  | SENSING UNIT | STORAGE UNIT |              
|-------------------|--------------|--------------|
| Spatial           |              |              |
| Data              | TICK         |              |
| Material          |              |              |

#

| Storing Unit | NAVIGATING UNIT | IDENTIFYING UNIT |
|--------------|-----------------|------------------|
| Spatial      |   TICK          |                  |
| Data         |                 |                  |
| Material     |                 |                  |

# 

| Plucking Unit  | STORAGE UNIT | MECHANICS UNIT |
|----------------|--------------|----------------|
| Spatial        |              |                |
| Data           |              | TICK           |
| Material       |              | TICK           |



