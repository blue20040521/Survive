## This is my answers to the problems in the Matlab Cody ##
### Quesrion 1 (230518) ###
Given the variable x as your input, multiply it by two and put the result in y.
```matlab 
function y = times2(x)
  y = x*2;
end
```
### Quesrion 2 (230518) ###
In MATLAB, you create a vector by enclosing the elements in square brackets like so:
<br>x = [1 2 3 4]
<br>Commas are optional, so you can also type
<br>x = [1, 2, 3, 4]
<br>Create the vector
<br>x = [1 2 3 4 5 6 7 8 9 10]
<br>There's a faster way to do it using MATLAB's colon notation.
```matlab 
function x = oneToTen
  x = [1:10]
end
```
