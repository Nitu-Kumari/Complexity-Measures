#Complexity
~~~
‘Complexity’ is an approximate measure of the efficiency of an algorithm.
2 kinds of complexities: 
1.TIME
2.Space
~~~

#Time complexity
~~~

Time complexity is an algorithm’s rate of growth of time taken with respect to the input. 
time complexity is an approximation of how much time it takes for a particular algorithm to execute as the input data grows in size.
~~~
#How to calculate time complexity?
~~~
suppose that our algorithm is running on a machine that

. single processor
 .32-bit architecture
Executes code sequentially, so does no parallel processing
Takes one ‘unit’ or ‘constant’ amount of time for basic operations.

time complexity
function addOne(x){
    x+= 7  ;
    return x;
}
console.log(7);
//
that means
Operation	Number of executions
x+=1	         1
return x	     1

time  Complexity= 1 + 1 ⇒2

~~~
# Measuring Time Complexity
~~~
 the steps to calculate the running time complexity we will split the code into individual operations and then compute how many times it is being executed.
 
            Operation                      Number of executions
           sum = 0	                                  1
            i++	                                       n  
            i=0	                                        1
           i=1                                        	 1
          i=2	                                          1
         i=n	                                           1
        sum+=1	                                           n
     console.log( sum)	                                    1



Time Complexity = 1 + n + (1 + 1 + 1 + ...+ 1) + n + 1⇒= 1 + n + n + n + 1⇒3n+2


