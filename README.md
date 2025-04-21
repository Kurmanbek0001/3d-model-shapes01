 shapes.py — Abstract Base Class and Subclasses
Shape3D is an abstract base class (ABC) using abc module.

It contains two abstract methods:

surface_area()

volume()

The three concrete subclasses Sphere, Cylinder, and Cube implement these methods with their own formulas.

main.py — Shape Generation and Output
Randomly creates 10 shape objects (Sphere, Cylinder, Cube).

Uses Python’s random module to:

Pick random dimensions (radius, height, side).

Randomly choose shape types.

Prints:

Shape type

Surface area (rounded to 2 decimal places)

Volume (rounded to 2 decimal places)

