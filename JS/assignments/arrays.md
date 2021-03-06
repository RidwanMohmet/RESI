# JS - Array Exercises

### Exercise: Level 1

1. Declare an _empty_ array;
2. Declare an array with more than 5 number of elements
3. Find the length of your array
4. Get the first item, the middle item and the last item of the array
5. Declare an array called _mixedDataTypes_, put different data types in the array and find the length of the array. The array size should be greater than 5
6. Declare an array variable name techCompanies and assign initial values Facebook, Google, Microsoft, Apple, IBM, Oracle and Amazon
7. Print the array using _console.log()_
8. Print the number of companies in the array
9. Print the first company, middle and last company
10. Print out each company using `forEach` method
11. Change each company name to uppercase one by one and print them out
12. Print the array like as a sentence: Facebook, Google, Microsoft, Apple, IBM,Oracle and Amazon are big IT companies.
13. Check if 'Apple' company exists in the techCompanies array. If it exist return the company else return a company is _not found_
14. Filter out companies which have more than one 'o' without the filter method
15. Sort the array using _sort()_ method
16. Reverse the array using _reverse()_ method
17. Slice out the first 3 companies from the array
18. Slice out the last 3 companies from the array
19. Slice out the middle Tech company or companies from the array
20. Remove the first IT company from the array
21. Remove the middle IT company or companies from the array
22. Remove the last IT company from the array
23. Remove all IT companies

### Exercise: Level 2

```js
const countries = [
  "Somaliland",
  "Somalia",
  "Jabouti",
  "Ethiopia",
  "Kenya",
  "Denmark",
  "Finland",
  "Germany",
  "Ireland",
  "Japan",
];

const webTechs = [
  "HTML",
  "CSS",
  "JavaScript",
  "React",
  "Redux",
  "Node",
  "MongoDB",
];
```

1. Create a separate countries.js file and store the countries array in to above, create a separate file web_techs.js and store the webTechs array above. Access both file in main.js file
1. First remove all the punctuations and change the string to array and count the number of words in the array

   ```js
   let text =
     "I love coding and challenges. I Learn HTML, CSS, JS, React, Python.";
   console.log(words);
   console.log(words.length);
   ```

   ```sh
   ["I", "love", "coding", "and", "challenges",  "I", "Learn", "HTML", "CSS", "JS", "React", "Python"]

   13
   ```

1. In the following shopping cart add, remove, edit items

   ```js
   const shoppingCart = ["Milk", "Coffee", "Tea", "Honey"];
   ```

   - add 'Meat' in the beginning of your shopping cart if it has not been already added
   - add Sugar at the end of you shopping cart if it has not been already added
   - remove 'Honey' if you are allergic to honey
   - modify Tea to 'Green Tea'

1. In countries array check if 'Ethiopia' exists in the array if it exists print 'ETHIOPIA'. If it does not exist add to the countries list.
1. In the webTechs array check if Sass exists in the array and if it exists print 'Sass is a CSS preprocessor'. If it does not exist add Sass to the array and print the array.
1. Concatenate the following two Arrays and store it in a fullStack variable.

   ```js
   const frontEnd = ["HTML", "CSS", "JS", "React", "Redux"];
   const backEnd = ["Node", "Express", "MongoDB"];

   console.log(fullStack);
   ```

   ```sh
   ["HTML", "CSS", "JS", "React", "Redux", "Node", "Express", "MongoDB"]
   ```

### Exercise: Level 3

1. The following is an array of 10 students ages:

   ```js
   const ages = [19, 22, 17, 15, 24, 20, 25, 26, 14, 17, 24, 25, 24];
   ```

   - Sort the array and find the min and max age
   - filter ages, find ages above 18
   - Find the average age(all items divided by number of items)
   - remove duplicate values

🎉 CONGRATULATIONS - you mastered JS Arrays! 🎉
