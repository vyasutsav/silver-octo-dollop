#include<stdio.h>
#include<conio.h>
#include<graphics.h>
#include<dos.h>
main()
{
int gdetect,gm,x,y,color,angle=0;
struct arccoordstype a,b;
initgraph(&gd,&gm,"C:\\TC\\BGI");
delay(2000);
while(angle<=360)
{
setcolor(black);
arc(getmaxx()/2,getmaxy()/2,angle,angle+2,100);
setcolor(RED);
getarccoords(&a);
circle(a.xstart,a.ystart,25);
setcolor(black);
arc(getmax()/2,getmaxy()/2,angle,angle+2,150);
getarccoords(&2);
set color(BLACK);
      arc(getmaxx()/2,getmaxy()/2,angle,angle+2,150);
      getarccoords(&a);
      setcolor(GREEN);
      circle(a.xstart,a.ystart,25);
      angle = angle+5;
      delay(50);
   }
 
   getch();
   closegraph();
   return 0;
}

NOTE:Kindly write this code one after the another line it will be very easy to use and tell me the errors if it's there.Your errors will be removed shortly.
