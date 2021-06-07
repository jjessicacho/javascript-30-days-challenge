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

### 5. Flex Panel Gallery
![flex-panel-gallery](https://user-images.githubusercontent.com/40417828/117208316-d7691b00-ada9-11eb-90f6-abfa8b3143b7.jpg)
[Flex Panel Gallery](https://jjessicacho.github.io/javascript-30-days-challenge/flex-panel-gallery/)

#### Things I learned:
- Advanced css flexbox
- Transition
- toggleOpen
- toggleActive
- transition"end" not transtioned

### 6. Type Ahead
![type-ahead](https://user-images.githubusercontent.com/40417828/117385483-14acd600-ae9a-11eb-8787-837792e6bea5.jpg)
[Type Ahead](https://jjessicacho.github.io/javascript-30-days-challenge/type-ahead/)

#### Things I learned:
- Fetch API 
- Promises 

### 7. Array Cardio Day 2
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

### 8. HTML5 Canvas
![canvas](https://user-images.githubusercontent.com/40417828/117739042-48e20880-b1b2-11eb-9c2f-b72ac4def9c1.jpg)
[HTML5 Canvas](https://jjessicacho.github.io/javascript-30-days-challenge/canvas/)

#### Things I learned:
- Change width and height to 100% screen in JavaScript
- lineJoin, lineCap: "bevel" || "round" || "miter"
- Blend mode
- Stroke Style: `hsl(${hue}, 100%, 50%)`
- How to make it more simple: 
```js
[lastX, lastY] = [e.offsetX, e.offsetY];
  // this is same as following:
  // lastX = e.offsetX;
  // lastY = e.offsetY;
```

### 9. Dev Tools Domination
[Dev Tools Domination](https://jjessicacho.github.io/javascript-30-days-challenge/dev-tools-domination/)

#### Things I learned:
console
- log
- interpolated ('')
- styled (css)
- warning: warn
- error 
- testing
- clear
- viewing DOM Elements: dir
- grouping together: group
- counting: count
- timing (how long it takes): time, timeEnd, fetch

### 10. Hold Shift to Check Checkbox
![checkbox](https://user-images.githubusercontent.com/40417828/118047152-36410e00-b32f-11eb-9945-db2e6d641121.jpg)
[Hold Shift to Check Checkbox](https://jjessicacho.github.io/javascript-30-days-challenge/checkbox/)

#### Things I learned:
- choose multiple checkbox
  - loop 
  - forEach
- flag variable

### 11. Custom Video Player
![custom-video-player](https://user-images.githubusercontent.com/40417828/118204882-13d4f080-b414-11eb-946d-fa498c6a4245.jpg)
[Custom Video Player](https://jjessicacho.github.io/javascript-30-days-challenge/custom-video-player/)

#### Things I learned:
- play video
- pause video
- drag video bar
- update bar
- volume up and down
- skip before (-10 seconds) and after (25 seconds) 

### 12. Key Sequence Detection (KONAMI CODE)
![key-sequence-detection](https://user-images.githubusercontent.com/40417828/118204884-15061d80-b414-11eb-8455-7fd750a500e7.jpg)
[Key Sequence Detection](https://jjessicacho.github.io/javascript-30-days-challenge/key-sequence-detection/)

#### Things I learned:
- key sequencing detection
- store them in an array
- check every single time that they key up if it matches what you're looking for

### 13. Slide In on Scroll
![slide](https://user-images.githubusercontent.com/40417828/118336838-54da0d00-b4c7-11eb-9926-29e79cfd57d4.jpg)
[Slide In on Scroll](https://jjessicacho.github.io/javascript-30-days-challenge/slide-in-on-scroll/)

#### Things I learned:
- console.count()
- Calculate half way through the image and bottom of the image
  - window.scrollY
  - offsetTop

### 14. JavaScript References VS Copy
[JavaScript References VS Copy](https://jjessicacho.github.io/javascript-30-days-challenge/js-references-vs-copying/)

#### Things I learned:
- array concat
- object assign
- JSON parse (not recommend to use in this project though)

### 15. LocalStorage
![localStorage](https://user-images.githubusercontent.com/40417828/118418248-8f30df00-b66c-11eb-9b76-2c1b42505724.jpg)
[LocalStorage](https://jjessicacho.github.io/javascript-30-days-challenge/localStorage/)

#### Things I learned:
- preserve log
- save items to local storage 

### 16. Mouse Move Shadow 
![mouse-move-shadow](https://user-images.githubusercontent.com/40417828/118886221-84b15800-b8ad-11eb-86f8-aef46bb91ed7.jpg)
[Mouse Move Shadow](https://jjessicacho.github.io/javascript-30-days-challenge/mouse-move-shadow/)

#### Things I learned:
- Using offset to get the position where your cursor is 
- If you have nested elements inside the if statement, you sometimes will need to do a little bit of math 

### 17. Sort Without Articles 
![sort-without-articles](https://user-images.githubusercontent.com/40417828/119030607-f85f6d80-b95e-11eb-84b3-4ac3d2ee4609.jpg)
[Sort Without Articles](https://jjessicacho.github.io/javascript-30-days-challenge/sort-without-articles/)

#### Things I learned:
- Sort lists without articles using `strip`

### 18. Tally String Times with Reduce
[Tally String Times with Reduce](https://jjessicacho.github.io/javascript-30-days-challenge/tally-string-times-with-reduce/)

#### Things I learned:
- By using Reduce, add the total number of minutes, seconds and hours that is the actual videos

---
For the following challenges that include `package.json`:
- How to open the file:
  - go to `cmd`
  - go to the file location 
  - `npm install`
  - `npm start`

*jason file is required for a local host (aka secure origin)*

---
### 19. Webcam

#### Things I learned:
- live video from webcam 
- canvas element
- take photos 
- download photos 
- photo edit effects (rgbSplit)
 
### 20. Speech Detection
#### Things I learned:
- speech recognition in the browser (without any libraries or external APIs)
- Voice to Text
 
### 21. Geolocation
- Required devices:
  - Mac laptop or iOS Phone
  - Xcode (aka simulator)
  - Safari
- Note: This challenge is not monitored because I do not own either Mac or iOS.
#### Things I learned:
- Simulate the Geolocation
  
### 22. Follow Along Links
![follow-along-link](https://user-images.githubusercontent.com/40417828/120876771-afff9c80-c567-11eb-972d-105dae4678fc.jpg)
[Follow Along Links](https://jjessicacho.github.io/javascript-30-days-challenge/highlighter/)

#### Things I learned:
- When hover over the nav, the highlight background follow links 
- transition 

### 23. Speech Synthesis
![speech-synthesis](https://user-images.githubusercontent.com/40417828/120877062-45e7f700-c569-11eb-90d7-f1878a3cfb36.jpg)
[Speech Synthesis](https://jjessicacho.github.io/javascript-30-days-challenge/speech-synthesis/)

#### Things I learned:
- Speech Synthesis API
- Text to Voice
- Rate (Fast/Slow)
- Pitch (High/Low)

### 24. Sticky Nav
![sticky-nav](https://user-images.githubusercontent.com/40417828/120878135-54391180-c56f-11eb-97b7-3391e792193c.jpg)
[Sticky Nav](https://jjessicacho.github.io/javascript-30-days-challenge/sticky-nav/)

#### Things I learned:
- Fix a nav when you scroll to it
- Do not hard code the height because it is different by the screen size 

### 25. Event Capture, Propagation, Bubbling and Once
[Event Capture, Propagation, Bubbling and Once](https://jjessicacho.github.io/javascript-30-days-challenge/event-capture-propagation-bubbling-once/)

#### Things I learned:
- Event Capture
  - `capture: false;` <- default
- Propagation
  - `e.stopPropagation`: stop bubbling
- Bubbling
  - bubble up: when you click on the element, it will trigger an event on the parent and that parent as well
- Once
  - `once: true;` 
  - It will listen for a click once, then unbind itself so that there's no future clicks on it 
  - usually use this for `button`

### 26. Stripe Follow Along Dropdown
![dropdown](https://user-images.githubusercontent.com/40417828/120908888-f4e90900-c623-11eb-8e43-7f2385ace1b4.jpg)
[Stripe Follow Along Dropdown](https://jjessicacho.github.io/javascript-30-days-challenge/dropdown/)

#### Things I learned:
- the background of the dropdown transform itself from the width and the height as well as wherever it is on the page (x & y)

### 27. Click and Drag
![click-drag](https://user-images.githubusercontent.com/40417828/120909354-15679200-c629-11eb-9f58-70bf74619a3c.jpg)
[Click and Drag](https://jjessicacho.github.io/javascript-30-days-challenge/click-drag/)

#### Things I learned:
- click and drag elements horizontally

### 28. Video Speed Controller UI
![video-speed-controller-ui](https://user-images.githubusercontent.com/40417828/120909745-0be02900-c62d-11eb-91db-d36cab2e996b.jpg)
[Video Speed Controller UI](https://jjessicacho.github.io/javascript-30-days-challenge/video-speed-controller-ui/)

#### Things I learned:
- Create a bar that controls the speed of the video 
- playback rate when min is not 0 nor max is 100
- 2 decimal places: toFixed(2)


### 29. Countdown Clock
![countdown](https://user-images.githubusercontent.com/40417828/120945024-4bba1580-c6ec-11eb-944f-e94f6c93a60e.jpg)
[Countdown Clock](https://jjessicacho.github.io/javascript-30-days-challenge/countdown-clock/)

#### Things I learned:
- countdown timer (minutes: seconds)
- what time to be back
- `Date.now()` - current time in milliseconds 
- `setInterval`
- `Math.floor()` - to round up 
- ternary operator: `minutes < 10 ? '0' : ''` - if the minutes are less than 10, return a 0, otherwise return nothing
-  `e.preventDefault();` - to stop reloading the page and send the data over a get
- timestamp

























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

[CanvasRenderingContext2D.lineJoin](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineJoin)

[How to select only one DIV from multiple divs using javascript](https://stackoverflow.com/questions/31531461/how-to-select-only-one-div-from-multiple-divs-using-javascript/31533039)