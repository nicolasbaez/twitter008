## twitter008 | #つぶやきProcessing 
https://twitter.com/nicolasbaez/status/1253846890065670146?s=20

![twitter](https://github.com/nicolasbaez/twitter008/blob/master/twitter008.gif)
```processing
void setup(){size(512,256,P3D);}float t(float r){return radians(r);}float d,y,j,i=0;void draw(){clear();translate(256,128);rotateY(t(y));for(j=0;j<360;j+=24){rotateX(t(j));for(i=0;i<360;i+=15){text(char(int(i+j)),64*cos(t(i+d)),64*sin(t(i)));}d+=0.1;}y+=0.5;}
```
