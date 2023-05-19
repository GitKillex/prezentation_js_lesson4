<h1 align = 'center'>JavaScript Lecture #4 </h1>

## Array
### Array - is a data which can conatain many datas

## Creating Array 
_to create array we must to put square after initializating variable_

```javascript
let nums = [nums1,nums2,nums3,...];
```


## Array - Methods
+ .pop()
  + Удаляет с конца
  ```javascript
   const numbers = [4,9,16,25];
   const newArr = numbers.pop() //4 9 16 
   ```
+ .shift()
  + Удаляет с начала
   ```javascript
   const numbers = [4,9,16,25];
   const newArr = numbers.shift() //9 16 25
   ```
+ .push()
  + Добавляет с конца
  ```javascript
   const numbers = [4,9,16,25];
   const newArr = numbers.push(100) //4 9 16 25 100
   ```
+ .unshift()
  + Добавляет с начала
  ```javascript
   const numbers = [4,9,16,25];
   const newArr = numbers.unshift(7,8) //7 8 4 9 16 25
   ```
+ .concat()
  + Объединяет несколько массивов
  ```javascript
   const numbers = [4,9,16,25];
   const numbers2 = [1,2,3,4,5];
   const newArr = numbers.concat(numbers2) //4 9 16 25 1 2 3 4 5 
   ```
+ .slice()
  + Показывает елементы с начала до конца
  ```javascript
   const numbers = [4,9,16,25];
   const newArr = numbers.slice(1,3) // 9 16 
   ```
+ .join()
  + Соединяет несколько массивов в один целый
  + .slice()
  + Показывает елементы с начала до конца
+ .includes()
  + Отправляет буловое значение ест ли данный элемент в данном массиве
  + .slice()
  + Показывает елементы с начала до конца
  ```javascript
   const numbers = [4,9,16,25];
   const newArr = numbers.map(Math.sqrt) 
   ```
+ .indexOf()
  + Показывает индекс определенного элемента
+ .splice()
  + 
+ .toString()
  + Превращает в строку весь массив через запятую 
+ .toReversed()
  + Переворачивает массив оставляя оригиналбный массив
# CallBack Functions
+ .forEach()
  ```javascript
   const ages = [3,10,19,20];
   function checkAge(age){
     return age > 18;
   } 
   console.log(ages.find(checkAge))
   ```
+ .map()
   ```javascript
   const numbers = [4,9,16,25];
   const newArr = numbers.map(Math.sqrt) 
   ```
+ .find()
  + Находит есть ли элемент в данном массиве и отправляет его индекс
  ```javascript
   const ages = [3,10,19,20];
   function checkAge(age){
     return age > 18;
   } 
   console.log(ages.find(checkAge))
   ```
+ .filter()
  ```javascript
   const words = [1,2,4,50,5,6,7,8,88];
   const result = words.filter(n => n>5)
   console.log(ages.find(checkAge))
   ```
+ .reduce()
  ```javascript
   const array1 = [1,2,3,4];
   const initialValue = 0;
   const sumWithInitial = array1.reduce(
     (accumulator, currentValue) => accumulator + currentValue,
     initialValue
   );
   console.log(sumWithInitial)
   ```
+ toSorted()

<h1 align = 'center'>Thank you for Reading!!!</h1>

# prezentation_js_lesson4
