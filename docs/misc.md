# Module: Miscellaneous Functions
This module contains all miscellaneous functions that cannot otherwise fit under one roof/category with other related functions.

## Slope function
![](https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/slope.gif)
```
slope(y2, y1, x2, x1);
```
- Parameters:
    - `y2` - The y2 value of the slope formula
    - `y1` - The y1 value of the slope formula
    - `x2` - The x2 value of the slope formula
    - `x1` - The x1 value of the slope formula
    
## Distance Formula (On a Plane)
![][distplane]
```
dist_on_plane(y2, y1, x2, x1);
```
- Parameters:
    - `y2` - The y2 value of the distance formula
    - `y1` - The y1 value of the distance formula
    - `x2` - The x2 value of the distance formula
    - `x1` - The x1 value of the distance formula

## Midpoint on a Plane
![][midplane]
```
mid_on_plane(y2, y1, x2, x1);
```
- Parameters:
    - `y2` - The y2 value of the midpoint formula
    - `y1` - The y1 value of the midpoint formula
    - `x2` - The x2 value of the midpoint formula
    - `x1` - The x1 value of the midpoint formula

## Pythagorean Theorum
![][pythm]
```
py_thm(a, b, c);
```
- Parameters:
    - `a` - The a value of the Pythagorean Theorum
    - `b` - The b value of the Pythagorean Theorum
    - `c` - The c value of the Pythagorean Theorum
    
## Perimeter of a Rectangle
![][perirect]

![][perirect2]
```
p_of_rect(l, w);
```
This function defaults to the first formula specified.

- Parameters:
    - `l` - The length value of a rectangle
    - `w` - The width value of a rectangle
    
## Quadratic Formula
![][quadform]
```
quad_formula(a, b, c);
```
- Parameters:
    - `a` - The a value of the Quadratic Formula
    - `b` - The b value of the Quadratic Formula
    - `c` - The c value of the Quadratic Formula
    
## Circumference of a Circle
![][circum]
```
circum_of_circle(d);
```
- Parameters:
    - `d` - The diameter of a circle
    
[slope]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/slope.gif
[distplane]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/distance_plane.gif
[midplane]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/mid_on_plane.gif
[pythm]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/py_thm.gif
[perirect]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/p_of_rect.gif
[perirect2]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/p_of_rect_2.gif
[quadform]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/quad_formula.gif
[circum]: https://github.com/ChristoffenOSWorks/libalgebra-rs/blob/master/docs/images/circum_of_circ_1.gif
