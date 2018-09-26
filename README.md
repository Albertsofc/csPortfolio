# csPortfolio

* WebPage [here](https://albertsofc.github.io/lightning2/)
* Lightning [here(https://albertsofc.github.io/lightning2/)

```Java
 while (endX<550) {
    endX=startX+((int)(Math.random()*10));
    endY=startY+(int)(Math.random()*19)-9;
    line(startY, startX, endY, endX);
    startX=endX;
    startY=endY;
    println("startX"+startX);
    println("endX"+endX);
    println();
  }
  if (millis()-timer>=((int)(Math.random()*1250)+250)){
    background(bg);
    //startX=(int)(Math.random()*(-500))+1;
    startX=0;
    startY=(int)(Math.random()*500);
    //endX=(int)(Math.random()*500);'
    endX=160;
    endY=250;
    timer=millis();
  }

```
