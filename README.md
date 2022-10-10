# Codigos-programacion-Holman
Programacion profe 

void setup() {
Serial.begin(9600);  }

void loop() { 

if(Serial.available() != 0) {
  char texto = Serial.read();
  Serial.print( texto);
  delay (200);
}
}
