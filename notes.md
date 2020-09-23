1. lorem50 will give 50 words.
2. for image tag, "alt" means alternative text which display if image is not loaded for some reason.
3. unsplash - (for random images)
4. ## HTML table tags

```
    <thead> - table header
    <tr> - table row
    <th> -  table heading
    <tbody> - table body

```
5. Button tye - reset - resets all the fields in the form.

```
    <button type="reset">Reset</button>

```
## Practices for Responsive Design

1. Set the viewport/sacle
2. Use fluid widthsa soppose to fixed
3. Media queries 
4. rem units over px
5. Mobile first Method

* example for using vh unit and setting image as background.

```
 body {
            background:  #eee url('https://source.unsplash.com/random;') no-repeat center center/cover;
            height: 100vh;
        }
```

## CSS Grid

* Similar to flexbox. (but more powerfull)
* eg: display: grid;   // creates a grid
* "grid-template-columns" defines width and number of cols.
* Better for 2 dimensional layouts.

### CSS units relative 
```
%   -To parent element
em  -To font size of parent element
rem -To font size of root elemnt
vw  -To 1% of viewport width
vh  -To 1% of viewport height
```
### specific attribute selection
```
input[type='text'];
input[type='email'];
```

**Nth child selector**

```
li:nth-child(3) // 3rd child
li:nth-child(3n+0) // every 3rd child
li:nth-child(odd)  // odd child
```

## before and after

eg:
```
.is-required:after {    // this will insert a red star sign without affecting html
    content; '*';
    color: red;
}
```

**Box shadow**
```
box-shadow: 3px 3px 10px 1px rgba(0,0,0,0.3)
offset x, offset y, blur radius, spread radius
```

### CSS variables

```
:root {
   --light-color: #eeee; 
}

background: var(--light-color); //usage
```
 ### Transition

 eg:

 .box {
     width: 100px;
     height: 100px;
     Transition: all 2s ease-in-out;
 }

 .box:hover {
     backrgound: red;
     border-radius: 50%;
     height: 300px;
     width: 300px;
 }

 ### keyframes

 eg:
 ```
 .box {
     backrgound: red;
     height: 300px;
     width: 300px;
     animation: animate1 5s forwards 1s ease-in-out;
 }

 @keyframes animate1 {
     from {
         top: 0;
     }

     width {
         width: 600px;
     }
 }
 ```




 


