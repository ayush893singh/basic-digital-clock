## Simple Python Clock (Second-Based)
A simple Python program that displays a live clock in the console for a specified number of seconds.

## Technologies Used
Python 3 – Programming language
time module – To get the current time and control the clock intervals

## How it Works
The program asks the user for the number of seconds the clock should run.
It uses a for loop to run the clock for the specified seconds.
Inside the loop, it fetches the current time using time.strftime("%I:%M:%S %p").
Prints the current time every second using time.sleep(1).
After the loop ends, it prints a message that the clock has stopped.

## Note: This clock runs in seconds only, not minutes or hours.

## Code
```
import time
C = int(input("Kitne second tak clock chalani hai : "))
for i in range(C):
    current_time = time.strftime("%I:%M:%S %p")
    print(current_time)
    time.sleep(1)
print("Clock band ho gayi!!!")
```

## Output
```
Kitne second tak clock chalani hai? 5
10:30:15 AM
10:30:16 AM
10:30:17 AM
10:30:18 AM
10:30:19 AM
Clock band ho gayi!!!
```

## Author
Ayush Singh https://github.com/ayush893singh
