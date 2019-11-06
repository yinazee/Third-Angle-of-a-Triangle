# Third-Angle-of-a-Triangle
Coding Challenge

You are given two angles (in degrees) of a triangle.

Write a function to return the 3rd.

Note: only positive integers will be tested.

Better Solution:

function otherAngle(a, b) {
  return 180-(a+b);
}

My Solution:

function otherAngle(a, b) {
  
  let c = 180 - (a + b)
  return c;
}

otherAngle()
