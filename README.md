# Coding-question-infosys-aug-22

## Question 1.

Few people are traveling from place `A` to place `B` using a bicycle.
### Conditions:
1. There is only one bicycle .
2. Two people can travel at most.
3. At least one person is required to ride the bicycle.
4. If a single person is riding, the time to complete the ride is the same as the time taken by that individual.
5. If two people are riding, the time to complete the ride is the same as the time taken by the person who needs more time. <br>
( if `x` requires `5 min` and `y` requires `10 min`, then the time needed for their travel is `10 min`.)

The task is to find the minimum time taken to complete the journey.

### Input: 
  * `n` - The number of people.
  * `A` - an array of size `n` that indicates the time taken by each individual.

### Output:
It should be an integer that gives the minimum time for the journey.

### Sample Input and Output:

```n = 3
A = [10,15,3]
Answer - 28 
```
#### Explanation:
While starting, three people are at place `A`. 
1. People with times `10` and `3` travel to place `B`. `Time - 10`.
2. `3` ride the bicycle back to `A`. `Time - 3`. 
3. Then both `3` and `15` move to `B`. `Time - 15`.
`Total time - 10 + 3 + 15 = 28`.

### Constraints:
* `1 <= n <= 10e5`
* `1 <= A[i] <=10e9`


