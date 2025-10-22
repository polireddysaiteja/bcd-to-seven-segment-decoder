# BCD to Seven Segment Display Decoder

This project demonstrates a **BCD to Seven Segment Display Decoder** circuit designed using **NI Multisim** and the **74LS47 decoder IC**.

## 🧰 Tools Used
- NI Multisim
- 74LS47 BCD to 7-Segment Decoder
- 7-Segment Display

## ⚙️ Working Principle
The 74LS47 IC takes a 4-bit BCD input and drives the 7-segment display to show the corresponding decimal digit (0–9).  
The input switches (S1–S4) represent binary bits (A, B, C, D). Depending on their combination, the decoder outputs activate specific segments on the display.

## 🖥️ Circuit Diagram
![BCD to Seven Segment Decoder Circuit](Screenshot%202025-10-22%20212827.png)

## 🧩 Connections Overview
- **Inputs (A, B, C, D):** Controlled by switches S1–S4  
- **Outputs (a–g):** Connected from U1 (74LS47) to the 7-segment display (U2)  
- **Power Supply:** 5V DC  

## ✨ Author
Sai Teja Pollireddy
