# basic-digital-clock.py
# A simple 12-hour digital clock in Python using for loop and user input.

import time
C = int(input("Kitne second tak clock chalani hai? "))
for i in range(C):
    current_time = time.strftime("%I:%M:%S %p")
    print(current_time)
    time.sleep(1)
print("Clock band ho gayi!!!")

# Agar input time se pahle clock ko rokna hai to Terminal me click karke (Ctrl + C) karenge to clock ruk jayegiii
 
