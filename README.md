# Basic-JavaScript-Nesting-For-Loops
Modify function multiplyAll so that it returns the product of all the numbers in the sub-arrays of arr.

[1,2],[3,4],[5,6,7]
OUTER LOOP

Initialize: var i=0
Test: i < arr.length; Is i=0 less than array.length(3). If YES or TRUE enter inner loop
INNER LOOP

Initialize: var j=0
Test: j < arr[i].length;
->i was initialized to 0.
->array[i].length is same as array[0].length i.e length of [1,2] which is 2).
->Is j=0 less than array[i].length? YES, execute code inside j loop
product= product(=1) * arr[i][j](value in position [0][0] (=1))
product= 1
Increment: j++ (j=1)
Test: j < arr[i].length;
->i is still initialized to 0.
->array[i].length is same as array[0].length i.e length of [1,2] which is 2).
->Is j=1 less than array[i].length? YES, execute code inside j loop
product= product(=1) * arr[i][j](value in position [0][1] (=2))
product=2
Increment: j++ (j=2)
Test: j < arr[i].length;
->i is still initialized to 0.
->array[i].length is same as array[0].length i.e length of [1,2] which is 2).
->Is j=2 less than array[i].length? NO, go to outer loop.
Increment: i++ (i=1).
Repeat process from Outer Loop with i=1. Then…
product= product(=2) * arr[i][j](value in position [1][0] (=3))
product=6
and so on…hope this helps
