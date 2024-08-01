# README

This README file contains JavaScript code snippets for various functions. Each function is described below along with an example usage.

## isAnagram
The `isAnagram` function takes two parameters, `str1` and `str2`, and returns `true` if they are anagrams, and `false` otherwise. An anagram is a word or phrase formed by rearranging the letters of another word or phrase.

Example usage:
```javascript
console.log(isAnagram("Listen", "Silent")); // true
console.log(isAnagram("Hello", "World")); // false
```

## calculateTotalSpentByCategory
The `calculateTotalSpentByCategory` function takes a list of transactions as a parameter and returns a list of objects where each object represents a unique category and has the total price spent in that category as its value.

Example usage:
```javascript
const transactions = [
    { category: "Food", price: 10.5 },
    { category: "Transport", price: 25.0 },
    { category: "Food", price: 5.25 },
    { category: "Utilities", price: 100.0 },
    { category: "Transport", price: 7.5 },
];

console.log(calculateTotalSpentByCategory(transactions));
```

## findLargestElement
The `findLargestElement` function takes an array of numbers as a parameter and returns the largest element in the array.

Example usage:
```javascript
const array = [1, 5, 3, 9, 2];
console.log(findLargestElement(array)); // Output: 9
```

## isPalindrome
The `isPalindrome` function takes a string as a parameter and returns `true` if it is a palindrome, and `false` otherwise. A palindrome is a word, phrase, number, or other sequence of characters that reads the same forward and backward.

Example usage:
```javascript
console.log(isPalindrome("A man, a plan, a canal, Panama")); // true
console.log(isPalindrome("Hello, World!")); // false
```

## calculateTime
The `calculateTime` function takes a number `n` as a parameter and calculates the time it takes for JavaScript code to calculate the sum from 1 to `n`. The time is returned in seconds.

Example usage:
```javascript
const n = 1000000;
console.log(`Time taken: ${calculateTime(n)} seconds`);
```

## countVowels
The `countVowels` function takes a string as a parameter and returns the number of vowels in the string.

Example usage:
```javascript
console.log(countVowels("Hello World")); // Output: 3
console.log(countVowels("JavaScript is awesome")); // Output: 8
console.log(countVowels("123456")); // Output: 0
```

## sumArray
The `sumArray` function takes an array of numbers as a parameter and returns the sum of all the numbers.

Example usage:
```javascript
console.log(sumArray([1, 2, 3, 4])); // Output: 10
console.log(sumArray([10, -2, 3.5, 0])); // Output: 11.5
console.log(sumArray([])); // Output: 0
```

## filterEvenNumbers
The `filterEvenNumbers` function takes an array of numbers as a parameter and returns a new array containing only the even numbers.

Example usage:
```javascript
console.log(filterEvenNumbers([1, 2, 3, 4, 5, 6])); // Output: [2, 4, 6]
console.log(filterEvenNumbers([10, 21, 32, 43, 54])); // Output: [10, 32, 54]
console.log(filterEvenNumbers([7, 13, 21])); // Output: []
```

## findSmallestElement
The `findSmallestElement` function takes an array of numbers as a parameter and returns the smallest element in the array.

Example usage:
```javascript
console.log(findSmallestElement([5, 3, 9, 1, 6])); // Output: 1
console.log(findSmallestElement([-2, -5, 0, 4])); // Output: -5
console.log(findSmallestElement([7])); // Output: 7
```

## reverseString
The `reverseString` function takes a string as a parameter and returns the string reversed.

Example usage:
```javascript
console.log(reverseString("hello")); // Output: "olleh"
```

## fibonacci
The `fibonacci` function takes a number `n` as a parameter and prints the `n`th number in the Fibonacci sequence.

Example usage:
```javascript
const number = 5;
let n1 = 0,
    n2 = 1,
    nextTerm;

console.log("Fibonacci Series:");

for (let i = 1; i <= number; i++) {
    console.log(n1);
    nextTerm = n1 + n2;
    n1 = n2;
    n2 = nextTerm;
}
```

## removeDuplicates
The `removeDuplicates` function takes an array as a parameter and returns a new array with duplicate values removed.

Example usage:
```javascript
console.log(removeDuplicates([1, 2, 2, 3, 4, 4, 5])); // Output: [1, 2, 3, 4, 5]
console.log(removeDuplicates(["a", "b", "a", "c"])); // Output: ['a', 'b', 'c']
```

## countOccurrences
The `countOccurrences` function takes a string and a character as parameters and returns the number of times the character appears in the string.

Example usage:
```javascript
const string = "Hellooo";
const letterToCheck = "o";

const result = countOccurrences(string, letterToCheck);
console.log(result);
```

## findCommonElements
The `findCommonElements` function takes two arrays as parameters and returns a new array containing the elements that are present in both arrays.

Example usage:
```javascript
console.log(findCommonElements([1, 2, 3, 4], [3, 4, 5, 6])); // Output: [3, 4]
console.log(findCommonElements(["a", "b", "c"], ["b", "c", "d"])); // Output: ['b', 'c']
console.log(findCommonElements([1, 2, 3], [4, 5, 6])); // Output: []
```

## sortStrings
The `sortStrings` function takes an array of strings as a parameter and returns the array sorted in alphabetical order.

Example usage:
```javascript
console.log(sortStrings(["banana", "apple", "cherry"])); // Output: ["apple", "banana", "cherry"]
console.log(sortStrings(["zebra", "elephant", "dog", "cat"])); // Output: ["cat", "dog", "elephant", "zebra"]
console.log(sortStrings(["grape", "apple", "mango", "banana"])); // Output: ["apple", "banana", "grape", "mango"]
```
