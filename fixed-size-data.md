For each row of shapes in the image below, go through the following steps:

1. In a code comment, describe the family of shapes.
2.Describe what variables you will need in the data type, and the meaning of each
3. Write a class  with the necessary variables.  Make all varables `final`.
4. Write a constructor for the data type.
5. Write a function that draws a value of your data type.

For example, for the first row, I would write for each step:

1. Circles of various sizes
2. The radius of the circle
3. ```
class Circle {
    final float r;
}```
4. ```
Circle(float r_) {
   r = r_;
   }```
5. ```
   drawCircle(Circle c) {
   ellipse(0,0,c.r,c.r);
}```

![](images/fixed-size-data.png)
