#define led_FLASH 4

void setup() {
  pinMode(led_FLASH, OUTPUT);
}

void loop() {
  digitalWrite(led_FLASH, LOW); 
  delay (1000); 
  digitalWrite(led_FLASH, HIGH); 
  delay (1000); 
}