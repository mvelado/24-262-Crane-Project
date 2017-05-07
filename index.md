# Crane Project Team 30
## Sarah Jurgens, Hans Kumar, Sidney Velado

### Mechanism:

Our crane is divided into three main parts: The lever arm, the crane arm, and the base. Each part was designed to prevent what torsion and bending, the two main challenges we forsaw in this project. The way our mechanism works is by putting as much stress on the base, as it is the most structurally sound. To put in perspective, everything starts at the lever arm. the lever arm has a "hook" that connect with the weight in order to lift it. The lever arm is screwed into the servo motor horn in order to turn and lift the weight. Additionally, it has a counter weight at the opposite end of the hook, in order to assist the servo motor in lifting the weight. That servo motor is screwed into our crane arm. The crane arm is a triagular cross section truss. It's design allows it to resist the torsion and bending caused by the lever arm and servo. The crane arm is then screwed into our base, which supports the whole crane, with a similar trust design. That is then secured to the bottom metal plate, which is held in place by two metal clamps. 

### Theoretical Predictions

**Theoretical Servo Torque Calculations**

 1. Assumptions
 - We assume that no forces being applied to the motor (i.e. friction)


 2. Variables
```markdown
- T = 56 oz-in (Maximum torque of Servo motor)
- W = 16 oz (Weight of the cylinder)
- D = 2 in (Distance between motor and weight)
- Tu = Torque of Motor used
- r = ? (Ratio maximum torque used)
```
 3. Calculations
![Image](/calcServo.png)

 4. Results
 We estimate to use 56.14% of the motor's torque with our design. 
 
**Theoretical Lift Distance Calculations**

 1. Assumptions
 - We assume that that the torque and angle of rotation vary linearly
 
 2. Variables 
```markdown
- øm = 90º (Maximum angle of rotation)
- hm = 2 in (Maximum height of lift)
- r = 56.14% (Ratio of max torque used)
- ø = ? (Actual angle of rotation)
- h = ? (Actual height of lift)
```
 3. Calculations
 will come

**Interesting and Original Features**
![Image](/truss.png)

One of our favorite parts of our project was our crane arm truss. Many people went with a rectangular designs or went with diagonal truss links. We decided to do our with the straight triangles because it appeared the sturdiest in terms of torsion. We knew that the holding the weight was going to be the priority for everyone, but the fact that they ingore torsion was going to make or break a lot of teams. Our arm truss was *very* resistant to torsion. Even though past the first designing phase we had to tweak certain parts of the lever arm or base, the crane arm was the most resilient component. We were also very proud because it's design made it very hard to screw since multiple screws would get in each other's way but we managed to do it after a big effor and it paid off. Finally, the servo motor fit perfectly into our arm. we had to saw off a bit off the bottom of it, but once that was done we could scren the servo perfecting into our crane arm where it fit flush. It was the most ardous part to build but also our favorite. 

**Structural Principle Applications**
The leap in our knowledge from our initial Statics class to Stress Analysis was very clear as we hopped from the first Design Review to the second Design Review. The first design review, our crane didn't collapse, which was good news, however, it was unable to lift the weight at all. The crane held and didn't get destroyed, but we had not properly prepared the base to withstand the torsion on the crane arm or the bending that would occur to the crane arm. 

<center>Design I Base</center>
![Image](/base.png)

As we learned those concepts in class, we adapted our design to be ready to withstand the torsion moments and bending moments. For the bending moments, we added additional supports to the base from the arm that extending closer to the servo motor and lever arm. The additional support distribute the load more and had the support end closer to the source of the force. As we learned from cantaliver beams; which our crane resembled a lot, the further the force is from the support, the greater the deflection. For the torsion, we also made sure to secure our arm along more points to the base as opposed to the singular two we had originally. These multiple anchor points made more moment to counter act the torsion moment caused by the weight of the servo and lever arm to where it wouldn't twist. Finally, since we finally had a much stronger moment to withstand the torsion moment, we could make it greater and add a counterweight which would help the servo motor lift the weight more easily to the 2 in. we needed. 

<center>Design II</center>

Overall, if we hadn't applied the concepts we picked up over Stress Analysis, we would have struggled a lot more to make our crane work. Our knowledge fo the concepts of torsion, and bending came in use a lot, especially for our design since it was a very direct approach, as I mentioned before, essentially a cantaliver beam. 
