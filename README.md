//Drawing custom shapes

void setup() {
  size(840,660);
  
}

void draw(){
  
  background(#FFF8F7);

//Draw rectangle
fill(#FF766A);
stroke(#030000);
rect(290,20,240,180);
fill(#D37F77);
rect(180,220,480,360);
fill(#DE9A94);
rect(210,230,450,330);
fill(#F5C3BE);
rect(230,250,430,310);
fill(#F59188);
rect(250,270,410,290);
fill(#FF7164);
rect(270,290,390,270);
fill(#F0D1CE);
rect(290,310,370,250);
fill(#F0928A);
rect(310,330,350,230);
fill(#F0D1CE);
rect(330,350,330,210);
fill(#FF766A);
rect(350,370,310,190);

//Draw packman
fill(#D1574C);
arc(600,450,80,80,0,PI+HALF_PI,PIE);
arc(500,450,80,80,0,PI+HALF_PI,PIE);
arc(400,450,80,80,0,PI+HALF_PI,PIE);

//Drawing eyes
fill(#5F312D);
stroke(#FFFDFC);
ellipse(350,70,50,50);
ellipse(470,70,50,50);

//Draw mouth
fill(#DB2B1B);
stroke(#FFFDFC);
rect(360,120,100,50);

//Drawing legs
fill(#DB2B1B);
stroke(#030000);
rect(300,585,30,30);
rect(300,630,30,30);
rect(500,585,30,30);
rect(500,630,30,30);

//Drawing arms
fill(#FF7164);
rect(670,380,150,50);
rect(20,380,150,50);



}
