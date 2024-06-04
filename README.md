# 10.3.1-sun-and-moon
Make sure to download the pictures for house, sun, and moon 

```javaScript
//Global Variables
let sky = 255;
let house, sun, moon;
let big = 10;

function preload(){
  house= createImg("house.png");
  sun= createImg("sun.png");
  moon= createImg("moon.png");
}//end preloading of images and fonts

function setup() {
  createCanvas(500, 600);
    
}//end setup

function draw() {
// step 1: set the sky variable
  background(sky);

//step 2 draw the sun & moon  Use if() statements 



//draw the snow
  fill(200);
  noStroke();
  rect(0,550,500,50);
  fill(255,0,0);

//Step 3 draw caption

  textSize(big);
  textAlign(CENTER);
  text("A fine winter's day!", width/2,590);
    
}//end draw

```
