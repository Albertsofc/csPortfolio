# Welcome to my csPortfolio!
### Here you will find lots of code, all done by me, **_Olivia Alberts_**!
### Scroll to the bottom of the page for a breif history of my involvement with computer sceince.
> These various projects were part of my Advanced Computer Science class, a class focused on the use of **_data structures_**! The topics we've encountered so far include:
> - Chemotaxis
> - Arrays
> - CSS
> - HTML
>


* WebPage [here](https://albertsofc.github.io/dogPage/dogPage3//)
* Lightning [here](https://albertsofc.github.io/lightning2/)
* Dice [here](https://albertsofc.github.io/dice3/)
* Starfield [here](https://albertsofc.github.io/starfield5/)

___

#### This is the most interesting code I've written so far, found in my "Starfield" lab. It makes a glitter-type particle (a star, in this case), and can easily be instantiated into an array. In my Starfield lab, I have around 400 of these guys.
```Java
class NormalParticle implements Particle {
  double x, y, speed, angle;
  NormalParticle() {
    x=width/2;
    y=height/2;
    speed=(Math.random()*4)+1;
    angle=(Math.random()*(Math.PI*4));
  }
  void show() {
    noStroke();
    fill(255, (float)((Math.random()*69)+171), (float)(Math.random()*230));
    ellipse((int)x, (int)y, (int)(Math.random()*8), (int)(Math.random()*8));
  }
  void move() {
    x+=Math.cos(angle)*speed;
    y+=Math.sin(angle)*speed;
    angle+=0.025;
  }
}
```
___
### Olivia's History in Computing
> September, 2017
