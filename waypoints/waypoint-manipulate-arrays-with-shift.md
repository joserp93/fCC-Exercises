#Waypoint: Manipulate Arrays With shift
<a href="http://freecodecamp.com/challenges/Waypoint:%20Manipulate%20Arrays%20With%20shift?solution=var%20ourArray%20%3D%20%5B%22Stimpson%22%2C%20%22J%22%2C%20%5B%22cat%22%5D%5D%3B%0AourRemoved%20%3D%20ourArray.shift()%3B%0A%2F%2F%20ourArray%20now%20equals%20%5B%22J%22%2C%20%5B%22cat%22%5D%5D.%0A%0Avar%20myArray%20%3D%20%5B%22John%22%2C%2023%2C%20%5B%22dog%22%2C%203%5D%5D%3B%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20myRemoved%20%3D%20myArray.shift()%3B%20%2F%2F%20This%20should%20be%20%5B%22John%22%5D%20and%20myArray%20should%20now%20be%20%5B23%2C%20%5B%22dog%22%2C%203%5D%5D.%0A%2F%2F%20Only%20change%20code%20above%20this%20line.%0A%0A%2F%2F%20We%20use%20this%20function%20to%20show%20you%20the%20value%20of%20your%20variable%20in%20your%20output%20box.%0A%2F%2F%20You%27ll%20learn%20about%20functions%20soon.%0A(function(y%2C%20z)%7Breturn%20%27myArray%20%3D%20%27%20%2B%20JSON.stringify(y)%20%2B%20%27%20%26%20myRemoved%20%3D%20%27%20%2B%20JSON.stringify(z)%3B%7D)(myArray%2C%20myRemoved)%3B%0A" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10"><code>pop()</code> always removes the last element of an array. What if you want to remove the first? That&apos;s where <code>.shift()</code> comes in.</p><p class="wrappable negative-10">Take the <code>myArray</code> array and <code>shift()</code> the first value off of it. Set <code>myRemoved</code> to the first value of <code>myArray</code> using <code>shift()</code>.</p><div class="negative-bottom-margin-30"><div id="MDN-links"><p class="negative-10">Here are some helpful links:</p></div></div>


####Answer:
```javascript
var ourArray = ["Stimpson", "J", ["cat"]];
ourRemoved = ourArray.shift();
// ourArray now equals ["J", ["cat"]].

var myArray = ["John", 23, ["dog", 3]];
// Only change code below this line.

var myRemoved = myArray.shift(); // This should be ["John"] and myArray should now be [23, ["dog", 3]].
// Only change code above this line.

// We use this function to show you the value of your variable in your output box.
// You'll learn about functions soon.
(function(y, z){return 'myArray = ' + JSON.stringify(y) + ' & myRemoved = ' + JSON.stringify(z);})(myArray, myRemoved);

```