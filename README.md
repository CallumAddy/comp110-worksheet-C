# comp110-worksheet-C
Base repository for COMP110 worksheet C

a) State what task this algorithm performs.
This algorithm scans the list to see if it finds any duplicate items.

b) Explain why the worst case running time of the algorithm is quadratic, i.e.
O(n^2).
it's n to the power of 2 because it has to loop through i and then loop through again for j

Now suppose that the for loop on line 4 is changed so that j ranges from 0 to
i − 1.

c) Explain why the algorithm is still correct.

this is still correct because list[i] will be tested against elements up from i-1 and the elements after this are tested because i is increased.

d) Explain why the algorithm will run approximately twice as fast.

it only checks itself against another element once, and it won't ever check against itself therefore the program will run twice as fast as before.

e) Is the time complexity of the algorithm still quadratic? Explain your answer.

yes because it's still looping to the power of 2 because it loops through i and it loops through j

f) 
https://wiki.python.org/moin/TimeComplexity
"Sort:

O(n log n)"

g)

h)
the second algorith would be faster this is because it tests itself against the elements only once and never tests against itself
i)
I would use the slower algorith because it would be easier to maintain because it's slower and i can manage the properties easier.
1) procedure HASDUPLICATE(list)

a) This line starts the function called "HasDuplicate(list)" and adds the variable list in the parameters

2) let n be the length of list

a) This makes "n" the length of the list that will be assigned.

3) for i = 0, 1, . . . , n − 1 do

a) this sets a loop for when i equals 0 up to the value of n - 1, and it'll do something until it reaches that value

4) for j = 0, 1, . . . , n − 1 do

a) this sets a loop for when j equals 0 up to the value of n - 1, and it'll do something until it reaches that value

5) if i (does not equals sign) j and list[i] = list[j] then

a) if i does not equals j and the list i is the same as list j then it'll continue with the program

6) return true

a) this will return true if the if statement is true

7) end if

a) this ends the if statement

8) end for

a) this ends the first for loop

9) end for

a) this ends the second for loop

10) return false

a) if the if statement isn't true it'll return false by default

11) end procedure

a) this ends the function

