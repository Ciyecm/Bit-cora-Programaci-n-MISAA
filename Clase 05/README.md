# Clase 05
```
int numerosLost[] = {4,8,15,16,23,42};

void setup() {
Serial.begin(9600);
Serial.println("empezamos ciclo for");
for(int i = 0; i <= 5; i++) {
Serial.println(numerosLost[i]);
delay(1000);
};
Serial.println("sali del ciclo for");
}

void loop() {

}

```
```

String lineasPoema[] = {
"Soy el jefe del mundo",
"Soy el mas alto del mundo",
"Soy el mas excelso del mundo",
"Esta es mi ultima encarnacion",
"Ya no hay renacimiento para mi",
};
void setup() {
  Serial.begin(9600);
}

void loop() {

Serial.println("empezamos ciclo for");
for(int i = 0; i <= 4; i++) {
Serial.println(lineasPoema[i]);
delay(1000);
};
Serial.println("sali del ciclo for");
}
```
