# 🤖 Obstacle Avoiding Arduino Car

This is an Arduino-based robot car that automatically detects and avoids obstacles using an ultrasonic sensor (HC-SR04) and L298N motor driver module. It’s a great beginner project to understand robotics, sensors, and motor control.

> ✅ Perfect for school/college robotics projects.

---

## 🚀 Features

- Moves forward automatically  
- Stops and turns when obstacle is detected  
- Uses ultrasonic sensor for distance measurement  
- Powered by Arduino UNO and L298N motor driver  
- Lightweight and easy to build

---

## 🧰 Components Required

- Arduino UNO  
- HC-SR04 Ultrasonic Sensor  
- L298N Motor Driver  
- 2x DC Motors & Wheels  
- Chassis  
- 9V or 12V Battery  
- Jumper Wires  
- Castor Wheel  
- Switch  

---

## 🔌 Circuit Connections

- **HC-SR04:**  
  - VCC -> 5V  
  - GND -> GND  
  - TRIG -> Pin 12  
  - ECHO -> Pin 11  

- **L298N Motor Driver:**  
  - IN1 -> Pin 8  
  - IN2 -> Pin 7  
  - IN3 -> Pin 6  
  - IN4 -> Pin 5  
  - ENA -> Pin 9  
  - ENB -> Pin 10  
  - VCC -> Battery +  
  - GND -> Battery - & Arduino GND  

---

## 📄 How It Works

1. HC-SR04 measures distance in front of the car  
2. If distance < 20cm → car stops and turns  
3. Else → car moves forward  

---

## 🧑‍💻 Author

**Pradeep Kumar S**  
📧 pradeepniatian@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/pradeep-kumar-s-61856336b)

---

## 📃 License

This project is open for learning and educational use. Have fun building!
