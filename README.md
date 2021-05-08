# javascript-30-days-challenge
30 day Vanilla JavaScript coding challenge

## Project List

### 1. JavaScript Drum Kit
![drum-kit](https://user-images.githubusercontent.com/40417828/116617206-6e3d5f80-a8f2-11eb-97f2-d12e47530064.jpg)
[JS Drum Kit](https://jjessicacho.github.io/javascript-30-days-challenge/drum-kit/)

#### Things I learned:
- key events
    - `data attributes`: allow us to store extra information on standard
- audio
- transition end event / animation end event


### 2. CSS JavaScript Clock 
![clock](https://user-images.githubusercontent.com/40417828/116766547-e59ced00-a9df-11eb-8c7f-6a6e389c195a.jpg)
[CSS JS Clock](https://jjessicacho.github.io/javascript-30-days-challenge/css-js-clock/)
#### Things I learned:
- current time:
    - `getHours()`
    - `getMinutes()`
    - `getSeconds()`
- degree: `((seconds / 60) * 360) + 90`;
- `transition-timing-function: ease-in-out`
- style height property 

### 3. CSS Variable
![css-variables](https://user-images.githubusercontent.com/40417828/116798518-1004ae00-aaa5-11eb-8829-0fdbbacd1686.jpg)
[CSS Variables](https://jjessicacho.github.io/javascript-30-days-challenge/css-variables/)

#### Things I learned:
- mouse event
- forEach
- `style.setProperty(propertyName, value, priority);`
    - `propertyName` is a `DOMString` representing the CSS property name (hyphen case) to be modified.
    - `value` (Optional) is a `DOMString` containing the new property value. If not specified, treated as the empty string.
    *Note*: value must not contain "!important" -- that should be set using the priority parameter.

### 4. Array Cardio Day 1
[Array Cardio Day 1](https://jjessicacho.github.io/javascript-30-days-challenge/array-cardio-day-01/)
#### Things I learned:
- `console.table`: shows a table in the console 
- array filter
- array map
- array sort
- array reduce
- arrow function

### 4. Flex Panel Gallery
![flex-panel-gallery](https://user-images.githubusercontent.com/40417828/117208316-d7691b00-ada9-11eb-90f6-abfa8b3143b7.jpg)
[Flex Panel Gallery](https://jjessicacho.github.io/javascript-30-days-challenge/flex-panel-gallery/)

#### Things I learned:
- Advanced css flexbox
- Transition
- toggleOpen
- toggleActive
- transition"end" not transtioned


### 5. Type Ahead
![type-ahead](https://user-images.githubusercontent.com/40417828/117385483-14acd600-ae9a-11eb-8787-837792e6bea5.jpg)
[Type Ahead](https://jjessicacho.github.io/javascript-30-days-challenge/type-ahead/)

#### Things I learned:
- Fetch API 
- Promises 


### 5. Array Cardio Day 2
[Array Cardio Day 2](https://jjessicacho.github.io/javascript-30-days-challenge/array-cardio-day-02/)

#### Things I learned:
- `Array.prototype.some()`
- `Array.prototype.every()`
- `Array.prototype.find()`
- `Array.prototype.findIndex()`
- How to delete the comment without using `splice` (very popular in Redux): create a new array of the updated comments
```js
  const index = comments.findIndex(comment => comment.id === 823423);
  
  //comments.splice(index, 1);

  const newComments = [
    ...comments.slice(0, index),
    ...comments.slice(index + 1)
  ];
```


## Source
[JavaScript 30 by Wes Bros](https://javascript30.com/)

Photo by <a href="https://unsplash.com/@gopack?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Alexander Yemchenko</a> on <a href="https://unsplash.com/s/photos/drum?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
[keycode](http://keycode.info/)

[Using data attributes MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes)

[Style Height Property w3school](https://www.w3schools.com/jsref/prop_style_height.asp)

[CSS Style Declaration MDN](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/setProperty)

[Array.prototype.filter() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

[Array.prototype.map() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

[Array.prototype.sort() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)

[Array.prototype.reduce() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

[10 Classical Music Composers to Know](https://www.britannica.com/list/10-classical-music-composers-to-know)

[Learn Fetch API In 6 Minutes by Web Dev Simplified](https://www.youtube.com/watch?v=cuEtnrL9-H0)