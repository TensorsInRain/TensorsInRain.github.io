{% include head.html %}

# Simple Projectile Motion With Kinematics

A common type of question in an introductory mechanics class involves solving a  simple projectile motion problem with kinematic equations.  This type of problem is usually introduced fairly early in the course.  Simple projectile motion problems deal with the motion of an object given an initial speed and launch angle.  This tutorial will go over main calculations from simple projectile motion problems using kinematic equations, as well as a couple of example problems.

## Problem Set-up

An object with some mass, m, is launched with some initial speed, v$$_i$$, and at some angle, $$\theta$$.

## Main Assumptions

It is always important to know what assumptions you are making in a physics problem, even if you do not directly reference them.  Here is a list (by no means complete) of assumptions that are commonly made in simple projectile motion problems.

* Motion only takes place in two dimensions: x (horizontal) and y (vertical).
* There is no air resistance or any other forces acting on the projectile besides gravity.
* The object is near Earth's surface so gravitational acceleration can be represented as (0, -9.81) m/s$$^2$$.
* The object is a point mass particle, meaning that it has mass but no size.
* All measurements and answers will be in SI units.
* Unless told otherwise, the object's initial position is (0, 0)m.
* Unless told otherwise, the object's final y position is 0m.

## Initial Velocity

### Short Answer

In vector form: $$\textbf{v_i}$$ = (v$$_i$$cos($$\theta$$), v$$_i$$sin($$\theta$$)) (remember that bold quantities are vectors and non-bold quantities are scalars)

In component form: v$$_{i,x}$$ = v$$_i$$cos($$\theta$$); v$$_{i,y}$$ = v$$_i$$sin($$\theta$$)

### Long Answer

Any two dimensional vector in the xy-coordinate plane, **b** = (b$$_x$$, b$$_y$$), can be written as follows:

$$ \textbf{b} = (bcos(\theta), bsin(\theta))$$

where b is the magnitude of the vector **b** (b = $$\sqrt(b_x^2 + b_y^2))$$) and $$\theta$$ is the angle the vector makes with the x axis.

Therefore given the speed (which is the magnitude of the velocity vector) and the angle the ball is kicked at (the angle between the x axis and the velocity vector), then the initial velocity of the ball can be written as $$\textbf{v_i}$$ = (v$$_i$$cos($$\theta$$), v$$_i$$sin($$\theta$$)) in vector form or v$$_{i,x}$$ = v$$_i$$cos($$\theta$$); v$$_{i,y}$$ = v$$_i$$sin($$\theta$$) in component form.

## Component Equations for Position, Velocity, and Acceleration as a Function of Time

### Short Answer

#### Position

r$$_x$$ = r$$_{x,i}$$ + v$$_i$$cos($$\theta$$)t

r$$_y$$ = r$$_{y,i}$$ + v$$_i$$sin($$\theta$$)t - 0.5gt$$^2$$

Typically r$$_{x,i}$$=r$$_{y,i}$$=0m, unless otherwise stated in the problem.

#### Velocity

v$$_x$$ = v$$_i$$cos($$\theta$$)

v$$_y$$ = v$$_i$$sin($$\theta$$) - gt

#### Acceleration

a$$_x$$ = 0

a$$_y$$ = -g

### Long Answer

The movement of any object in one dimension can be described as a function of time using this equation:

$$r = r_i + v_it + 0.5at^2$$

where r$$_i$$ is the intial position of the object, v$$_i$$ is the initial velocity of the object, a is the acceleration of the object (assumed to be constant), t is the time that has elapsed since the object started moving and r is the position of the object at time t.  All quantities in the above equation are taken to be the x or y components of the corresponding vectors.

Taking the derivative of the above equation with respect to time gives us the equation for the velocity of an object at any given time (since velocity if the derivative (rate of change) of position):

$$v = v_i + at$$

All variables represent the same thing that they did in the position equation and all quantities are taken to be the x or y components of the corresponding vectors.

Finally, the equation for acceleration as a function of time can be derived by taking the derivative of the velocity equation (since accleration is the derivative (rate of change) of velocity).  This simply gives:

$$ a = a$$

since it is assumed that acceleration does not change with time as the near earth gravitational force is constant.  

