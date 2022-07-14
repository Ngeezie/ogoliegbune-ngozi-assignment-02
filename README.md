## AltSchool Assignment

Complete any two out of the three challenges. See below for details of each challenge.

### Javascript Fluency Assignment

// *//Challenge - 1
// *
// * Calculate and return the sum of numbers in an array.
// * If you did challenge - 1, remove the comment in the line just after this function *//

  // @param {Array} arrayOfNumbers the array of numbers to sum
  // @returns number the sum of numbers
 // solution of challenge 1
function sumOfNumbers(arrayOfNumbers) {
 count sum = arrayOfNumbers.reduce ((a,b) => a+b);
return sum
}
assignment.sumOfNumbers = sumOfNumbers


/**
 * Challenge - 2
 *
 * Count all even numbers within an array of numbers.
 * If you did Challenge - 2, remove the comment in the line just after the function
 *
 * @oparam {Array} arraysOfNumbers the array containing even and non even numbers
 * @return number the count of even numbers
 */


 function countEvenNunmbers(arrauOfNumbers) {
      lets count = 0;
   for (let i = 1; i < arrayOfNumbers.length; i++) {
     if(arrayOfNumbers[i]) % 2 === 0){ 
      count++
    }
 }
   return count
 }
 assignment.countEvenNumbers = countEvenNumbers;
   

#### Challenge - 3
> In `src/assignment.mjs`, implement the `celsiusToFahrenheit` function. Convert the array of numbers representing temperatures in Celsius, to an array of temperatures in Fahrenheit. Decimal figures in the converted values in Fahrenheit should be removed. E.g 51.21 should just be 51 (hint: Math.trunc(...) function) 
 See https://www.thoughtco.com/celcius-to-farenheit-formula-609227 for the conversion formula. If you did Challenge - 3, remove the comment in the line just after the `celsiusToFahrenheit` function, otherwise leave the comment.


