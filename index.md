<link rel="stylesheet" href="img.css">
# Crane Project Team 30
## Sarah Jurgens, Hans Kumar, Sidney Velado

### Mechanism:

<center>Our Crane</center>
![Image](/cover.png){: .center-image }

Our crane can be divided into three components: The lever arm, the crane arm, and the base. Each part was designed to minimize torsion and bending, the two main challenges we forsaw in this project. 

<center>The Lever Arm</center>
![Image](/leverarm.png){: .center-image }

<center>The Hook</center>
![Image](/hook.png){: .center-image }

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
<center>Crane Arm Truss</center>
![Image](/truss.png){: .center-image }

One of our favorite parts of our project was our crane arm truss. While many people chose rectangular designs or diagonal truss links, we decided on triangles because it appeared the sturdiest in terms of torsion.
We knew that the holding the weight was going to be the priority for everyone, but the fact that they ingore torsion was going to make or break a lot of teams. Our arm truss was *very* resistant to torsion. Even though past the first designing phase we had to tweak certain parts of the lever arm or base, the crane arm was the most resilient component. We were also very proud because it's design made it very hard to screw since multiple screws would get in each other's way but we managed to do it after a big effor and it paid off. Finally, the servo motor fit perfectly into our arm. we had to saw off a bit off the bottom of it, but once that was done we could scren the servo perfecting into our crane arm where it fit flush. It was the most ardous part to build but also our favorite. 

### Structural Principle Applications
The leap in our knowledge from our initial Statics class to Stress Analysis was very clear as we hopped from the first Design Review to the second Design Review. The first design review, our crane didn't collapse, which was good news, however, it was unable to lift the weight at all. The crane held and didn't get destroyed, but we had not properly prepared the base to withstand the torsion on the crane arm or the bending that would occur to the crane arm. 

<center>Design I Base</center>
![Image](/base.png){: .center-image }

As we learned those concepts in class, we adapted our design to be ready to withstand the torsion moments and bending moments. For the bending moments, we added additional supports to the base from the arm that extending closer to the servo motor and lever arm. The additional support distribute the load more and had the support end closer to the source of the force. As we learned from cantaliver beams; which our crane resembled a lot, the further the force is from the support, the greater the deflection. For the torsion, we also made sure to secure our arm along more points to the base as opposed to the singular two we had originally. These multiple anchor points made more moment to counter act the torsion moment caused by the weight of the servo and lever arm to where it wouldn't twist. Finally, since we finally had a much stronger moment to withstand the torsion moment, we could make it greater and add a counterweight which would help the servo motor lift the weight more easily to the 2 in. we needed. 

<center>Design II</center>
![Image](/addsupp.png){: .center-image }

The concepts we learned throughout the semester in Stress Analysis helped us immensely in designing our crane. Our knowledge of torsion and bending stress was critical to our success in this project.
