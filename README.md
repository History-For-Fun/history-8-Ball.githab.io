var fontAppears = true;
var x = 200;
var y = 250;
var answer =7;
var r = 100;
var g = 0; 
var b  = 255;
var rp = 5;
var gp = 5;
var bp = 5;
var thereshadow = false;
var draw = function() {
    background(255, 18, 18);
    for(var p = 400; p > -1; p-=1){
        stroke(p-255, 0, p);
        strokeWeight(-9);
        line(0, p, 395, p);
        text("Hatshepsut", 65, 229);
    }
    fill(0, 0, 0);
    
    textSize(30);
         text("Hatshepsut", x, y);
    fill(255, 255, 255);
     ellipse(x, y, 300, 300);
     fill(0, 0, 0);
         triangle(289, 211, 94, 214, 198, 315);
     if (mouseIsPressed) {
         fill(255, 0, 0);
         textSize(24);
         text("Hatshepsut", 139, 229);
         
     }
     else {
         textSize(12);
         
         fill(255, 0, 0);
         text("Who Is The Greatest", 139, 229);
         text("Female Pharaoh?", 155, y);
        text("Press Here To Know", 141, 208); 
     }
    text("History 8-ball", 160, 121);
};
