{% include head.html %}

# Simple Projectile Motion With Kinematics

A common problem in an introductory mechanics class involves simple projectile motion.  This type of problem is usually introduced fairly early in the course.  Simple projectile motion problems deal with the motion of an object given an initial speed and launch angle.  This tutorial will go over main calculations from simple projectile motion problems using kinematic equations, as well as a couple of example problems.

## Problem Set-up

An object with some mass, m, is launched with some initial speed, v$$_i$$, and at some angle, $$\theta$$.

## Main Assumptions

* Motion only takes place in two dimensions: x (horizontal) and y (vertical).
* There is not air resistance or any other forces acting on the object besides gravity.
* The object is near Earth's surface so gravitation acceleration can be represented as (0, -9.81) m/s^2.
* The object is a point mass particle, meaning that it has mass but no size.
* All measurements and answers will be in SI units.
* Unless told otherwise, the object's initial position is (0, 0)m.
* Unless told otherwise, the object's final y position is 0m.

## Initial Velocity

### Short Answer

In vector form: $$\textbf{v_i}$$ = (v$$_i$$cos($$\theta$$), v$$_i$$sin($$\theta$$)) (remember that bold quantities are vectors and non-bold quantities are scalars)

In component form: v$$_{i,x}$$ = v$$_i$$cos($$\theta$$); v$$_{i,y}$$ = v$$_i$$sin($$\theta$$)


## Component Equations for Position, Velocity, and Acceleration

### Short Answer

#### Position

r$$_x$$ = r$$+{x,i}$$ + v$$_i$$cos($$\theta$$)t

r$$_y$$ = r$$_{y,i}$$ + v$$_i$$sin($$\theta$$)t - 0.5gt$$^3$$

Typically r$$_{x,i}$$=r$$_{y,i}$$=0m, unless otherwise stated in the problem.

#### Velocity

v$$_x$$ = v$$_i$$cos($$\theta$$)

v$$_y$$ = v$$_i$$sin($$\theta$$) - gt

#### Acceleration

a$$_x$$ = 0

a$$_y$$ = -g

## Vector Equations for Position, Velocity, and Acceleration

### Short Answer

#### Position

**r** = **r$$_i$$** + **v$$_i$$**t + 0.5**a**t$$^2$$ = (r$$_{x,i}$$, r$$_{y,i}$$) + (v$$_i$$cos($$\theta$$), v$$_i$$sin($$\theta$$))t + 0.5(0, -g, 0)t$$^2$$

Typically this is **r$$_i$$** = (0, 0)m, unless the problem statement tells otherwise

#### Velocity

**v** = **v$$_i$$** + **a**t = (v$$_i$$cos($$\theta$$), v$$_i$$sin($$\theta$$)) + (0, -g, 0)t

#### Acceleration

__a__ = (0, -g, 0)


## Time to Maximum Height

### Short Answer

```markdown
$$t_{max\ y} = \frac{v_isin(\theta)}{g}$$
```

Note that for an object which starts and ends at ground level t$$_{max\ y}$$ = t$$_{1/2}$$.

### Long Answer 

The object will reach its maximum y position (i.e. the top of the arc) when the y component of velocity is zero.  To find this time, take the equation for the y component of velocity (defined above) and set it equal to zero.

v$$_y$$ = v$$_i$$sin($$\theta$$) - gt$$_{max\ y}$$ = 0

$$t_{max\ y} = \frac{v_isin(\theta)}{g}$$

## Total Time

## Total Range

## Maximum Height

## Example 1: Ball Kicked from Ground Level

A ball with a mass of 0.1kg is kicked with an initial speed of 15m/s at an angle of 32 degrees.

a. Find the total time the ball will be in the air.

b. Find the maximum height the ball obtains.

c. Calculate where the ball will land.

#### Part a

## Example 2: Ball Thrown from a Building
