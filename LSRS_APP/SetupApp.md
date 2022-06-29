#LSRS Application
##Setup
### REACT
 npm version 5.2+ :
 <br> <code> <b> $:> cd projectname $:> npx create-react-app . </code>
 <br> or 
 <br> <code> $:> npx create-react-app projectname </b> </code>
 
### animation CSS 
[animation CSS](https://animate.style/)
<br> <code> <b>  ``` $:> npm install animate.css --save ```</b></code>
<br>
*** App.js **
<br> <code> <b>  ```  import 'animate.css';  ```</b></code>
<br>
*** copy method 
className = " animate_animated animate__fadeIn" 


### React Transition Group

[Motion](https://reactcommunity.org/react-transition-group/)

<br> <code> <b>  ``` $:>npm install react-transition-group --save ```</b></code>
<br>
*** App.js **
<br> <code> <b>  ```  import {
  CSSTransition,
  SwitchTransition,
} from 'react-transition-group';  ```</b></code>
<br>

### react-toastify

[react-toastify](https://www.npmjs.com/package/react-toastify)
<br>
<br> <code> <b>  ``` $:>npm i react-toastify</b></code>


#### App.js
*** Bootstrap CSS
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous"/>
```
<br>

*** Google Font (Thai) **
```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Niramit:wght@200;300;400;500&display=swap" rel="stylesheet">
```

### Deploy 

*** build folder

<br> <code> <b>  ``` $:>npm run build ```</b></code>

### Surge 

[Surge](https://surge.sh/help/getting-started-with-surge)
<br> <code> <b>  ``` $:>npm install --global surge```</b></code>

<br> <code> <b>  ``` $:>surge```</b></code>
<br> <code> <b>  ``` email password type "build" and enter url ```</b></code>

