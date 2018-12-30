# Algorithms and Data Structures

* Solve coding problems
* Different version of codes
* Visualize to expalain solution

## Example #1: FizzBuzz

Write a program that prints numbers from 1 to 100. But for multiples of three, print "Fizz" instead of the number, and for the mulitples of five, print "Buzz". For numbers which are mulitiples of both three and five, print "FizzBuzz"

* Requires you to print out all the numbers between 1 and 100
* If a printed number is divisible by 3, print "Fizz"
* If a printed number is divisible by 5, print "Buzz"
* If a printed number is divisible by 3 & 5, print "FizzBuzz"

Note: This is an extremely commonly used question, and considered the easiest. However, some still fail :( It's "supposed" to be an easy question. There's a trick to it, we'll see later.

## Example #2: Fibonacci Series

A series of numbers in which each number (Fibonacci number) is the sum of the two preceding numbers. The simplest is the series 1, 1, 2, 3, 5, 8, etc.

* You're supposed to print out a specific number from the Fibonacci Series
* Most time, will be asked to solve the problem with a **Recursive Solution**

**Recursive Solution**
```
function fib(n) {
  if (n < 2) {
    return n;
  }
  return fib(n - 1) + fib(n - 2);
}
```

Note: This question has been asked a lot as well. 
# Order of Exercises

* [ReverseString](https://repl.it/@aeimskei/algo-ds-js-reversestring)
* [Palindrome](https://repl.it/@aeimskei/algo-ds-js-palindrome)
* [ReverseInt](https://repl.it/@aeimskei/algo-ds-js-reverseint)
* [MaxChar](https://repl.it/@aeimskei/algo-ds-js-maxchar)
* [FizzBuzz](https://repl.it/@aeimskei/algo-ds-js-fizzbuzz)
* [ArrayChunk](https://repl.it/@aeimskei/algo-ds-js-arraychunk)
* [Anagrams](https://repl.it/@aeimskei/algo-ds-js-anagrams)
* [Capitalize](https://repl.it/@aeimskei/algo-ds-js-capitalize)
* [PrintSteps](https://repl.it/@aeimskei/algo-ds-js-printsteps)