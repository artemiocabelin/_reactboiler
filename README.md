### Main Packages
```
npm install --save redux react-redux react-router-dom redux-form redux-promise redux-thunk axios

```

### Optional Packages
```
npm i --save react-sparklines@1.6.0 


npm i --save gsap
npm i --save react-gsap-enhancer
npm i --save gsap-promise

npm install --save prop-types
npm install --save escape-string-regexp
npm install --save sort-by
npm install --save form-serialize
npm install --save react-icons
npm install --save react-loading
npm install --save react-modal
npm install --save redux-logger
```
---
#### React Sparklines 

Sparklines for react.

---
#### Redux Thunk 

Middleware that allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods dispatch and getState as parameters.

```javascript
import ReduxThunk from 'redux-thunk';
```

---

#### GSAP

A JavaScript library for high-performance HTML5 animations that work in all major browsers. No other library delivers such advanced sequencing, reliability, API efficiency, and tight control while solving real-world problems for animators on over 3 million sites. GSAP can animate any numeric property of any JS object, not just CSS properties.

```javascript
//typical import
import {TweenMax, Power2, TimelineLite} from "gsap";
 
//or get to the parts that aren't included inside TweenMax (works as of 1.19.1):
import Draggable from "gsap/Draggable";
import ScrollToPlugin from "gsap/ScrollToPlugin";
```

---
#### React GSAP Enhancer

We have great tools (like react-motion, or Animated) to animate the state and props of our React components but if you ever needed to create a longer animation sequence with React you can still feel the desire to reach out for a tool like GSAP which makes it easy to compose your animation and apply it on the DOM with its super performance and bulit in polyfills. Unfortunately, if you let anything to mutate the DOM of a component, React can break on the next update because is suppose that the DOM looks exacly the same like after the last update. This tool is a work around for this problem.

```javascript
import GSAP from 'react-gsap-enhancer'
 
class MyComponent extends Component {
  render() {/*...*/}
}
 
export default GSAP()(MyComponent)
```

---

#### GSAP Promise

---

#### PropTypes

PropTypes is a package that lets us define the data type we want to see right from the get-go and warn us during development if the prop that's passed to the component doesn't match what is expected.

---

#### escape-string-regexp

Escape RegExp special characters

---

#### Sort-By

A utility to create comparator functions for the native Array.sort() in both node and the browser. Allows for sorting by multiple properties.

---

#### Form-serialize

serialize form fields to submit a form over ajax

---