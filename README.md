# Duck_Behaviour_Simulation

Description
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This Java program demonstrates the behavior of different types of ducks using the Strategy Design Pattern. It defines various swimming and flying behaviors that can be assigned dynamically to different duck types. The program follows object-oriented principles such as inheritance, abstraction, and interfaces.

Features
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Implements SwimBehavior and FlyBehavior as interfaces.<br/>

Provides different behaviors:<br/>

Swimming: Swim, Float, Drown<br/>

Flying: Fly, NotFly<br/>

Implements an abstract Duck class that delegates behavior to swim and fly behaviors.<br/>

Creates concrete duck types:<br/>

MallardDuck<br/>

RubberDuck<br/>

DecoyDuck<br/>

Uses composition to dynamically assign behaviors to ducks.<br/>

Demonstrates polymorphism and dynamic behavior assignment.<br/>

Class Structure<br/>

Interfaces:<br/>

SwimBehavior → Defines swim() method<br/>

FlyBehavior → Defines fly() method<br/>

Concrete Behavior Implementations:<br/>

Swim → Implements SwimBehavior<br/>

Float → Implements SwimBehavior<br/>

Drown → Implements SwimBehavior<br/>

Fly → Implements FlyBehavior<br/>

NotFly → Implements FlyBehavior<br/>

Abstract Duck Class:<br/>

Duck → Defines performSwim(), performFly(), and display()<br/>

Duck Types:<br/>

MallardDuck → Swims and flies<br/>

RubberDuck → Floats and doesn't fly<br/>

DecoyDuck → Sinks and doesn't fly<br/>
