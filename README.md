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
# Olivia's History in Computing
<details open>
  <summary>September, 2017</summary>
  <br>
  I started my first comp sci course, AP Computer Science, at Rosemount High School. Through this course I learned the basics of Java.
   </details>

<details>
  <summary>March, 2018</summary>
  <br>
  I started working as an instructor at the Community Ed organization Girls Who Code!
  Here, I work with elementary school aged girls to help inspire a love of coding within them, as well as help them to become comfortable with Java logic.
  </details>
  
<details>
  <summary>April, 2018</summary>
  <br>
  Awarded "Certificate of Distinction" by the National Center of Women in Technology's Aspirations in Computing program.
   </details>
 <details>
  <summary>September, 2018</summary>
  <br>
  Started Advanced Computer Science, a dual-enrollment program through a local community college. In this course I was introduced to CSS, JavaScript, and HTML, and expanded on my knowledge of Java.
   </details>
 <details>
  <summary>October, 2018</summary>
  <br>
  Started my second term of Coding for Girls!
   </details>
 <details>
  <summary>November, 2018</summary>
  <br>
  Started this year's Hack Club as a Leader. Took initiative to reach out to all math classes, not just computer science classes, to encourage students who haven't had experience with coding to come and see if they like it! Presented to coputer science classes as well. Every week, I spend an hour with these new coders, engaging them in the excitement of code! 
   </details>
   
  #### If I've learned one thing during my time as a student of computer science, it's been adaptation. Since the field changes so quickly, I've gotten accoustumed to using all my resources to solve a problem in the most efficient way possible.

