#Waypoint: Create a JavaScript Slot Machine
<a href="http://freecodecamp.com/challenges/Waypoint:%20Create%20a%20JavaScript%20Slot%20Machine?solution=fccss%0A%20%20function%20runSlots()%7B%0A%20%20%20%20var%20slotOne%3B%0A%20%20%20%20var%20slotTwo%3B%0A%20%20%20%20var%20slotThree%3B%0A%20%20%20%0A%20%20%20%20var%20images%20%3D%20%5B%22http%3A%2F%2Fi.imgur.com%2F9H17QFk.png%22%2C%20%22http%3A%2F%2Fi.imgur.com%2F9RmpXTy.png%22%2C%20%22http%3A%2F%2Fi.imgur.com%2FVJnmtt5.png%22%5D%3B%0A%20%20%20%20var%20myArray%20%3D%20%5B%5D%3B%20%20%20%0A%20%20%20%20%2F%2F%20Only%20change%20code%20below%20this%20line.%0Avar%20rand%20%3D%20Math.floor(Math.random()%20*%20(3%20-%201%20%2B%201))%20%2B%201%3B%0AmyArray.push(rand)%3B%0Avar%20rand%20%3D%20Math.floor(Math.random()%20*%20(3%20-%201%20%2B%201))%20%2B%201%3B%0AmyArray.push(rand)%3B%0Avar%20rand%20%3D%20Math.floor(Math.random()%20*%20(3%20-%201%20%2B%201))%20%2B%201%3B%0AmyArray.push(rand)%3B%0A%20%20%20%20%0A%20%20%20%20slotOne%20%3D%20myArray%5B0%5D%3B%0A%20%20%20%20slotTwo%20%3D%20myArray%5B1%5D%3B%0A%20%20%20%20slotThree%20%3D%20myArray%5B2%5D%3B%0A%20%20%20%20%0A%20%20%20%20%2F%2F%20Only%20change%20code%20above%20this%20line.%0A%20%20%20%20%0A%20%20%20%20%24(%22.logger%22).html(%22%22)%3B%0A%20%20%20%20%24(%22.logger%22).html(%22Not%20A%20Win%22)%0A%20%20%20%20%0A%20%20%20%20if(slotOne%20!%3D%3D%20undefined%20%26%26%20slotTwo%20!%3D%3D%20undefined%20%26%26%20slotThree%20!%3D%3D%20undefined)%7B%0A%20%20%20%20%20%20%24(%22.logger%22).html(slotOne%20%2B%20%22%20%22%20%2B%20slotTwo%20%2B%20%22%20%22%20%2B%20slotThree)%3B%0A%20%20%20%20%7D%0A%20%20%20%20return%20%5BslotOne%2C%20slotTwo%2C%20slotThree%5D%3B%0A%20%20%7D%0A%0A%20%20%24(document).ready(function()%7B%0A%20%20%20%20%20%24(%22.go%22).click(function()%7B%0A%20%20%20%20%20%20%20runSlots()%3B%0A%20%20%20%20%20%7D)%3B%0A%20%20%20%7D)%3B%0Afcces%0A%20%0A%3Cdiv%3E%0A%20%3Cdiv%20class%20%3D%20%22container%20inset%22%3E%0A%20%20%20%3Cdiv%20class%20%3D%20%22header%20inset%22%3E%0A%20%20%20%20%20%3Cimg%20src%3D%22https%3A%2F%2Fs3.amazonaws.com%2Ffreecodecamp%2Ffreecodecamp_logo.svg.gz%22%20alt%3D%22learn%20to%20code%20javascript%20at%20Free%20Code%20Camp%20logo%22%20class%3D%22img-responsive%20nav-logo%22%3E%0A%20%20%20%20%20%3Ch2%3EFCC%20Slot%20Machine%3C%2Fh2%3E%0A%20%20%20%3C%2Fdiv%3E%0A%20%20%20%3Cdiv%20class%20%3D%20%22slots%20inset%22%3E%0A%20%20%20%20%20%3Cdiv%20class%20%3D%20%22slot%20inset%22%3E%0A%20%20%20%20%20%20%20%0A%20%20%20%20%20%3C%2Fdiv%3E%0A%20%20%20%20%20%3Cdiv%20class%20%3D%20%22slot%20inset%22%3E%0A%20%20%20%20%20%20%20%0A%20%20%20%20%20%3C%2Fdiv%3E%0A%20%20%20%20%20%3Cdiv%20class%20%3D%20%22slot%20inset%22%3E%0A%20%20%20%20%20%20%20%0A%20%20%20%20%20%3C%2Fdiv%3E%0A%20%20%20%3C%2Fdiv%3E%0A%20%20%20%3Cbr%2F%3E%0A%20%20%20%3Cdiv%20class%20%3D%20%22outset%22%3E%0A%20%20%20%20%20%3Cbutton%20class%20%3D%20%22go%20inset%22%3E%0A%20%20%20%20%20%20%20Go%0A%20%20%20%20%20%3C%2Fbutton%3E%0A%20%20%20%3C%2Fdiv%3E%0A%20%20%20%3Cbr%2F%3E%0A%20%20%20%3Cdiv%20class%20%3D%20%22foot%20inset%22%3E%0A%20%20%20%20%20%3Cspan%20class%20%3D%20%22logger%22%3E%3C%2Fspan%3E%0A%20%20%20%3C%2Fdiv%3E%0A%20%3C%2Fdiv%3E%0A%3C%2Fdiv%3E%0A%0A%3Cstyle%3E%0A%20.container%20%7B%0A%20%20%20background-color%3A%20%234a2b0f%3B%0A%20%20%20height%3A%20400px%3B%0A%20%20%20width%3A%20260px%3B%0A%20%20%20margin%3A%2050px%20auto%3B%0A%20%20%20border-radius%3A%204px%3B%0A%20%7D%0A%20.header%20%7B%0A%20%20%20border%3A%202px%20solid%20%23fff%3B%0A%20%20%20border-radius%3A%204px%3B%0A%20%20%20height%3A%2055px%3B%0A%20%20%20margin%3A%2014px%20auto%3B%0A%20%20%20background-color%3A%20%23457f86%0A%20%7D%0A%20.header%20h2%20%7B%0A%20%20%20height%3A%2030px%3B%0A%20%20%20margin%3A%20auto%3B%0A%20%7D%0A%20.header%20h2%20%7B%0A%20%20%20font-size%3A%2014px%3B%0A%20%20%20margin%3A%200%200%3B%0A%20%20%20padding%3A%200%3B%0A%20%20%20color%3A%20%23fff%3B%0A%20%20%20text-align%3A%20center%3B%0A%20%7D%0A%20.slots%7B%0A%20%20%20display%3A%20flex%3B%0A%20%20%20background-color%3A%20%23457f86%3B%0A%20%20%20border-radius%3A%206px%3B%0A%20%20%20border%3A%202px%20solid%20%23fff%3B%0A%20%7D%0A%20.slot%7B%0A%20%20%20flex%3A%201%200%20auto%3B%0A%20%20%20background%3A%20white%3B%0A%20%20%20height%3A%2075px%3B%0A%20%20%20margin%3A%208px%3B%0A%20%20%20border%3A%202px%20solid%20%23215f1e%3B%0A%20%20%20border-radius%3A%204px%3B%0A%20%7D%0A%20.go%20%7B%0A%20%20%20width%3A%20100%25%3B%0A%20%20%20color%3A%20%23fff%3B%0A%20%20%20background-color%3A%20%23457f86%3B%0A%20%20%20border%3A%202px%20solid%20%23fff%3B%0A%20%20%20border-radius%3A%202px%3B%0A%20%20%20box-sizing%3A%20none%3B%0A%20%20%20outline%3A%20none!important%3B%0A%20%7D%0A%20.foot%20%7B%0A%20%20%20height%3A%20150px%3B%0A%20%20%20background-color%3A%20457f86%3B%0A%20%20%20border%3A%202px%20solid%20%23fff%3B%0A%20%7D%0A%20%0A%20.logger%20%7B%0A%20%20%20color%3A%20white%3B%0A%20%20%20margin%3A%2010px%3B%0A%20%7D%0A%20%0A%20.outset%20%7B%0A%20%20%20-webkit-box-shadow%3A%200px%200px%2015px%20-2px%20rgba(0%2C0%2C0%2C0.75)%3B%0A%20%20%20-moz-box-shadow%3A%200px%200px%2015px%20-2px%20rgba(0%2C0%2C0%2C0.75)%3B%0A%20%20%20%20%20box-shadow%3A%200px%200px%2015px%20-2px%20rgba(0%2C0%2C0%2C0.75)%3B%0A%20%7D%0A%20%0A%20.inset%20%7B%0A%20%20%20-webkit-box-shadow%3A%20inset%200px%200px%2015px%20-2px%20rgba(0%2C0%2C0%2C0.75)%3B%0A%20%20%20-moz-box-shadow%3A%20inset%200px%200px%2015px%20-2px%20rgba(0%2C0%2C0%2C0.75)%3B%0A%20%20%20box-shadow%3A%20inset%200px%200px%2015px%20-2px%20rgba(0%2C0%2C0%2C0.75)%3B%0A%20%7D%0A%3C%2Fstyle%3E%0A" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10">We are now going to try and combine some of the stuff we&apos;ve just learned and create the logic for a slot machine game.</p><p class="wrappable negative-10">For this we will need to generate three random numbers between <code>1</code> and <code>3</code> to represent the possible values of each individual slot.</p><p class="wrappable negative-10">Store the three random numbers in <code>slotOne</code>, <code>slotTwo</code> and <code>slotThree</code>.</p><p class="wrappable negative-10">Generate the random numbers by using the system we used earlier (an explanation of the formula can be found <a href="https://github.com/FreeCodeCamp/FreeCodeCamp/wiki/Waypoint-Generate-Random-Whole-Numbers-within-a-Range#explanation">here</a>):</p><p class="wrappable negative-10"><code>Math.floor(Math.random() * (3 - 1 + 1)) + 1;</code></p><div class="negative-bottom-margin-30"></div>


