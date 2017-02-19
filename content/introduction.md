# Introduction

Like any other kind of programming the best way is to cut down to pen and paper and design your idea before facing the IDE that can be distractive when you need to code a slighly complex function.

First it is defined what kind of variables you have, dividing them into inputs and outputs. For example in a radio controlled car, the trottle is an intput and the engine velocity is an output.

In microcontrollers the way of designing your project is by sketching a State Machine that is defined as follows:

![State Machine](https://i.stack.imgur.com/YHIVL.gif)

It is composed of various States that correspond to an output combination. In the given example, two combinations are possible, engine ON and engine OFF. Those States are reached conditionaly according to the given inputs.
These diagrams are very important so you don't forget to specify any state or a action for a given set of inputs, which could lead to a unexpected chain of events, and saves you some debugging time. 

You can research more about this matter, we just wanted to give you an overview, we can ignore this since we'll be making simple projects for now. However this becomes really important when dealing with real projects.

[Next](microcontroller.md)