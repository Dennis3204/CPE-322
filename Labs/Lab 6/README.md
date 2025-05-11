# CPE 322 - Lab 6 Node.js and Pystache
## Instructions

- Go to the GitHub repository Lesson 6
- Install Node.js and run hello-world.js, hello.js, and http.js
  - Refresh the webpage to see server activities
- Install Pystache and run say_hello.py that uses the template in say_hello.mustache


--- 
## Node.Js

I already had Node.js, so I didn't have to install it. Here are the commands I used to run the scripts:

- `cd ~/iot/lesson6`
- `node hello-world.js`
- `node hello.js` 
- `node http.js `

![](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%206/node.png)


These are the results of running the scrips:

![hello-world.js:](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%206/hello-world.png)
![hello.js:](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%206/hello1.png)
![http.js:](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%206/http.png)

Each script demonstrated distinct server behavior upon interacting with its corresponding webpage. The `http.js` script kept a running count of how many times the page was refreshed, updating the count with each request. The `hello.js` script logged "response end call done" and "request end event fired" to the terminal every time the page was reloaded. In contrast, `hello-world.js` did not produce any visible server output or terminal activity when accesse

---
## Pystache:
After I downloaded pystache using the `pip3 install pystache` command, I ran some files using these commands: 

- `cat say_hello.mustache`
- `cat say_hello.py`
- `python3 say_hello.py`

Here are the result of those commands:
![http.js:](https://github.com/Dennis3204/CPE-322/blob/main/Labs/Lab%206/pystache.png)

---

## Summary
In this lab, I learned the basics of using Node.js to run webpages and how to run Pystache.
