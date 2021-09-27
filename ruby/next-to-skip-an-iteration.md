# Next to skip an iteration

The next keyword is a keyword available in enumeration. It will halt the iteration and move onto the next value, ignoring further evaluation in the current scope. Not always necessary, but can be used for syntactic sugar.

**example -** 

_Skips current iteration._
```
  arr = [1,2,3,4,5,6,7,8,9,10]

  arr.each do |v|
    next if v.odd?
    p v
  end
=> 
2
4
6
8
10
```