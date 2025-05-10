# CPE 322 - Lab 5

## Instructions 

- Go to the GitHub repository for Lesson 5
- Install Paho-MQTT using `pip3 install paho-mqtt`
- Change directory to the `iot` repository
- Update the repository using `git pull`
- Change directory to the `Lesson 5` folder
- Run `python3 subcpu.py` in one terminal window
- Run `python3 pubcpu.py` in another terminal window

---

## What I did

After installing the necessary package (paho-mqtt) and updating my local repository with git pull, I navigated to the Lesson 5 directory. I then ran subcpu.py in one terminal to act as the subscriber, and pubcpu.py in another terminal to continuously publish simulated CPU usage values. The subscriber terminal successfully received and displayed the CPU usage data in real time.

![Screenshot: ](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%205/CPE322Lab5.png)


## Summary
In this lab, I learned another way to use terminal/commmand prompt. I didn't know that you could use paho-mqtt to have one terminal subscribe to another. I was glad to learn this today!
