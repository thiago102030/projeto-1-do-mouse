# projeto-1-do-mouse
function setup() {
  createCanvas(800, 800);
     background("black");

}

function draw() {
 
  stroke("blue");
  fill ("red");
 
  if(mouseIsPressed){
    rect(mouseX, mouseY, 10, 10);
  }
}
