[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/OJLySING)
# Stepper-Motor
Repo for students learning to interface and code for rotating a Stepper Motor

from machine import pin
import time

in1 = Pin(2, Pin.OUT)
in2 = Pin(4, Pin.OUT)
in3 = Pin(5, Pin.OUT)
in4 = Pin(18, Pin.OUT)

while True:

in1.value(1)
in2.value(0)
in3.value(0)
in4.value(0)
time.sleep_ms(3)

in1.value(0)
in2.value(1)
in3.value(0)
in4.value(0)
time.sleep_ms(3)

in1.value(0)
in2.value(0)
in3.value(1)
in4.value(0)
time.sleep_ms(3)

in1.value(0)
in2.value(0)
in3.value(0)
in4.value(1)
