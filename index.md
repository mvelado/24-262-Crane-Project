<link rel="stylesheet" href="img.css">
# Crane Project Team 30
## Sarah Jurgens, Hans Kumar, Sidney Velado

### Mechanism:

<center>Our Crane</center>
![Image](/cover.png){: .center-image }

Our crane can be divided into three components: The lever arm, the crane arm, and the base. Each part was designed to minimize torsion and bending, the two main challenges we forsaw in this project. 

<center>The Lever Arm</center>
![Image](/leverarm.png){: .center-image }

The lever arm is made up of a hook on one end, a counterweight on the other, and the servo motor attached at the middle. The counterweight assists the servo motor in lifting the cylinder weight, which is lifted up using the hook.

<center>Crane Arm</center>
![Image](/cranearm.png){: .center-image }

The crane arm is a triagular cross sectional truss. Its design allows it to resist the torsion and bending caused by the lever arm and servo motor.

<center>Base</center>
![Image](/newbase.png){: .center-image }

We designed our crane to maximize the stress on the base, since it is the most structurally sound component. The base has a similar truss design as the crane arm and is screwed into the bottom metal plate.

### Theoretical Predictions

**Theoretical Servo Torque Calculations**

 1. Assumptions
 - We assume that no forces being applied to the motor (i.e. friction)

 2. Variables
```markdown
- Tm = 57 oz-in (Maximum torque of Servo motor)
- Wcyl = 16 oz (Weight of the cylinder)
- Wcw = 4 oz (Weight of the counter weight)
- Darm = 4 in (Distance between motor and weight)
- Tu = Torque of Motor used
- r = ? (Ratio maximum torque used)
```
 3. Calculations
![Image](/Calculation.png)

 4. Results
 We estimate to use 84.2% of the motor's torque with our design. 
 
**Theoretical Lift Distance Calculations**

 1. Assumptions
 - We assume that that the torque and angle of rotation vary linearly
 
 2. Variables 
```markdown
- øm = 45º (Maximum angle of rotation)
- hm = 2 in (Maximum height of lift)
- Darm = 4 in (Lenght of Arm)
- h = ? (Actual height of lift)
```
 3. Calculations
![Image](/calcLiftFinal.png)

 4. Results
 We estimate the maximum lift to 5.65 inches

### Interesting and Original Features

One of our favorite parts of our project was our crane arm truss. While many groups chose rectangular designs or diagonal truss links, we decided on triangles because it appeared the sturdiest in terms of torsion (a factor we felt most groups had overlooked). Unsurprisingly, the arm truss was *very* resistant to torsion. Despite having to modify our design after the first design review, the crane arm was the most resilient feature and did not need any modifications. Although the process of assembling the arm was quite tedious, our hard work paid off when the servo motor fit perfectly inside and worked as planned.

<center>Crane Arm Truss</center>
![Image](/truss.png){: .center-image }

### Structural Principle Applications
The leap in our knowledge from our initial Statics class to Stress Analysis was very clear as our results improved drastically from Design Review I to Design Review II. Although our crane didn't collpase in the first design review, it was unable to lift any weight at all. The crane was clearly not suited to withstand the force of the weight.

For the second design review, we adapted our design to be able to handle the torsion and bending moments. For bending, we added additional supports to the base, which created a more even distribution of load as the attachment was closer to the source of the force. As we learned from cantaliver beams, which our crane resembled, the farther the force is from the support, the greater the deflection. For torsion, we decided to anchor our crane arm along more points in order to counteract the torsion moment caused by the weight of the lever arm. Additionally, we were able to maximize the torque from the motor by securing the hook farther away from the motor and attaching a counterweight on the opposite end.

The concepts we learned throughout the semester in Stress Analysis helped us immensely in designing our crane. Our knowledge of torsion and bending stress was critical to our success in this project.

<center>Design II Modifications</center>
![Image](/addsupp.png){: .center-image }
