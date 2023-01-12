# JS-string-array

## JavaScript Theory -
## Content -
## 1-String
## 2-Array

## JavaScript Strings -

JavaScript strings are for storing and manipulating text.<br>
A JavaScript string is zero or more characters written inside quotes.

## Escape Character-
## I-
let text = 'It\'s alright.';
console.log(text);
<details><summary><b>Answer</b></summary>
It's alright.
</details>

## II-
let text = "We are the so-called \"Vikings\" from the north.";
console.log(text);
<details><summary><b>Answer</b></summary>
We are the so-called "Vikings" from the north.
</details>

## III-
let text = "The character \\ is called backslash.";
console.log(text);
<details><summary><b>Answer</b></summary>
The character \ is called backslash.
</details>

## JavaScript Strings as Objects -
## I
let x = "John";
let y = new String("John");
console.log(typeof x + "<br>" + typeof y);
<details><summary><b>Answer</b></summary>
string
object
</details>

## II
let x = "John";
let y = new String("John");
console.log(x==y)
<details><summary><b>Answer</b></summary>
true
</details>

## III
let x = "John";
let y = new String("John");
console.log(x===y)
<details><summary><b>Answer</b></summary>
false
</details>

## JavaScript objects cannot be compared-

## I
let x = new String("John");  
let y = new String("John");  
console.log(x==y);
<details><summary><b>Answer</b></summary>
false
</details>

## II
let x = new String("John");  
let y = new String("John");  
console.log(x===y);
<details><summary><b>Answer</b></summary>
false
</details>

## JavaScript String Methods -

![image](https://user-images.githubusercontent.com/96730792/211377878-7257bae5-b188-4129-a4f7-c010c997d110.png)

## Extracting String Parts-
![image](https://user-images.githubusercontent.com/96730792/211378010-7bf24817-213e-4324-bba7-e45ec8d245fd.png)

## String slice()-

## I-
let text = "Apple, Banana, Kiwi";
let part = text.slice(7)
console.log(part);
<details><summary><b>Answer</b></summary>
Banana, Kiwi
</details>

## II-
let text = "Apple, Banana, Kiwi";
let part = text.slice(-12,-6)
console.log(part);
<details><summary><b>Answer</b></summary>
Banana
</details>

## III-
let text = "Apple, Banana, Kiwi";
let part = text.slice(7,13);
console.log(part);
<details><summary><b>Answer</b></summary>
Banana
</details>

## substring() 
substring() is similar to slice().
## I-
let str = "Apple, Banana, Kiwi";
let part = str.substring(7, 13);
console.log(part)
<details><summary><b>Answer</b></summary>
Banana
</details>

## II-
let str = "Apple, Banana, Kiwi";
console.log(str.substr(-4));
<details><summary><b>Answer</b></summary>
Kiwi
</details>

## Replacing String Content-
 let text = "Please visit Microsoft";
 let newText = text.replace("Microsoft","W3Schools");
document.write(newText);
<details><summary><b>Answer</b></summary>
Please visit W3Schools
</details>

## String ReplaceAll()-
let text = "I love cats. Cats are very easy to love. Cats are very popular."
text = text.replaceAll("Cats","Dogs");
text = text.replaceAll("cats","dogs");
console.log(text);
<details><summary><b>Answer</b></summary>
I love dogs. Dogs are very easy to love. Dogs are very popular.
</details>

## Converting to Upper and Lower Case-











*********************************************************** Array **********************************************************************
 ## Array-
 
 An array is a special variable, which can hold more than one value.<br>
  Array indexes start with 0. is the first element. 1 is the second element.<br>
  Arrays are a special type of objects. The typeof operator in JavaScript returns "object" for arrays.


## Arrays are Objects-
![image](https://user-images.githubusercontent.com/96730792/211619772-cddd18ee-cfe4-4c1e-87b5-8865675b88ae.png)

## Accessing the Last Array Element-
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let fruit = fruits[fruits.length - 1];
console.log(fruit);
<details><summary><b>Answer</b></summary>
mango
</details>

## Adding Array Elements-
const fruits = ["Banana", "Orange", "Apple"];
const newFruit = fruits.push("Lemon"); 
console.log(fruits)


## Difference Between Arrays and Objects-
JavaScript, arrays use numbered indexes.<br> objects use named indexes.
