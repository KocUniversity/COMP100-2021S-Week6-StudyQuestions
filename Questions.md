1. Write a function which takes two dictionaries as parameters and returns the **combined** dictionary.

> {'a': 100, 'b': 200, 'c': 300} + {'d': 300, 'f': 200} -> {'a': 100, 'b': 200, 'c': 300, 'd': 300, 'f':200}

2. Write a function which takes two dictionaries as parameters and returns the summation of the dictionaries. The summation can be defined as element-wise sum for each element. You can assume the keys that do not appear in the dictionaries have a value of 0.

> {'a': 100, 'b': 200, 'c': 300} + {'a': 300, 'b': 200, 'd': 400} -> {'a': 400, 'b': 400, 'c': 300, 'd': 400}

3. Write a function which takes a dictionary as parameters and a key as parameters and returns the dictionary with deleting the given key. That is, if the given key appears in the dictionary, it needs to be deleted.

> {'a': 100, 'b': 200, 'c': 300}, 'a' -> { 'b': 200, 'c': 300}

4. Write a function which takes two dictionaries as parameters and return a list which contains the common keys between the two. That is, if a key appears in both dictionaries, it needs to be in the output list.

> {'a': 100, 'b': 200, 'c': 300}, {'a': 300, 'b': 200, 'd': 400} -> ['a','b']

5. Write a function which takes a dictionary as a parameter and returns the multiplication of all the values in the dictionary. 

> {'a': 2, 'b': 5, 'c': 4, 'd':3} -> 120

6. Write a recursive function to calculate *the harmonic sum* of n. 

**Note**: *The harmonic sum* of n is the sum of reciprocals of all the positive integers up to n. 

> 1 + 1/2 + 1/3 + ... + 1/n


7. Write a function to reverse the string in a recursive way. Your implementation should be recursive and you should not use any loops.

> "abc" -> "cba"

8. Write a function which checks whether the given integer is prime or not in a recursive way. Your implementation should be recursive and you should not use any loops. 

**Hint:** You need to check if the given integer is divisible by all the number up until the square root of the given integer. 

For example, for 13, it is enough to check if numbers, 2, 3, 4 do not divide 13, we can say that is a prime number.


9. Write a recursive function that returns the maximum element of a given list. Your implementation should be recursive and you should not use any loops.


10. Find the sum of elements in a given nested list where the element of each list can be another list. Note that there might be more than two levels in the nesting of the lists. 

Some example cases:

> [1,2,[3,4],5] -> 15
> [1,[2,3],[[4,5],6]] -> 21
> [[1,[2,[3,[4,[5,[6,[7,[8,[9,[10]]]]]]]]]]] -> 55

