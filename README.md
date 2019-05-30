# Welcome to my csPortfolio!
### Here you will find lots of code, all done by me, **_Olivia Alberts_**!
#### - Scroll to the bottom of the page for a brief history of my involvement with computer science.<br> - Scroll even lower for my portfolio reflection
___
> These various projects were part of my Advanced Computer Science class, a class focused on the use of **_data structures_**! The topics we've encountered so far include:
> - Chemotaxis
> - Arrays
> - Trees
> - Linked Lists
> - Maps
>
> We've also covered multiple languages over the course of the year! I primarily code in **_Java_** but have also learned to code in:
> - HTML
> - CSS
> - JavaScript
>
___
#### Below you'll find some of the projects I've done so far. My two favorites are the GradData project and the ClubsList project
Project! | Link!
---|---
Chemotaxis | [open here!](https://albertsofc.github.io/chemotaxis/index.html)
Christmas Card | [repo!](https://github.com/SamEriksenSchultz/ACS-Holiday-Card/tree/master)
 Dice | [open here!](https://albertsofc.github.io/dice3/)
 Lightning | [open here!](https://albertsofc.github.io/lightning2/)
 Starfield | [open here!](https://albertsofc.github.io/starfield5/)
 Webpage | [open here!](https://albertsofc.github.io/dogPage/dogPage3//)
 MovieReviews | [open here!] ()
 GradData | [open here!]()
 ClubsList | [open here!]()

 #### Here are some informative presentations I've done!
 College Presentation: University of Abertay | [open here](https://albertsofc.github.io/starfield5/college.html)
 Cybersecurity in China | [open here]

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
<details>
  <summary>September, 2017</summary>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I started my first comp sci course, AP Computer Science, at Rosemount High School. Through this course I learned the basics of Java.
  <br>
   </details>

<details>
  <summary>March, 2018</summary>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I started working as an instructor at the Community Ed organization Girls Who Code!<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Here, I work with elementary school aged girls to help inspire a love of coding within them, as well as help them to become comfortable with Java logic.
  <br>
  </details>
  
<details>
  <summary>April, 2018</summary>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Awarded "Certificate of Distinction" by the National Center of Women in Technology's Aspirations in Computing program.
  <br>
   </details>
 <details>
  <summary>September, 2018</summary>
 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Started Advanced Computer Science, a dual-enrollment program through a local community college. In this course I was introduced to CSS, JavaScript, and HTML, and expanded on my knowledge of Java.
  <br>
   </details>
 <details>
  <summary>October, 2018</summary>
 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Started my second term of Coding for Girls!
  <br>
   </details>
 <details>
  <summary>November, 2018</summary>
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Started this year's Hack Club as a Leader. Took initiative to reach out to all math classes, not just computer science classes, to encourage students who haven't had experience with coding to come and see if they like it! Presented to coputer science classes as well. Every week, I spend an hour with these new coders, engaging them in the excitement of code! 
  <br>
   </details>
   
  #### If I've learned one thing during my time as a student of computer science, it's been adaptation. Since the field changes so quickly, I've gotten accoustumed to using all my resources to solve a problem in the most efficient way possible.
  
  ___
  
 # Portfolio Reflection
 #### Reflect on your portfolio projects
 >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I'm proud of my portfolio projects. They show an array (no pun intended) of the things I've learned this year, as well as the creativity I add into my code. I enjoy the design aspect of code, and I think my portfolio projects display this. My favorite project was probably my Starfield, but I also enjoyed designing the website and working with random timing with Lightning.
#### What is one or two things that are a source of pride in your programming development?
 >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;One source of pride for me was the design flair I added into my projects; I think they're all not only aesthetically pleasing, but interesting to look at, and that's important to me. I'm also proud of my progress in using arrays and mouseX and mouseY.
#### Expand on the pieces of pride
 >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I really enjoyed working with random RGB generators and I enjoyed limiting the parameters in which they could randomly generate so I got aesthetic outcomes (I think this is best shown with my particles in Starfield. This piece of code is shown above). I learned about arrays by repeated trials and learning from my classmates. I've learned of this important and efficient way to categorize and use code.
#### Identify the most significant hurdle you overcame this trimester
 >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I think the most significant hurdle I overcame this trimester was just becoming comfortable with learning how to write different classes and have a reliable output. Learning arrays really helped me as well. Though these hurdles are pretty run-of-the-mill, my strong foundation in them will help me for the rest of my coding experience. I've also gotten the opportunity to work with trigonometric functions, and even though that's still a work in progress (cue my original chemotaxis), working really hard on that taught me a lot about how a computer processes data.
 #### Describe the development process of your code
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;First, I always start with an idea. This is in the parameters of the code, but seldom do I start by actually writing the code. This is where I like to get creative, and where I do my research as to how I can accomplish my goals. This always includes lots and lots of time using the whiteboard right behind my workstation. For example, I spent probably a week just sketching out ways to make my plant stem move based on my mouse position, trying, testing, then going back to the drawing board. This is the second part of my development process; testing and experimenting with different methods. Then, I think about how I can complete code efficiently; what loops will I need, what arrays will I need, etc., and then I start setting up the skeleton of the code. Finally, I fill in the skeleton as I had originally planned, and keep modifying it until I get the result I'm looking for.<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This process is primarily independent. When I'm experimenting, however, I'll ask people around me if they've ever done anything like what I'm trying to do, and if they have I'll ask them how they did it. I also get lots of my ideas collaboratively, via inspiration from other people in my class, as well as code I see in the world.
