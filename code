// Define to which pin of the Arduino the output of the LM35 is connected:
#define sensorPin A0

void setup() {
  // Begin serial communication at a baud rate of 9600:
  Serial.begin(9600);
}

void loop() {
  // Get a reading from the temperature sensor:
  float var = analogRead(A0);
  
  // Convert the reading into voltage:
  float a = (var/3500 )*100;

  Serial.println(a);

  delay(1000); // wait a second between readings
}
