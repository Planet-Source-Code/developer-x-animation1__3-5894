<div align="center">

## animation1


</div>

### Description

it is just a simple but exquisite animation.
 
### More Info
 
it is made with help of ellipses,for and while loops.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[developer\_x](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/developer-x.md)
**Level**          |Advanced
**User Rating**    |3.6 (18 globes from 5 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__3-15.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/developer-x-animation1__3-5894/archive/master.zip)

### API Declarations

```
#include<iostream.h>
#include<conio.h>
#include<graphics.h>
#include<dos.h>
```


### Source Code

```
include<iostream.h>
#include<conio.h>
#include<graphics.h>
#include<dos.h>
void main()
{
int d=DETECT,m;
float j=0,k=0,x1=0,x2=559,y1=0,y2=479,i=0;
initgraph(&d,&m,"");
cleardevice();
while(!kbhit())
{
j=0;i=0;
for(i=0;i<113;i+=.5)
  {
  setcolor(15);
  ellipse(320,240,0,180,111-i,111+i);   //closing pearl
  ellipse(320,240,180,360,111+i,111-i);
  setcolor(2);
  ellipse(320,240,180,360,111-i,111+i);
  ellipse(320,240,0,180,111+i,111-i);
  delay(1);
  }
for(i=0;i<113;i+=.5)
  {
  setcolor(2);
  ellipse(320,240,0,180,111-i,111+i);   //closing pearl
  ellipse(320,240,180,360,111+i,111-i);
  setcolor(15);
  ellipse(320,240,0,180,111+i,111-i);
  ellipse(320,240,180,360,111-i,111+i);
  delay(1);
  }
}
getch();
}
```

