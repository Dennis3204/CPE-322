#CPE 322 - Lab 3

## Instructions 
Install required Python packages such as jdcal, astral, and geopy. Execute the following code: <br>
`cd ~/iot`, `cd *3`, `python3 julian.py`, `python3 date_example.py`, `python3 datetime_example.py`, `python3 time_example.py`, `python3 sun.py "New York"`, `python3 moon.py`, `python3 coordinates.py "Samuel C. Williams Library"`, `python3 address.py "40.74480675, -74.02532861159351"`, `python3 cpu.py`, `python3 battery.py`, `python3 documentstats.py document.txt`.
<br><br>  Document the results to your GitHub repository.

---

## Installing Python Packages

Install required python packages. 
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/install.png)

## cd ~/iot and ## cd *3

Go to Lab directory
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/cdLab3.png)

---

## Python Scripts
`python3 julian.py`<br>
Displays the current date in Julian format, which is useful in astronomical applications and date tracking for embedded systems.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/julian.py.png)

`python3 date_example.py`<br>
Prints today`s date and shows how to extract day, month, and year individually using Python’s datetime.date module.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/dateExample.png)

`python3 datetime_example.py` <br>
Demonstrates the use of the datetime.datetime class to show full timestamps and explain the difference between date and datetime objects.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/dateTimeExample.png)

`python3 time_example.py`<br>
Illustrates how to measure elapsed time using the time module, which is essential for benchmarking and delay management in scripts.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/timeExample.png)

`python3 sun.py "New York"`<br>
Uses the astral package to compute sunrise and sunset times for the specified city. Helps demonstrate time-based location data processing.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/sun.py.png)

`python3 moon.py`<br>
Calculates moon phases using the astral module, showing how astronomical data can be obtained through Python scripting.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/moon.py.png)

`python3 coordinates.py "Samuel C. Williams Library"`<br>
Retrieves latitude and longitude coordinates for a given location name using geopy. Shows reverse geocoding functionality.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/coordinates.py.png)

`python3 address.py "40.74480675, -74.02532861159351"`<br>
Takes latitude and longitude as input and returns a readable address, using forward geocoding with the geopy library.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/address.py.png)

`python3 cpu.py`<br>
Displays current CPU usage by percentage. Useful for understanding resource utilization in embedded systems or Raspberry Pi devices.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/cpu.py.png)

`python3 battery.py`<br>
Reports current battery status, including charge level and power source, using the psutil library. Helps monitor system power state.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/battery.py.png)

`python3 documentstats.py document.txt`<br>
Analyzes a given text file (document.txt) and outputs statistics such as line count, word count, and character count.
![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%203/documentStats.py.png)

--- 
## Summary

In this lab, I learned how to run python files in command prompt as well as some commands from the jdcal, astral, and geopy libraries.

