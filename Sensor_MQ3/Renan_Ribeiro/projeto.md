## Tarefa: prototipar a detecção de etanol
### Esquema montado no Tinkercad
![image](https://github.com/laciq/Tarefas/blob/main/Sensor_MQ3/Igor_Golcalves/Arduino%20da%20aula%20de%20ic.png)
---
### Código C
// C++ code
//
void setup()
{
  pinMode(A5, INPUT);
  pinMode(5, OUTPUT);
  pinMode(0, OUTPUT);
}

void loop()
{
  if (analogRead(A5) > 500) {
    digitalWrite(5, HIGH);
    digitalWrite(0, HIGH);
  } else {
    digitalWrite(5, LOW);
  }
  delay(10); // Delay a little bit to improve simulation performance
}

---
### Link do Tinkercad 
https://www.tinkercad.com/things/k2HtmyGKJja

