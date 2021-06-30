# day 006

## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

1. a function declaration which is the first form we learned. this one has a name declaration attached to the function and can be invoked outside of the function using functionName()

2. function expressions are anonymous and can be attached to a variable. example 
let name = fucntion(parameters){
    //code here//
}

3. and finally the '=>' can be used as a function usualy preceeded by a '.find' or some other method.

## What is the difference between Parameters and Arguments?

parameters are used when naming the values that will eventually be passed through the function and an arguement is that type of data that will actually pass through our function when invoked.

## What are higher order functions? Can you provide an example?

a higher order function is when we call another function inside the parameters of a function. therefore we have a function inside of another function. 

an example would be 'arr.protoType.map'