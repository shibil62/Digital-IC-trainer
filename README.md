# Digital IC Trainer

> An interactive, browser-based digital electronics laboratory for experimenting with 7400-series logic ICs, breadboard wiring, switches, LEDs, and logic verification.

![HTML](https://img.shields.io/badge/HTML5-Web%20Application-orange?style=for-the-badge&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20JS-yellow?style=for-the-badge&logo=javascript)
![CSS](https://img.shields.io/badge/CSS3-Styled-blue?style=for-the-badge&logo=css3)
![License](https://img.shields.io/badge/License-Educational-green?style=for-the-badge)

---

## 📌 Overview

**Digital IC Trainer** is an interactive web-based simulator designed to recreate the experience of working with a physical digital electronics trainer board.

Users can place supported **7400-series logic ICs**, connect pins using virtual wires, provide power, control logic inputs, observe outputs, and verify circuit behaviour using automated truth-table testing.

The project is designed as an educational tool for students learning:

- Digital Logic Design
- Boolean Logic
- Logic Gates
- Integrated Circuits
- Breadboard Connections
- Digital Electronics Laboratory Experiments

---

## ✨ Features

### 🔌 Interactive Breadboard

- Realistic digital electronics trainer interface
- Interactive breadboard connections
- Multiple IC placement slots
- Virtual wiring between terminals
- Colour-based wire selection

### 🧠 7400-Series IC Support

Currently supported ICs include:

| IC | Function |
|---|---|
| **7400** | Quad 2-Input NAND Gate |
| **7402** | Quad 2-Input NOR Gate |
| **7404** | Hex Inverter (NOT Gate) |
| **7408** | Quad 2-Input AND Gate |
| **7432** | Quad 2-Input OR Gate |
| **7486** | Quad 2-Input XOR Gate |

### ⚡ Circuit Simulation

- Power ON/OFF functionality
- VCC and GND connections
- Interactive logic inputs
- LED output indication
- Real-time logic state updates
- IC pin mapping

### 🛠️ Circuit Controls

- Place ICs
- Remove ICs
- Create connections
- Select wire colours
- Delete selected wires
- Clear all wires
- Undo previous actions
- Reset the entire board

### ⚠️ Safety Detection

The simulator includes basic circuit validation and can detect potentially invalid connections such as:

- Conflicting output connections
- Possible short circuits
- Incorrect circuit configurations

### 🧪 Truth Table Testing

Automatically test available input combinations and verify logic gate behaviour.

### 🔍 Navigation

- Zoom in
- Zoom out
- Reset zoom
- Pan around the virtual trainer board

### 📱 Responsive Design

The interface adapts to different screen sizes, including smaller displays.

---

## 🖥️ Technologies Used

This project is built entirely using web technologies.

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **SVG**

No frameworks or external dependencies are required.

---

## 🚀 Getting Started

### Option 1 — Run Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/digital-ic-trainer.git
```

2. Open the project folder.

3. Open:

```text
index.html
```

in any modern web browser.

That's it. No installation or build process required.

---

## 🎮 How to Use

### 1. Place an IC

Select a supported IC from the dropdown menu and click:

```text
Place IC
```

### 2. Connect Power

Connect:

- **VCC** to the positive power terminal
- **GND** to the ground terminal

### 3. Create Circuit Connections

Click on terminals to create virtual wire connections between:

- Logic switches
- IC inputs
- IC outputs
- LEDs
- Power terminals

### 4. Power the Circuit

Turn the virtual power supply ON.

### 5. Test Your Logic

Change input states and observe the resulting output.

Use the **Truth Table Test** feature to test all available logic combinations.

---

## 🧩 Project Structure

```text
Digital-IC-Trainer/
│
├── index.html
│
└── README.md
```

The application is intentionally lightweight and currently runs from a single self-contained HTML file.

---

## 🎯 Educational Purpose

This project was created as an educational simulation tool for understanding fundamental concepts in digital electronics.

It can be useful for:

- Engineering students
- Digital electronics laboratory preparation
- Logic gate experimentation
- Understanding 7400-series IC pin configurations
- Practising circuit connections before working with physical hardware

---

## 🔮 Future Improvements

Potential future enhancements include:

- Additional IC support
- Flip-flops and sequential circuits
- Multiplexers and decoders
- Circuit saving and loading
- Custom circuit projects
- More realistic electrical validation
- Expanded truth-table analysis
- Mobile UI improvements
- Drag-and-drop components

---

## ⚠️ Disclaimer

This project is an **educational simulator** and is not intended to replace professional electronic design automation or hardware simulation software.

Simulation behaviour is designed for learning and demonstration purposes.

---

## 👨‍💻 Author

**Shibil P A**

Created as an educational digital electronics project.

---

## 📄 License

This project is intended for educational and learning purposes.

Feel free to explore, learn from, and build upon the project with appropriate attribution.

---

⭐ **If you found this project useful, consider giving the repository a star!**
