# Half Subtractor - Logic Circuit Project

A **Half Subtractor** is a basic combinational circuit in digital electronics.  
It takes two binary inputs and produces:  
- **Difference** (A ⊕ B)  
- **Borrow** (A' · B)  

This project was created using **Logic Circuit Simulator Pro** on Android.

## 🧮 Truth Table - Half Subtractor  

| A | B | Difference (A ⊕ B) | Borrow (A' · B) |
|---|---|--------------------|-----------------|
| 0 | 0 | 0                  | 0               |
| 0 | 1 | 1                  | 1               |
| 1 | 0 | 1                  | 0               |
| 1 | 1 | 0                  | 0               |

## 🖼️ Project Images  

To view the images of the Half Subtractor circuit in different conditions:

- **HalfSubtractor00.png**  
- **HalfSubtractor01.png**  
- **HalfSubtractor10.png**  
- **HalfSubtractor11.png**  

## 🎥 View video  

- Go to **HalfSubtractor_Simulation.mp4**  
- Click on **view raw**  

## 🛠️ Tools Used  

- Logic Circuit Simulator Pro (Android app)  

## 💡 How it works  

The Half Subtractor subtracts two 1-bit binary inputs.  
- The **Difference** is calculated using an **XOR gate**.  
- The **Borrow** is calculated using an **AND gate** with **NOT(A)** and **B**.  

The circuit is built using drag-and-drop logic gates in the app.
