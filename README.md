# 10.3.1-sun-and-moon
Make sure to down load the pictures Too 

```
//Global Variables
let sky = 255;
let house, sun, moon;
let big = 10;

function preload(){
  house= loadImage("images/house.png");
  sun= loadImage("images/sun.png");
  moon= loadImage("images/moon.png");
}//end preloading of images and fonts

function setup() {
  createCanvas(500, 600);
    
}//end setup

function draw() {
//1 
  background(sky);
   
  //draw the sun & moon
  //2
  imageMode(CENTER)
  image(house,250,475,150,150)
  image(sun, mouseX, 100,350,350);

    //draw the snow
  fill(200);
  noStroke();
  rect(0,550,500,50);
  fill(255,0,0);

    // draw caption
  //3
  textSize(big);
  textAlign(CENTER);
  text("A fine winter's day!", width/2,590);
    
}//end draw

```
