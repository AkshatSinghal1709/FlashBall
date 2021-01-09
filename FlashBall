#include <graphics.h>
#include<process.h>
#include<iostream>
#include<dos.h>
#include<stdio.h>
#include<conio.h>
#include<cmath>
using namespace std;
bool checkcoll(double x1,double y1,double x2,double y2,double i,double j,double r){
    if(i>x1-r && i<x2+r && j>y1-r && j<y2+r ){
        return 1;

    }

return 0;

}

bool  linecollx(double x1,double y1,double x2,double y2,double i,double j){
    if(i>x1-4 && i<x2+4){
        if(j>=(y1-4) && j<(y1+5)){
            return 1;
        }


    }
    return 0;


}



bool linecoll(double x1,double y1,double x2,double y2,double i,double j){
    if(j>y1-4 && j<y2+4){
        if(i>=(x1-4) && i<(x1+5)){
            return 1;
        }

    }
return 0;

}

int main(){
double i=5,j=100,x=0,y=0,k,q,ch,gd=DETECT,gm;
double i2=700,j2=400,t=2,m;
initwindow(1500,1500);
 while(1){
    settextstyle(8,4,8);
    setcolor(14);
    outtextxy(500 ,500,"FLASH BALL");
    settextstyle(8,4,5);
    outtextxy(800 ,600,"press 1 to continue");
    rectangle(600,300,800,500);
    outtextxy(800 ,700,"press 2 to read rules");
    rectangle(600,300,800,500);

    setfillstyle(SOLID_FILL,GREEN);
        circle(i2,j2,10);
        floodfill(i2,j2,14);
        if(j2<310){
            t=2;
        }
        if(j2>490){
            t=-2;
        }


        j2=j2+t;
        delay(20);
cleardevice();

        if(kbhit()){
                m=getch();
        if(m==49){
            break;
        }
        if(m==50){cleardevice();
             settextstyle(8,4,6);
    setcolor(14);
    outtextxy(400 ,200,"How to Play");
     settextstyle(8,4,4);
     setcolor(GREEN);
     delay(1000);
    outtextxy(700 ,300,"Use control keys to move the ball");
    setcolor(3);
     settextstyle(8,4,4);
     delay(1000);
    outtextxy(500 ,400,"A for moving ball left");
    delay(1000);
    outtextxy(450 ,500,"W for moving ball up");
    delay(1000);
    outtextxy(490 ,600,"S for moving ball down");
    delay(1000);
     outtextxy(500 ,700,"D for moving ball right");
     delay(1000);
      outtextxy(1200 ,500,"press any key to cont..");
     getch();
     cleardevice();
     settextstyle(8,4,4);
    setcolor(GREEN);
    outtextxy(970 ,200,"Your goal is to get the ball to the final point");
    delay(2000);
    outtextxy(750 ,300,"Without hitting the BLOCKS and LINES");
    delay(2000);
    outtextxy(700 ,400,"Which will appear in yellow colour");
    delay(2000);
    outtextxy(1150 ,500,"The LINES appearing in BLUE colour will rebound the ball");
    delay(2000);
    outtextxy(550 ,600,"If you hit them GAME OVER");
    delay(2000);
    outtextxy(950 ,700,"If you cross 1st LEVEL ,2nd LEVEL will be there");
    delay(2000);
     outtextxy(500 ,800,"press any key to cont..");
    getch();
    cleardevice();
     setcolor(14);
     settextstyle(8,4,7);
    outtextxy(1200 ,500," ENJOY THE GAME FLASH BALL!!");
    delay(1000);
    setcolor(3);
    settextstyle(8,4,5);
     outtextxy(800 ,700,"press any key to escape");


    getch();
        }

        }




   }






while(1){

setcolor(3);
        line(0,60,800,60);
        line(0,220,600,220);
        line(600,220,600,500);
        line(800,60,800,700);
        line(600,500,0,500);
        line(800,700,0,700);
        setcolor(14);
        line(600,250,750,250);//h
        line(650,500,800,500);//h
        line(700,250,700,450);
        line(750,300,750,500);
        line(650,300,650,500);

        rectangle(540,60,610,180);

        rectangle(650,110,800,150);

        rectangle(670,590,800,650);//3

        rectangle(530,650,600,700);

        //5
        rectangle(420,500,480,620);


rectangle(420,650,480,700);

line(530,560,530,610);//3

line(600,560,600,610);//1
line(565,590,565,650);//2
rectangle(270,530,340,580);

rectangle(320,580,380,700);

rectangle(210,590,320,650);

rectangle(0,500,100,600);

        //11
rectangle(0,630,100,700);


rectangle(100,640,180,700);

        //13
rectangle(100,500,180,560);

        rectangle(60,60,128,148);

rectangle(160,120,220,220);

      rectangle(244,80,320,120);


rectangle(296,140,352,220);


rectangle(372,112,408,220);

rectangle(440,60,480,112);

rectangle(440,140,480,220);


rectangle(530,500,600,560);



        setcolor(YELLOW);
        setfillstyle(SOLID_FILL,CYAN);
        circle(i,j,4);
        floodfill(i,j,14);


if(kbhit()){

        ch=getch();
if(ch==119){
    x=0;
    y=-2;
}
else if(ch==97){

    x=-2;
    y=0;
}
else if(ch==100){

    x=2;
    y=0;
}
else if(ch==115){
    x=0;
    y=2;
}
else exit(0);




}

i=i+x;
j=j+y;
if(i<4 && j<500){
    x=2;
    y=0;
}

if(j<64){
    x=0;
    y=2;
}if(j<300){
if(j>216 && i<600){
    x=0;
    y=-2;
}
}
if(i>796){
    x=-2;
    y=0;
}
if(i>600 && i<604 && j>216 && j<610){
    x=2;
    y=0;
}if(j>500){
if(j<504 && i<600){
    x=0;
    y=2;
}
}
if(j>696){
    x=0;
    y=-2;
}
if(linecoll(565,590,565,650,i,j)==1){
break;
   }
   if(linecoll(700,250,700,450,i,j)==1){
break;
   }
if(linecoll(750,300,750,500,i,j)==1){
break;
   }
if(linecoll(650,300,650,500,i,j)==1){
break;
   }
   if(linecoll(600,560,600,610,i,j)==1){
break;
   }
   if(linecollx(600,250,750,250,i,j)==1){
break;
   }
   if(linecollx(650,500,800,500,i,j)==1){
break;
   }
if(linecoll(530,560,530,610,i,j)==1){
    break;
}

if(i>54 && i<132 && j<152 ){
 break;}

if(i>156 && i<224 && j>116 && j<224){
        break;}
if(checkcoll(244,80,320,120,i,j,4)==1){
            break;
        }
          if(checkcoll(296,140,352,220,i,j,4)==1){

            break;
        }
          if(checkcoll(372,112,408,220,i,j,4)==1){
            break;
        }
          if(checkcoll(440,60,480,112,i,j,4)==1){

            break;
        }
if(checkcoll(440,140,480,220,i,j,4)==1){
break;
        }
        if(checkcoll(540,60,610,180,i,j,4)==1){
break;
        }
        if(checkcoll(650,110,800,150,i,j,4)==1){
            break;
        }
        if(checkcoll(670,590,800,650,i,j,4)==1){//3
break;
        }
        if(checkcoll(530,500,600,560,i,j,4)==1){
break;
        }
        if(checkcoll(530,650,600,700,i,j,4)==1){ //5
 break;
        }
        if(checkcoll(420,500,480,620,i,j,4)==1){

            break;
        }
        if(checkcoll(420,650,480,700,i,j,4)==1){
                break;
        }
        if(checkcoll(270,530,340,580,i,j,4)==1){

            break;
        }
        if(checkcoll(320,580,380,700,i,j,4)==1){//9

            break;
        }
        if(checkcoll(210,590,320,650,i,j,4)==1){

            break;
        }
        if(checkcoll(0,500,100,600,i,j,4)==1){ //11

            break;
        }
        if(checkcoll(0,630,100,700,i,j,4)==1){

            break;
        }
        if(checkcoll(100,640,180,700,i,j,4)==1){ //13

            break;
        }
        if(checkcoll(100,500,180,560,i,j,4)==1){

            break;
        }

        if(i<4 && j>500){

            break;
        }

delay(10);


cleardevice();

}if(i<4){


settextstyle(4,4,4);
setbkcolor(RED);
outtextxy(500,500,"CONGRATULATIONS");
delay(1000);
cleardevice();
setbkcolor(RED);
outtextxy(500,500,"YOU HAVE WON ");
delay(500);

outtextxy(1000,700,"PRESS KEY TO MOVE TO NEXT LEVEL  ");
getch();
cleardevice();
double i1=150,j1=100,p=0,q=0,c,gd=DETECT,gm,x1=50,x2=100,x3=650,x4=700,y1=450,y2=500,y3=550,y4=600,h ,h1,h2,y5=450,y6=500,y7=550,y8=600;
initwindow(1500,1500);



while(1){
setcolor(14);
        line(50,300,220,300);//1
        line(50,400,220,400);
        line(650,300,820,300);//3
        line(650,400,820,400);
        line(680,350,850,350);//5
        line(80,350,250,350);
        setcolor(3);
        rectangle(250,0,650,450);
        rectangle(50,0,850,600);
        setcolor(14);
        rectangle(80,470,220,570);//1
        rectangle(680,470,820,570);
        rectangle(50,0,140,100);//3
        rectangle(160,0,250,100);
        rectangle(650,00,740,100);//5
		rectangle(760,0,850,100);
		 line(450,490,450,560);//7

		rectangle(x1,120,x2,200);//7
		rectangle(x3,120,x4,200);////


		rectangle(80,230,250,270);//9
		rectangle(680,230,850,270);
		rectangle(360,y1,430,y2);//11 left upperone
        rectangle(360,y3,430,y4);// left downside rectangle
		rectangle(470,y5,540,y6);//13
        rectangle(470,y7,540,y8);

		rectangle(270,450,330,500);//15
		rectangle(570,450,630,500);



        setcolor(14);
        setfillstyle(SOLID_FILL,RED);
        circle(i1,j1,4);
        floodfill(i1,j1,14);

if(kbhit()){

        c=getch();
if(c==119){
    p=0;
    q=-2;
}
else if(c==97){

    p=-2;
    q=0;
}
else if(c==100){

    p=2;
    q=0;
}
else if(c==115){
    p=0;
    q=2;
}
else exit(0);




}

i1=i1+p;
j1=j1+q;
if(i1<54){
    p=2;
    q=0;
}
if(j1>596){
    p=0;
    q=-2;
}
if(i1>846){
    p=-2;
    q=0;
}
if(i1<300){
if(i1>246 && j1<454){
    p=-2;
    q=0;
}
}
if(j1>450 && j1<454 && i1>250 && i1<650){
    p=0;
    q=2;
}
if(i1>650){
    if(i1<654 && j1<450){
        p=2;
        q=0;
    }
}
if(checkcoll(50,0,140,100,i1,j1,4)==1){//1

            break;
        }
        if(checkcoll(160,0,250,100,i1,j1,4)==1){

            break;
        }
        if(checkcoll(80,470,220,570,i1,j1,4)==1){//3

            break;
        }
        if(checkcoll(680,470,820,570,i1,j1,4)==1){


            break;
        }
        if(checkcoll(650,00,740,100,i1,j1,4)==1){//5


            break;
        }
        if(checkcoll(760,0,850,100,i1,j1,4)==1){

            break;
        }
        if(checkcoll(x1,120,x2,200,i1,j1,4)==1){//7

            break;
        }
        if(checkcoll(x3,120,x4,200,i1,j1,4)==1){

            break;
        }
        if(checkcoll(80,230,250,270,i1,j1,4)==1){//9

            break;
        }
        if(checkcoll(680,230,850,270,i1,j1,4)==1){
            break;
        }
if(checkcoll(360,y1,430,y2,i1,j1,4)==1){//11

            break;
        }
if(checkcoll(360,y3,430,y4,i1,j1,4)==1){

            break;
        }
if(checkcoll(470,y5,540,y6,i1,j1,4)==1){//13
            break;
        }
if(checkcoll(470,y7,540,y8,i1,j1,4)==1){


            break;
        }
        if(checkcoll(270,450,330,500,i1,j1,4)==1){//15

            break;
        }
        if(checkcoll(570,450,630,500,i1,j1,4)==1){

            break;
        }
        if(linecollx(50,300,220,300,i1,j1)==1){//1
    break;
}

if(linecollx(50,400,220,400,i1,j1)==1){
    break;
}

if(linecollx(650,300,820,300,i1,j1)==1){//3
    break;
}

if(linecollx(650,400,820,400,i1,j1)==1){
    break;
}

if(linecollx(680,350,850,350,i1,j1)==1){//5
    break;
}

if(linecollx(80,350,250,350,i1,j1)==1){
    break;
}

if(linecoll(450,490,450,560,i1,j1)==1){
    break;
}
if(x2==100){
    h=1;
}
if(x1==200){
    h=-1;
}
x1=x1+h;
x2=x2+h;
if(x4==700){
    h=1;
}
if(x3==800){
    h=-1;
}
x3=x3+h;
x4=x4+h;
if(y5==450){
    h1=0.5;
}
if(y6==525){
    h1=-0.5;
}
y5=y5+h1;
y6=y6+h1;
y1=y1+h1;
y2=y2+h1;
if(y7==525){
    h2=0.5;
}
if(y8==600){
    h2=-0.5;
}
y7=y7+h2;
y8=y8+h2;
y3=y3+h2;
y4=y4+h2;

if(j1<=4  && i1>650){
    break;
}


delay(10);
cleardevice();
}
if(j1<=4 && i1>650){
        settextstyle(4,4,4);
setbkcolor(RED);
outtextxy(700,200,"CONGRATULATIONS");
delay(1000);
cleardevice();
setcolor(14);
settextstyle(8,4,8);
outtextxy(1000,500,"YOU HAVE WON ");
delay(500);

outtextxy(1200,700,"ALL LEVEL COMPLETED  ");
getch();
}
else{

        settextstyle(4,4,4);
setbkcolor(RED);
outtextxy(600,300,"GAME OVER ");
delay(1000);
outtextxy(800,400,"TO EXIT PRESS KEY");
getch();
cleardevice();


}
}

else {
        settextstyle(4,4,4);
setbkcolor(RED);
outtextxy(500,400,"GAME OVER ");
delay(500);
outtextxy(700,600,"TO EXIT PRESS KEY");
getch();
cleardevice();



}

}