In the x direction there is an initial position, represented by r$$_{x,i}$$, and an initial velocity, which can be represented as v$$_{x,i}$$ = v$$_i$$cos($$\theta$$).  Since the only force acting on the projectile is gravity, and gravity only acts in the y direction, there is no acceleration in the x direction.  Plugging these values in to the above equations for position, velocity, and accleration yields:

$$r_x = r_{x,i} + v_icos(\theta)t$$

$$v_x = v_icos(\theta)$$

$$a_x = 0$$

In the y direction there is an initial position, represented by r$$_{y,i}$$, and an initial velocity, which can be represented as v$$_{y,i}$$ = v$$_i$$sin($$\theta$$).  Since the gravitational force acts in the y direction the acceleration in the y direction due to this force can be written as a$$_y$$ = -9.81m/s$$^2$$, or a$$_y$$ = -g, where g is the constant 9.81m/s$$^2$$.  Sometimes you will see this written as a$$_y$$ = g, where the negative sign is taken inside of into the g variable.  Using this information we can write the following equations for the position, velocity, and acceleration of the projectile in the y direction:

$$r_y = r_{y,i} + v_isin(\theta)t -0.5gt^2$$

$$v_y = v_isin(\theta) - gt$$

$$a_y = -g$$


## Vector Equations for Position, Velocity, and Acceleration as a Function of Time

### Short Answer

#### Position

**r** = **r$$_i$$** + **v$$_i$$**t + 0.5**a**t$$^2$$ = (r$$_{x,i}$$, r$$_{y,i}$$) + v$$_i$$(cos($$\theta$$), sin($$\theta$$))t + 0.5(0, -g, 0)t$$^2$$

Typically this is **r$$_i$$** = (0, 0)m, unless the problem statement tells otherwise

#### Velocity

**v** = **v$$_i$$** + **a**t = v$$_i$$(cos($$\theta$$), sin($$\theta$$)) + (0, -g, 0)t

#### Acceleration

__a__ = (0, -g, 0)

### Long Answer

The equations we derived above for the position, velocity, and acceleration in compoment form can be easily rewritten in vector form by replacing the component positions, velocities, and accelerations with their vector forms.  Therfore the equations for position, velocity, and acceleration as a function of time in vector form are:

$$\textbf{r} = \textbf{r_i} + \textbf{v_i}t + 0.5\textbf{a}t^2$$

$$\textbf{v} = \textbf{v_i} + \textbf{a}t$$

$$\textbf{a} = \textbf{a}$$

Using the component values that we wrote down in the previous section, we know that the initial x position is r$$_{x,i}$$ and the initial y position is r$$_{y,i}$$, so the initial position of the projectile in vector form is:

$$\textbf{r_i} = (r_{x,i}, r_{y,i})$$

Likewise, from the previous section we know that the initial velocity in the x direction is $$v_{x,i}$$ = v$$_i$$cos($$\theta$$) and the initial velocity in the y direction is $$v_{y,i}$$ = v$$_i$$sin($$\theta$$).  Therefore the initial velocity can be written in vector form as:

$$\textbf{v_i} = (v_icos(\theta), v_icos(\theta)) = v_i(cos(\theta), sin(\theta))$$

Finally, we know that there is know acceleration in the x direction and the acceleration in the y direction can be written as a$$_y$$ = -g.  Then, acceleration in vector form is:

$$\textbf{a} = (0, -g)$$

Now, taking the equations for initial position, initial velocity, and acceleration and plugging them into the vector equations for position, velocity, and acceleration as a function of time we get:

$$\textbf{r} = \textbf{r_i} + \textbf{v_i}t + 0.5\textbf{a}t^2 = (r_{x,i}, r_{y,i}) + v_i(cos(\theta), sin(\theta))t + 0.5(0, -g)t^2$$

$$\textbf{v} = \textbf{v_i} + \textbf{a}t = v_i(cos(\theta), sin(\theta)) + (0, -g)t$$

$$\textbf{a} = (0, -g)$$

## Time to Maximum Height

### Short Answer

$$t_{max\ y} = \frac{v_isin(\theta)}{g}$$

Note that for an object which starts and ends at ground level t$$_{max\ y}$$ = t$$_{1/2}$$ (which is one half of the total flight time).

### Long Answer 

The object will reach its maximum y position (i.e. the top of the arc) when the y component of velocity is zero.  To find this time, take the equation for the y component of velocity (defined above) and set it equal to zero.  Then simply solve for t:

