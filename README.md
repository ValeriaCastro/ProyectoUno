# ProyectoUno
Primer ejercicio como ejemplo
int tam;
float spin=0.0;
PImage imag;

void setup()
{
  size(600,600,P3D);
  imag=loadImage("fondo.jpg");
  tam=width/6;
}

void draw()
{
  image(imag,0,0,width,height);
  cubo();
}

void cubo()
{
    pointLight(150,100,0,200,-150,0);
    directionalLight(0,102,255,1,0,0);
    spotLight(255,255,255,0,40,200,0,-0.5,-0.5,PI/2,2);
    lights();
 pushMatrix();
  //Cara azul
    fill(0,0,255);
    translate(width/2,height/2,tam+tam/2);
      spin+=0.01;
      rotateX(PI/10+spin);
      rotateY(PI/10+spin);
    box(tam/2,tam/2,tam/100);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,0);
            }
            else
            {
              fill(0,0,255);
            }
          }
        }
    translate(0,-51,0);
    box(tam/2,tam/2,tam/100);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,255,0);
            }
            else
            {
              fill(0,0,255);
            }
          }
        }
    translate(0,-51,0);
    box(tam/2,tam/2,tam/100);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(0,0,255);
            }
          }
        }
    translate(51,0,0);
    box(tam/2,tam/2,tam/100);
    
    fill(0,0,255);
    translate(0,51,0);
    box(tam/2,tam/2,tam/100);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,150,0);
            }
            else
            {
              fill(0,0,255);
            }
          }
        }
    translate(0,51,0);
    box(tam/2,tam/2,tam/100);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,255,0);
            }
            else
            {
              fill(0,0,255);
            }
          }
        }
    translate(51,-102,0);
    box(tam/2,tam/2,tam/100);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,150,0);
            }
            else
            {
              fill(0,0,255);
            }
          }
        }
    translate(0,51,0);
    box(tam/2,tam/2,tam/100);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(0,0,255);
            }
          }
        }
    translate(0,51,0);
    box(tam/2,tam/2,tam/100);
    
  //Cara amarilla
  fill(255,255,0);
  if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(25,-102,-26);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,0,0);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,0,0);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
     translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,0,255);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,-102,-51);
    box(tam/100,tam/2,tam/2);
    
    fill(255,255,0);
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);  
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,255,0);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,-102,-51);
    box(tam/100,tam/2,tam/2);
  
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,0,255);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,255,0);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    
  //Cara blanca
    fill(255,255,255);
    translate(-127,0,-25);
    box(tam/2,tam/2,tam/100);
    translate(0,-51,0);
    box(tam/2,tam/2,tam/100);
    translate(0,-51,0);
    box(tam/2,tam/2,tam/100);
    translate(51,0,0);
    box(tam/2,tam/2,tam/100);
    translate(0,51,0);
    box(tam/2,tam/2,tam/100);
    translate(0,51,0);
    box(tam/2,tam/2,tam/100);
    translate(51,-102,0);
    box(tam/2,tam/2,tam/100);
    translate(0,51,0);
    box(tam/2,tam/2,tam/100);
     translate(0,51,0);
    box(tam/2,tam/2,tam/100);
    
  //Cara verde
    fill(0,255,0);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(-126,-102,128);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,150,0);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,0);
            }
            else
            {
              fill(255,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,0,0);
            }
            else
            {
              fill(0,255,0);
            }
          }
        }
    translate(0,-102,-51);
    box(tam/100,tam/2,tam/2);
    
    fill(0,255,0);
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(0,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,150,0);
            }
            else
            {
              fill(0,255,0);
            }
          }
        }
    translate(0,-102,-51);
    box(tam/100,tam/2,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,0,255);
            }
            else
            {
              fill(0,255,0);
            }
          }
        }
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
    fill(0,255,0);
    translate(0,51,0);
    box(tam/100,tam/2,tam/2);
    
  //Quinta naranja
    fill(255,150,0);
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,0,0);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(126,-128,102);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,0,255);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,0,0);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(0,0,-51);
    box(tam/2,tam/100,tam/2);
    
    fill(255,150,0);
    translate(51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,0);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,0);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(0,0,-51);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,255);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,0,0);
            }
            else
            {
              fill(255,150,0);
            }
          }
        }
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
    
  //Quinta roja
    fill(255,0,0);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,150,0);
            }
            else
            {
              fill(255,0,0);
            }
          }
        }
    translate(103,153,102);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,255,0);
            }
            else
            {
              fill(255,0,0);
            }
          }
        }
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,0,255);
            }
            else
            {
              fill(255,0,0);
            }
          }
        }
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(255,255,0);
            }
            else
            {
              fill(255,0,0);
            }
          }
        }
    translate(0,0,-51);
    box(tam/2,tam/100,tam/2);
    
    fill(255,0,0);
    translate(51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,255,0);
            }
            else
            {
              fill(255,0,0);
            }
          }
        }
    translate(51,0,0);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,255,0);
            }
            else
            {
              fill(255,0,0);
            }
          }
        }
    translate(0,0,-51);
    box(tam/2,tam/100,tam/2);
    
    if (keyPressed)
      {
        if(key==CODED)
          {
            if(keyCode==UP)
            {
              fill(0,0,255);
            }
            else
            {
              fill(255,0,0);
            }
          }
        }
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
    
    fill(255,0,0);
    translate(-51,0,0);
    box(tam/2,tam/100,tam/2);
 popMatrix();
}
