```
int ledPin = 13;  
int Tp = 200;
int Tr = 400;
int Ts = 50;
int Tfc = 100;
int Te = 300;
void setup(){
  pinMode(ledPin,OUTPUT);
}
void loop(){
e();
n();
delay(Te);
e();
l();
delay(Te);
c();
i();
e();
l();
o();
delay(Te);
y();
delay(Te);
e();
n();
delay(Te);
l();
a();
delay(Te);
t();
i();
e();
r();
r();
a();
coma();
delay(Te);
s();
o();
y();
delay(Te);
e();
l();
delay(Te);
u();
n();
i();
c();
o();
delay(Te);
h();
o();
n();
r();
r();
a();
d();
o();
delay(Te);
}
void e(){
punto();
delay(Tfc);
}
void n(){
raya();
punto();
delay(Tfc);
}
void l(){
punto();
raya();
punto();
punto();
delay(Tfc);
}
void c(){
raya();
punto();
raya();
punto();
delay(Tfc);
}
void i(){
punto();
punto();
delay(Tfc);
}
void o(){
raya();
raya();
raya();
delay(Tfc);
}
void y(){
raya();
punto();
raya();
raya();
delay(Tfc);
}
void a(){
punto();
raya();
delay(Tfc);
}
void t(){
raya();
delay(Tfc);
}
void r(){
punto();
raya();
punto();
delay(Tfc);
}
void coma(){
raya();
raya();
punto();
punto();
raya();
raya();
delay(Tfc);
}
void s(){
punto();
punto();
punto();
delay(Tfc);
}
void u(){
punto();
punto();
raya();
delay(Tfc);
}
void h(){
punto();
punto();
punto();
punto();
delay(Tfc);
}
void d(){
raya();
punto();
punto();
delay(Tfc);
}
void punto(){

    digitalWrite(ledPin,HIGH);
    delay(Tp);
    digitalWrite(ledPin,LOW);
    delay(Ts);
}
void raya(){

    digitalWrite(ledPin,HIGH);
    delay(Tr);
    digitalWrite(ledPin,LOW);
    delay(Ts);
}
```