$$v_y = v_isin(\theta) - gt_{max\ y} = 0$$

$$t_{max\ y} = \frac{v_isin(\theta)}{g}$$

## Maximum Height

### Short Answer

$$r_{y,max} = r_{y,i} + \frac{v_i^2sin^2(\theta)}{2g}$$

### Long Answer

The maximum height (y position) occurs at the time found above.  Plug that time into the component equation for the y position to get the maximum height.

$$r_y = r_{y,i} + v_isin(\theta)t - 0.5gt^2$$

$$t_{max\ y} = \frac{v_isin(\theta)}{g}$$

$$r_{y,max} = r_{y,i} + v_isin(\theta)\frac{v_isin(\theta)}{g} - 0.5g(\frac{v_isin(\theta)}{g})^2$$

$$r_{y,max} = r_{y,i} + \frac{v_i^2sin^2(\theta)}{2g}$$

## Y Velocity the Instance Before the Object Hits the Ground

### Short Answer

v$$_{y,f} = -\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})}$$

The minus sign is there to denote direction.  Note that if the object leaves the ground at the same y position that it hits the ground then v$$_{y,f}$$ = -v$$_{y,i}$$ = -v$$_i$$sin($$\theta$$).

### Long Answer

Since the total time is not known, we need to use an equation that does not contain time:

$$v_{f}^2 = v_{i}^2 + 2ad$$

where d represents distance.  Plugging in v$$_{y,i}$$ = v$$_i$$sin($$\theta$$), a = -g, and d = r_{y,f} - r_{y,i} and solving for v$$_{y,f}$$ yields:

$$v_{y,f} = -\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})}$$

where the negative sign (coming from the square root) is there to denote the direction (i.e. the ball is moving downward).

## Total Time

### Short Answer

$$t_{tot} = \frac{\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})} + v_isin(\theta)}{g}$$

Note that for an object landing at the same y position it was launched from 

$$t_{tot} = 2t_{max\ y} = \frac{2v_isin(\theta)}{g}

### Long Answer

Using the velocity equation for the y direction:

$$v_{y,f} = v_{y,i} - gt$$

and then solving for t:

$$t = \frac{-(v_{y,f} = v_{y,i})}{g}$$

Plug in the result for final velocity found above and simplify the signs:

$$t_{tot} = \frac{\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})} + v_isin(\theta)}{g}$$


## Total Range

### Short Answer

$$r_{f,x} = r_{i,x} + v_icos(\theta)\frac{\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})} + v_isin(\theta)}{g}$$

Note that for an object landing at the same y position it was launched from 

$$r_{f,x} = r_{i,x} + \frac{2}{g}v_i^2cos(\theta)sin(\theta)$$

### Long Answer

Starting with the kinematic equation for position

$$r_f = r_i + v_it + 0.5at^2$$

and plugging in a = 0 (for the x direction), v$$_i$$ = v$$_i$$cos(\theta), and t = t$$_{tot}$$:

$$r_{f,x} = r_{i,x} + v+icos(\theta)\frac{\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})} + v_isin(\theta)}{g}$$

## Example 1: Ball Kicked from Ground Level

A ball with a mass of 0.1kg is kicked with an initial speed of 15m/s at an angle of 32 degrees.

a. Find the time the ball needs to get to its maximum height.

b. Find the maximum height the ball obtains.

c. Calculate the total time the ball will be in the air.

d. Calculate the x position where the ball will land.

#### Part a

Using the equation from above

$$t_{max\ y} = \frac{v_isin(\theta)}{g}$$

And plugging in the given values:

$$t_{max\ y} = \frac{(15m/s)sin(32)}{9.81m/s^2} = 0.810s$$

#### Part b

Using the equation above 

$$r_{y,max} = r_{y,i} + \frac{v_i^2sin^2(\theta)}{2g}$$

and plugging in the given values:

r$$_{y,max}$$ = $$0m + \frac{(15m/s)^2sin^2(32)}{2(9.81m/s^2)} = 3.220m$$

At t=0.810s the y position of the ball is r$$_y$$ = 3.220m, the maximum y height the ball will obtain.

#### Part c

Using the fact that the total time is just double time time needed to get to the maximum y position, then:

$$t_{tot} = 2t_{max\ y} = 1.62s$$

