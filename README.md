function setup() {
  createCanvas(1920,1080);
  fr=createSprite(400, 200, 50, 50);
  fr.shapeColor="green"
  mr=createSprite(400, 200, 50, 50);
  mr.shapeColor="green"
}

function draw() {
background(255,255,255); 

mr.x=World.mouseX
mr.x=World.mouseY

if (fr.x-mr.x<fr.width/2+mr.width/2 && mr.x-fr.x<mr.width/2+fr.width/2 && fr.y-mr.y<fr.height/2+mr.height/2 && mr.y-fr.y<fr.height/2+mr.height/2) {
  fr.shapeColor="red"
  mr.shapeColor="red"
}
else {ss
  fr.shapeColor="green"
  mr.shapeColor="green"
}




  drawSprites();
}
