# js-for-react-native-11212478

This repository contains JavaScript functions designed for processing arrays, which can be utilized in React Native projects.

## Functions

### `processArray(numbersArray)`

This function takes an array of numbers and processes each element based on whether it is even or odd. 

- Even numbers are squared.
- Odd numbers are tripled.

#### Parameters:
- `numbersArray` (Array of Numbers): An array of numbers to be processed.

#### Returns:
- Array: A new array where each element has been processed (squared if even, tripled if odd).

#### Example:
```javascript

const numbers = [1, 2, 3, 4];
const processedNumbers = processArray(numbers);
console.log(processedNumbers); // Output: [3, 4, 9, 16]

formatArrayStrings(stringsArray, numbersArray)
This function takes two arrays, one of strings and one of numbers, and processes each string based on the corresponding number:

If the number is even, the string is converted to uppercase.
If the number is odd, the string is converted to lowercase.
Parameters:
stringsArray (Array of Strings): An array of strings to be formatted.
numbersArray (Array of Numbers): An array of numbers used to determine how to format the corresponding string.
Returns:
Array: A new array of formatted strings based on the corresponding numbers.
Throws:
Error: If the lengths of stringsArray and numbersArray do not match.