Note that this equation only works for a ball that is launched and lands at the same same y position.

#### Part d

Using the equation from above:

 $$r_{f,x} = r_{i,x} + \frac{2}{g}v_i^2cos(\theta)sin(\theta)$$

 And plugging in the given values:

 $$r_{f,x} = 0m + \frac{2}{9.81m/s^2}(15m/s)^2cos(32)sin(32) = 20.6m$$

 This means that at t=1.62s the position of the ball is **r$$_f$$** = (20.6m, 0m).

## Example 2: Ball Thrown from a Building
A ball of mass 0.1kg is thrown from a building that is 30m tall with an initial speed of 10m/s at an angle of 45 degrees.

a. As a vector, calculate the initial velocity of the ball.

b. As a vector, calculate the position of the ball when it is at its maximum y distance.

c. As a vector, calculate the velocity of the ball the instant before it hits the ground.

d. As a vector, calculate the position of the ball when it hits the ground.

#### Part a

Using the equation from above:

$$\textbf{v_i} = (v_icos(\theta), v_isin(\theta))$$

And plugging in the given values:

$$\textbf{v_i} = (10\frac{m}{s}cos(45), 10\frac{m}{s}sin(45)) = (7.07\frac{m}{s}, 7.07\frac{m}{s})$$

#### Part b

First, we need to the the time the ball will be at its maximum height.  Using the equation from above and plugging in the given values:

$$t_{max\ y} = \frac{(10m/s)sin(45)}{9.81m/s^2} = 0.720s$$

Second, we need to find the y position at this time.  This corresponds to the maximum height, so using the equation above and plugging in the given values:

$$r_{y,max} = 30m + \frac{(10m/s)^2sin^2(45)}{2(9.81m/s^2)} = 32.5m$$

Third, we need to find the x position at this time.  This equation is not above, but we can easily derive it using the equation for the x position at t = t_{max\ y}:

$$r_{x,max\ y} = r_{x,i} + v_{i,x}t_{max\ y}$$

$$r_{x,max\ y} = v_icos(\theta)\frac{v_isin(\theta)}{g}$$

$$r_{x,max\ y} = \frac{v_i^2cos(\theta)sin(\theta)}{g}$$

$$r_{x,max\ y} = \frac{(10m/s)^2cos(45)sin(45)}{9.81m/s^2} = 5.09m$$

Finally, combining these results into a vector:  **r$$_{max\ y}$$** = (32.5m, 5.09m)

#### Part c

First, we know that the x velocity of the ball does not change, so v$$_{x,i}$$ = v$$_{x,f}$$ = v$$_i$$cos($$\theta$$) = 10cos(45) = 7.07m/s.

Next, when the ball hits the ground, we know that its y position is zero, because we set the zero point of the y axis to be the ground.  Therefore r$$_{y,f}$$ = 0.  Then, we have an equation for the velocity in the y direction the instant before the ball hits the ground. Using the equation from above and plugging in the given values:

v$$_{y,f} = -\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})} = -\sqrt{(10m/s)^2sin^2(45) - 2g(0m - 30m)} = -25.2m/s$$

Finally, combining these results into one vector yields:  **v$$_f$$** = (7.07m/s, -25.2m/s).

Note: You could also solve this problem by solving for the total flight time and then plugging this value into the the equation for velocity as a function of time in vector form.

#### Part d

First, when the ball hits the ground, we know that its y position is zero, because we set the zero point of the y axis to be the ground.  Therefore r$$_{y,f}$$ = 0.

Next, we have an equation for the total range of the projectile, which is the final x position if we assume the projectile's initial x position is 0m.  Using the equation from above and plugging in the given values:

$$r_{x,f} = r_{i,x} + v_icos(\theta)\frac{\sqrt{v_i^2sin^2(\theta) - 2g(r_{y,f} - r_{y,i})} + v_isin(\theta)}{g} = 0m + (10m/s)cos(45)\frac{\sqrt{(10m/s)^2sin^2(45) - 2g(0m - 30m)} + (10m/s)sin(45)}{g}$$

$$r_{x,f} = 465.4m$$

Finally, combining these results into one vector yields: **r$$_f$$** = (465.4m, 0m).

Note: You could also solve this problem by solving for the total flight time and then plugging this value into the the equation for position as a function of time in vector form.

