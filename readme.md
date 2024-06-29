<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  <h1>JavaScript Questions</h1>
</div>

> [!NOTE]  
> my repo is created with easy basic Js questions for beginners to understnad wht they're learning

---

<p align="center">feel free to reach out to me 😊</p>

<p align="center">
  <a href="#">Instagram</a> || <a href="#">Twitter</a> || <a href="#">LinkedIn</a> || <a href="#">Blog</a>
</p>

</p>
</details>

#### Question 1

Q: What is the correct syntax to print "Hello, World!" in JavaScript?

<details><summary><b>Answer</b></summary>

```js
console.log("Hello, World!");
```

</details>

#### Question 2

Q: How do you create a variable in JavaScript?

<details><summary><b>Answer</b></summary>

```js
let yourVariableName //  its called camlecase formate
var yourVariableName
const yourVariableName
```

> var, let, and const are all used for declaring variables in JavaScript, but they have different scoping, hoisting, and reassignment behaviors. in the modern days var is not recomanded.

</details>

#### Question 3

Q: How do you create a function in JavaScript?

<details><summary><b>Answer<br></summary>

```js
function functioName() {
  //u can use name as it function name
  // your code excute here
}
```

![alt text](image.png)

</details>

#### Question 4

Q: How do you call a function in JavaScript?

<details><summary><b>Answer<br></summary>

```js
function yourFunction() {
  // your code excute here
}
yourFunction();
```

![alt text](image-1.png)

</details>

#### Question 5

Q: How do you write an if statement in JavaScript to check if "a" variable "a" is equal to 5?

<details><summary><b>Answer<br></summary>

```js
if (a === 5)
```

</details>

#### Quesiont 6

Q: wht is === mean in js

<details><summary><b>Answer<br></summary>

<p > in JavaScript, the === operator is known as the strict equality operator. It compares two values for equality, considering both the value and the type. This means that === will only return true if the values on both sides of the operator are exactly same in both type and value </p>

</details>

#### Question 6

Q: how do you write a loop that runs 5 times in ?

<details><summary><b>Answer<br></summary>

```js
for (let number = 1; number <= 5; number++) {
  console.log(number);
}
```

![alt text](image-2.png)

</details>

#### Question 7

Q: Write a while loop that prints the numbers from 1 to 5.

<details><summary><b>Answer<br></summary>

```js
let value = 1;
while (value < 5) {
  console.log(value);
  value++;
}
```

![alt text](image-3.png)

</details>

#### Question 8

Q: Write a do...while loop that prints the numbers from 1 to 5.

<details><summary><b>Answer<br></summary>

```js
let value = 1;
do {
  console.log(value);
  value++;
} while (value < 5);
```

![alt text](image-4.png)

</details>

#### Question 7

Q: How do you add an element with the id myDiv to the HTML document using JavaScript?

<details><summary><b>Answer<br></summary>

```javascript
let newDiv = document.createElement("div");
newDiv.id = "myDiv";
document.body.appendChild(newDiv);
```

</details>

#### Question 8

Q: How do you create an array in JavaScript?

<details><summary><b>Answer<br></summary>

```js
let myArray = [1, 2, 3, 4, 5];
```

![alt text](image-5.png)

</details>

#### Question 9

Q: How do you access the first element of an array named myArray?

<details><summary><b>Answer<br></summary>

```js
let myArray = [1, 2, 3, 4, 5];
console.log(myArray[0]);
```

![alt text](image-6.png)

</details>

#### Question 10

Q. how we can modify Array Elements

<details><summary><b>Answer<br></summary>

```js
let myToy = ["car", "bike", "computer"];

myToy[2] = "Toyota Truck";

console.log(myToy);
```

![alt text](image-7.png)

</details>

#### Question 11

Q. Adding Elements to an Array

<details><summary><b>Answer<br></summary>

```js
// add an element to the end
let myNumber = [1, 2, 3];
myNumber.push(4);
console.log(myNumber);
```

![alt text](image-8.png)

```js
// add an element to the beginning
let myNumber = [2, 3, 4];
myNumber.unshift(1);

console.log(myNumber);
```

![alt text](image-9.png)

</details>

#### Question 12

Q. how we can remove Elements from an Array

<details><summary><b>Answer<br></summary>

```js
//remove last element
let language = ["Bangla", "English", "Abaric", "Hindi"];

language.pop();

console.log(language);
```

![alt text](image-10.png)

```js
//remove first element
let language = ["Bangla", "English", "Abaric", "Hindi"];

language.shift();

console.log(language);
```

![alt text](image-11.png)

</details>
