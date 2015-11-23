# ImageJ-Troubleshooting
An interactive toy repository to demonstrate troubleshooting techniques.

Intended for use with a [companion guide](http://imagej.net/Debugging_Exercises).

## Source code structure

Note that the source code is split into two packages:

* `visible` - Source code for use and inspection in troubleshooting exercises. These are the classes intended for inspection and setting breakpoints.
* `hidden` - A simulated "black box" of utility methods. These classes are not intended for inspection.

Troubleshooting is the art of determining the cause and/or location of a problem. If you have complete, perfect knowledge of the code then there isn't really a need for troubleshooting, as it is trivial to see why something is behaving incorrectly.

Because this project is intended to help new developers practice troubleshooting skills, it uses contrived examples, limited in complexity. Inspection of the `hidden` package will typically allow you to easily "troubleshoot" an exercise without using the intended technique.

Remember the goal of these exercises is **not** to solve the problems, but to learn how and when to use the myriad of troubleshooting techniques available. Given the inherent complexity that comes with a combined work, all of these techniques have their time and place when working on a rich application like ImageJ.
