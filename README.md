# LED
- Hijau = Pin 10
- Kuning = Pin 9
- Merah = Pin 8

```c
// Deklarasi pin LED
int ledMerah = 8;    // Pin untuk LED merah
int ledKuning = 9;   // Pin untuk LED kuning
int ledHijau = 10;   // Pin untuk LED hijau

void setup() {
  // Atur semua pin sebagai output
  pinMode(ledMerah, OUTPUT);
  pinMode(ledKuning, OUTPUT);
  pinMode(ledHijau, OUTPUT);
}

void loop() {
  // LED Merah menyala selama 2 detik
  digitalWrite(ledMerah, HIGH);  // LED merah ON
  delay(2000);                   // Tunggu 2 detik
  digitalWrite(ledMerah, LOW);   // LED merah OFF

  // LED Kuning menyala selama 2 detik
  digitalWrite(ledKuning, HIGH); // LED kuning ON
  delay(2000);                   // Tunggu 2 detik
  digitalWrite(ledKuning, LOW);  // LED kuning OFF

  // LED Hijau menyala selama 2 detik
  digitalWrite(ledHijau, HIGH);  // LED hijau ON
  delay(2000);                   // Tunggu 2 detik
  digitalWrite(ledHijau, LOW);   // LED hijau OFF
}

```
