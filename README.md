# Handbook_Arduino

LED
- Longer head = Anode = connect to positive side
- Shorter head = Cathode = connect to the ground / negative side.


## Blink

```bash
/*
Arduino UNO, on-board LED (LED_BUILTIN) attached to pin 13
*/

void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);                      // wait for a second
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
```

