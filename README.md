# ESUG-2022-TTQs
Time-Traveling Queries demostration ESUG 2022

## Video Demo

[View Video](https://drive.google.com/file/d/12MlQZO9X1WN7e1LUqm5p0E-x8VJXQz0h/view?usp=sharing)

[Video - Slower silent demo with captions](https://drive.google.com/file/d/1vc97XggNn43VJl8Afs8W97QLJ0OgRYud/view?usp=sharing)

[Video Original Speed with Captions](https://drive.google.com/file/d/1LlNiDW1qqXTD-asBLoMGnfSSJXO7nTDg/view?usp=sharing)

## Reference publication

* [Time-Traveling Debugging Queries: Faster Program Exploration @ IEEE](https://ieeexplore.ieee.org/document/9724738)  
* [Pre-print version](https://hal.inria.fr/hal-03463047/)

## Time-Traveling Debugger Code - Baseline

Seeker: Prototype Scriptable Time-Traveling Queryable Debugger.
Compatible with Pharo10, Pharo 9.0, Moose Suite 9.0 at current date (2022-07-13).

Do this:
```Smalltalk
Metacello new
    baseline: 'Seeker';
    repository: 'github://maxwills/SeekerDebugger:main';
    load.
```

### Main project repository

More information in the debugger project dedicated repository:

https://github.com/maxwills/SeekerDebugger
