# How to Solve a Problem in Introductory Physics Classes

## The Problem: A Box Slides Down A Ramp

Let's consider the below problem, which is a common type of problem found in all introductory physics classes.

A box with a mass of 40kg starts at the top of a ramp that is 3 m long with an angle of 30 degrees and slides down to the bottom.  The coefficient of kinetic friction between the box and the ramp is 0.25.  Find the speed of the box at the bottom of the ramp.

## Steps to Solve a Physics Problem

#### 1. Choose a reference frame

This sounds like a scary step but for introductory physics classes all it means is you have to set where t=0 occurs, where the spatial origin (i.e. **r** = (0, 0, 0)) is, and how the coordinate axes should be rotated.

#### 2. Draw a picture

If a picture is not provided with the problem, draw one.  Even a rough sketch is better than no picture at all.  When drawing the pictures think about all forces that could be acting on the object and draw those in as well.  Also add in arrows representing other vectors you know (displacement, velocity, etc.).

#### 3. List any assumptions that you have to make to simplify the problem.

#### 4. Write down any knowns, separated by the direction in which they are relevant

#### 5. Write down any unknowns you need to solve for, separated by the direction in which they are relevant

#### 6. Using the knowns and unknows as a guide, write down an equations that may be helpful to solve the problem

#### 7. Combine the equations and known values to solve for the unknowns you need

## Using These Steps to Solve a Physics Problem

A box with a mass of 40kg starts at the top of a ramp that is 3 m long with an angle of 30 degrees and slides down to the bottom.  The coefficient of kinetic friction between the box and the ramp is 0.25.  Find the speed of the box at the bottom of the ramp.

1. Choose a reference frame

For this problem, let'ss choose the starting time to be the time the box starts to move.  Let's choose the origin to be the box's starting position.  For the orientation of the coordinate axis (in this case only the xy coordinate plane) let's arange the x axis so that it is in line with the ramp and the y axis will then be perpendicular to that.  This is a very typical way to orient the axes for a ramp problem.

2. Draw a picture

![Ramp Problem Picture](ramp.png)

3. List any assumptions that you have to make to simplify the problem.

* We are assuming that the only forces on the box are gravity and friction.  Therefore there are no other forces like air resistance.
* The box and ramp are located on Earth (this is not directly said).
* The box starts from rest and is given no initial velocity from a push.
* We do not need to take into account static friction.
* The third dimension, z, is not important for this problem.
* Motion only occurs in the x direction.

4. Write down any knowns, separated by the direction in which they are relevant

The only knowns given in the problem are the mass of the box, the length of the ramp, the angle of the ramp, and the coefficient of friction.  However, from the drawing and our assumptions we can fill out a few more knowns.  We known that the starting position of the box is the origin, the box starts from rest, and the motion occurs only in the x direction (i.e. r$$_y$$ = v$$_y$$ = a$$_y$$ = 0).

|                x                   |                y                 | No direction|
|------------------------------------|----------------------------------|-------------|
|length of ramp, d$$_x$$ = 3m        |velocity, v$$_y$$ = 0m/s          |mass, m = 40kg|
|initial velocity, v$$_{i,x}$$ = 0m/s|acceleration, a$__y$$ = 0m/s$$^2$$|coefficient of friction, $$\mu_k$$ = 0.25|
|initial position, r$$_{i,x}$$ = 0m  |position, r$$_{y}$$ = 0m          |ramp angle, $$\theta$$ = 30 degrees|

5. Write down any unknowns you need to solve for, separated by the direction in which they are relevant

The unknown we eventually need to solve for is the final velocity in the x direction, but there are some other unknowns that could be helpful in solving for that.

|              x                 |               y                |
|--------------------------------|--------------------------------|
|final velocity, v$$_{f,x}$$     |force of gravity, F$$_{grav,y}$$|
|force of friction, F$$_{fric}$$ |normal force, F$$_N$$           |
|force of gravity, F$$_{grav,x}$$|                                |
|acceleration, a$$_x$$           |                                |

6. Using the knowns and unknows as a guide, write down an equations that may be helpful to solve the problem

* Since we are looking for final velocity there are two kinematic equations that could give us that:
$$v_f^2 = v_i^2 + 2ad$$
$$v_f = v_i + at$$

* A lot of the knowns are forces, but the equations for those are known:
$$F_{net} = ma$$_{net}$$
$$F_{fric} = \mu_kF_N$$
$$F_{grav,x} = mgsin(\theta)$$
$$F_{grav,y} = mgcos(theta)$$
$$F_N = -F_{grav,y}$$

7. Combine the equations and known values to solve for the unknowns you need

Since it does not appear that we have time, a useful equation to find final velocity would be:

$$v_f^2 = v_i^2 + 2ad$$

Since we know that the motion will only be in the x direction, then we can add that into the equation:

$$v_{f,x}^2 = v_{i,x}^2 + 2a_xd_x$$

The length of the ramp, which is d$$_x$$ is given, the initial velocity v$$_{i,x}^2$$ is zero since we assume that the box starts from rest.  Plugging in these values reduces the above equation to (including units):

$$v_{f,x}^2 = (6m)a_x$$

Now all we need to do is find an expression for a$$_x$$ in terms of our knowns.  From Newton's second law we know:

$$\textbf{F}_{net} = m\textbf{a}$$

so in terms of only the x direction we have:

$$F_{net,x} = ma_x$$

which means that in order to find an expression for a$$_x$$, we need to find F$$_{net,x}$$.  Refering to the picture we drew in step two, there are two forces in the x direction: friction and the x component of gravity.

Using the equation for above we can express the force of friction as:

$$F_{fric,x} = \mu_kF_N$$

But we also know that $$F_N = -F_{grav,y}$$, so:

$$F_{fric,x} = \mu_kF_N = -\mu_kF_{grav,y} = -\mu_kmgcos(
theta)$$

And we have the equation for the the x component of gravity written above:

$$F_{grav,x} = mgsin(\theta)$$

So adding these two forces together will give us the net force:

$$F_{net,x} = F_{fric,x} + F_{grav,x} = -\mu_kmgcos(
theta) + mgsin(\theta) = mg(sin(\theta) - \mu_kcos(\theta))$$

But we also know that $$F_{net,x} = ma_x$$ so:

$$F_{net,x} = ma_x = mg(sin(\theta) - \mu_kcos(\theta))$$

$$a_x =  g(sin(\theta) - \mu_kcos(\theta))$$

So now that we have the acceleration in the x-direction, we can plug it back into the equation for final velocity and solve the equation:

$$v_{f,x}^2 = (6m)a_x = (6m)g(sin(\theta) - \mu_kcos(\theta)) = (6m)(9.81m/s^2)(sin(30) - 0.25cos(30))$$

$$v_{f,x}^2 = 16.686 m$$^2$$/s$$^2$$$$

$$v_{f,x} = 4.084 m/s$$

So as a check to see if our answer is correct, the units are correct for velocity and 4.084 m/s corresponds to about 9 mph, which is relatively slow but seems achievable for a box on a rather long ramp with a rather low coefficient of friction.  So numerically and unit wise the answer checks out! 

This is a rather long winded solution, but you would not write all of this down typically when solving a problem.  Here is what a solution to this problem would typically look like:

![Solution](solution.png)