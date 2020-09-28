# Blackout math puzzle

## Calculate area of circle

Write a program to approximate the area under a
circle with radius r. Note that you should forget the existence of the well
known formula area = πr2.

![Alt text](https://github.com/lavivien-ds-algo/CalculateAreaOfCircleNotUsePi/blob/master/circle_area.jpg?raw=true "Title")

Method: The equation of a circles with radius r, centered at origin is x2 + y2 = r2.
Divide the area under the first quadrant in to small rectangles of width of your choice
(dx) { smaller the better { and add these areas of all these rectangles to approximate the
area of one quarter of the circle. You should pass radius (r) and the width of the above
small rectangles (dx) as parameters. Instead of the width of those small rectangles, you
can pass the number of rectangles you want { say, n { (I think this is easier and makes
more sense as dx = r=n). Once you have the area of one quadrant, multiply that value
by 4 to get the area of the circle. Your method should return that value. In other words,
your method takes two input and return the area.

You must test your results with known radius values (Say, if you set your radius to 1.
Then you should see the π as the answer for the area).

You don't need any Calculus knowledge to solve this problem.

## Calculate area of ellipse

Write a program to approximate the area under an
ellipse centered at origin. Assume major axis and minor axis lengths are 2a
and 2b respectively. Note that you should forget the existence of the well
known formula area = πab.

![Alt text](https://github.com/lavivien-ds-algo/CalculateAreaOfCircleNotUsePi/blob/master/ellipse_area.jpg?raw=true "Title")

Method: The equation of such an ellipse centered at origin is as follows.

![Alt text](https://github.com/lavivien-ds-algo/CalculateAreaOfCircleNotUsePi/blob/master/ellipse_formula.jpg?raw=true "Title")

Divide the area under the first quadrant in to small rectangles of your
choice – smaller the better and you should pass this as a parameter to your
method (or you can pass number of small rectangles, and then calculate the
width of the rectangle inside the method), in addition to a and b– and add
these areas of all these rectangles to approximate the area of one quarter of
the ellipse. Multiplying that value by four give the approximate area of the
ellipse. You must test your results with known a and b values (especially,
test with a = 1 and b = 1 and you should see  as the area).
Note: Your method should take a, b, and number of small rectangles (or
width of small rectangles) as parameters and returns the area of the ellipse.
You don’t need any Calculus knowledge to solve this problem.






