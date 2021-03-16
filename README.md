# JS

## Resources

- https://www.codecademy.com/learn/introduction-to-javascript
- https://www.codecademy.com/learn/paths/front-end-engineer-career-path


## What's Javascript

This a cool language

## Data Type

```javascript
// Number
const integer = 1; // 10, 20, 100, -1, -2
const float = 1.1; // 1.00, 1.3, -1.2

console.log(typeof integer)
console.log(typeof float)

console.log('---');

// String
const string1 = '1'; // '1', "1", `1`
const string2 = `1`;
const string3 = "1";
const string4 = "";
const string5 = "How are you~~~~" + "!!!" + "?";

console.log(typeof string1)
console.log(typeof string2)
console.log(typeof string3)
console.log(typeof string4)
console.log(typeof string5, string5)

console.log('---');

// function 食譜
// - name -> makeACake
// - arguements 食材 -> ()
// - steps 步驟 -> {}
// - return 蛋糕 -> return

// name + arguements
function makeACake(sugar, milk, flour, egg) {
  // steps
  const cake = sugar + milk + flour + egg;

  // return
  return cake;
}

// call function 有人要做蛋糕
const finalCake = makeACake('糖', '牛奶', '中筋麵粉', '蛋四顆');
console.log(finalCake);

function sum(num1, num2) {
  return num1 + num2;
}

const sumResult = sum(1, 100);
console.log('sumResult', sumResult);

function multiple(num, times) {
  return num * times;
}

const multipleResult = multiple(1, 100);
console.log('multipleResult', multipleResult);

const x = 1;
const y = 2;
const result = x + y;

// Array []
const arrayItem1 = 'A';
const array = [arrayItem1, 'C', 'B', 'D'];
console.log(typeof array, array);
console.log(array[0]);
console.log(array[1]);
console.log(array[2]);
console.log(array[3]);
console.log(array[4]);

const arrayItemTwo = 'A';
const array_item_two = 'A';

// Boolean 
console.log(1 + 1 === 2); // 等於
console.log(1 + 1 !== 2); // 不等於
console.log(typeof true)

const age = 20;
if (age < 18) {
  console.log('You can not drink');
} else {
  console.log('You can drink');
}

// Object {}
// 想成一個人
const person = {
  // properties 人身上的部分
  hair: 'black',
  eye: 'blue',
  lip: 'red',
  hands: {
    left: 5,
    right: 5,
  },

  cloths: ['flower', 'modern'],

  say: function ajsdklajsdlasjdklasjdkl(word) {
    return word;
  }
};

console.log(person.hair)
console.log(person.hands.left)
console.log(person.cloths[1])
console.log(person.say('隨便都可以'))
```

## Variable
