<h3>PINMODE :</h3>

    - pinMode, pinin girişmi çıkışmı olduğunu ayarlamamızı sağlar.
  
    - pinMode(pin, mode) iki değer alır biri pin numarası, diğeri INPUT (Giriş) veya OUTPUT (Çıkış) parametreleri.
1. Örnek

pinMode(pin, OUTPUT);
  
2. Örnek

pinMode(pin, INPUT);

<h3>DIGITALWRITE :</h3>
  
    - digitalWrite, ayarlanan pine 1 veya 0 yani açık veya kapalı şeklinde değer yollar bu da pinin açılmasını veya kapanmasını sağlar.
  
    - digitalWrite(pin, value) iki değer alır biri pin numarası, diğeri HIGH-0 (Yüksek) ve LOW-1 (Düşük) parametreleri.
  
1. Örnek

digitalWrite(pin, HIGH);
  
2. Örnek
  
digitalWrite(pin, LOW);
<h3>DIGITALREAD :</h3>

    - digitalRead, pinin durumunu sorgular ve geriye HIGH (Yüksek) veya LOW (Düşük) döndürür.
  
    - digitalRead(pin) tek değer alır o da pin numarası'dır. 
  
1. Örnek
  
int x = digitalRead(pin);
  
2. Örnek
  
if(digitalRead(pin) == HIGH) digitalWrite(pin, LOW);
<h3>DELAY :</h3>

    - delay, programı belirli bir süre çerçevesinde duraksatmak, geciktirmek için kullanılır.
  
    - delay() milisaniye cinsinden tek parametre alır. 1000 milisaniye = 1 saniye.
  
1. Örnek
  
delay(1000);