####Answer:
```javascript
fccss
  function runSlots(){
    var slotOne;
    var slotTwo;
    var slotThree;
   
    var images = ["http://i.imgur.com/9H17QFk.png", "http://i.imgur.com/9RmpXTy.png", "http://i.imgur.com/VJnmtt5.png"];
    var myArray = [];   
    // Only change code below this line.
var rand = Math.floor(Math.random() * (3 - 1 + 1)) + 1;
myArray.push(rand);
var rand = Math.floor(Math.random() * (3 - 1 + 1)) + 1;
myArray.push(rand);
var rand = Math.floor(Math.random() * (3 - 1 + 1)) + 1;
myArray.push(rand);
    
    slotOne = myArray[0];
    slotTwo = myArray[1];
    slotThree = myArray[2];
    
    // Only change code above this line.
    
    $(".logger").html("");
    $(".logger").html("Not A Win")
    
    if(slotOne !== undefined && slotTwo !== undefined && slotThree !== undefined){
      $(".logger").html(slotOne + " " + slotTwo + " " + slotThree);
    }
    return [slotOne, slotTwo, slotThree];
  }

  $(document).ready(function(){
     $(".go").click(function(){
       runSlots();
     });
   });
fcces
 
<div>
 <div class = "container inset">
   <div class = "header inset">
     <img src="https://s3.amazonaws.com/freecodecamp/freecodecamp_logo.svg.gz" alt="learn to code javascript at Free Code Camp logo" class="img-responsive nav-logo">
     <h2>FCC Slot Machine</h2>
   </div>
   <div class = "slots inset">
     <div class = "slot inset">
       
     </div>
     <div class = "slot inset">
       
     </div>
     <div class = "slot inset">
       
     </div>
   </div>
   <br/>
   <div class = "outset">
     <button class = "go inset">
       Go
     </button>
   </div>
   <br/>
   <div class = "foot inset">
     <span class = "logger"></span>
   </div>
 </div>
</div>

<style>
 .container {
   background-color: #4a2b0f;
   height: 400px;
   width: 260px;
   margin: 50px auto;
   border-radius: 4px;
 }
 .header {
   border: 2px solid #fff;
   border-radius: 4px;
   height: 55px;
   margin: 14px auto;
   background-color: #457f86
 }
 .header h2 {
   height: 30px;
   margin: auto;
 }
 .header h2 {
   font-size: 14px;
   margin: 0 0;
   padding: 0;
   color: #fff;
   text-align: center;
 }
 .slots{
   display: flex;
   background-color: #457f86;
   border-radius: 6px;
   border: 2px solid #fff;
 }
 .slot{
   flex: 1 0 auto;
   background: white;
   height: 75px;
   margin: 8px;
   border: 2px solid #215f1e;
   border-radius: 4px;
 }
 .go {
   width: 100%;
   color: #fff;
   background-color: #457f86;
   border: 2px solid #fff;
   border-radius: 2px;
   box-sizing: none;
   outline: none!important;
 }
 .foot {
   height: 150px;
   background-color: 457f86;
   border: 2px solid #fff;
 }
 
 .logger {
   color: white;
   margin: 10px;
 }
 
 .outset {
   -webkit-box-shadow: 0px 0px 15px -2px rgba(0,0,0,0.75);
   -moz-box-shadow: 0px 0px 15px -2px rgba(0,0,0,0.75);
     box-shadow: 0px 0px 15px -2px rgba(0,0,0,0.75);
 }
 
 .inset {
   -webkit-box-shadow: inset 0px 0px 15px -2px rgba(0,0,0,0.75);
   -moz-box-shadow: inset 0px 0px 15px -2px rgba(0,0,0,0.75);
   box-shadow: inset 0px 0px 15px -2px rgba(0,0,0,0.75);
 }
</style>

```