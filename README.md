# 🚀ROS 2 TASKS – 2

---

## I) 🐢TurtleSim

1. Create a ROS node to control the turtlesim bot  
   *(Move, Rotate, Go to goal)*

2. Write a script to draw the letter **D** using the turtle bot.

3. Write a script to implement a **service client** to draw a polygon with
   the number of sides requested by the client.

---

## II) 🔁Publisher–Subscriber

Create a **chatting application** where you can send and receive text typed
inside the terminal from one ROS node to another and vice versa.

- Use **ROS 2 Publisher–Subscriber**
- Implement using **C++**
- You should be able to send **multiple messages** without waiting for a reply

---

## III) 📨Custom Messages

Design and implement a **ROS 2–based temperature monitoring system** where:

- One node simulates data from a real temperature sensor, published using a
  **custom ROS 2 message**
- Another node subscribes to the data and continuously logs the
  **current temperature** and the **maximum safe temperature** using `INFO` logs.
- Whenever the temperature crosses the defined safe limit
  (`temperature > max_safe_temperature`), the subscriber should additionally
  log a `WARN` message indicating an **over-temperature condition**.


    ### Custom Message Format
    
    ```bash
    builtin_interfaces/Time stamp
    float32 temperature
    string unit
    float32 max_safe_temperature
    bool over_temperature

---
## 📚Resources :
- ROS2 Turtoials Documentations: (https://docs.ros.org/en/humble/Tutorials.html)

## 📦Deliverables :
- ROS 2 packages implementing the complete solution for the above tasks

## ⏰Deadline : 27/01/2026
