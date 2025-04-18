# Virtual Kitchen Swing Application

## 🏠 Introduction

**Virtual Kitchen** is an interactive Java Swing application that simulates a realistic kitchen with multiple appliances that users can control. Built using Java's GUI framework, the project allows interaction with a refrigerator, oven, microwave, sink, and a timer. It serves both as a **learning tool** for GUI development that showcases Java proficiency, custom painting, event handling, and user interaction in desktop applications.

---

## ⚙️ Technologies Used

- **Java SE**  
- **Java Swing GUI Toolkit**  
- **Custom painting using `Graphics` and `JPanel`**  
- **Event handling with `ActionListener`, `ChangeListener`**  
- **Timers using `javax.swing.Timer`**

---

## 🧱 Features

### 🧊 Refrigerator  
- Button to open/close the door  
- Door graphics change upon interaction  
- Feedback label shows `"Refrigerator is open"` or `"Refrigerator is closed"`

### 🔥 Oven  
- Slider to control temperature (0–250°C)  
- Oven interior glows (yellow-red) based on temperature  
- Real-time temperature label updates

### 📡 Microwave  
- Button to start microwave for 5 seconds  
- Flashing animation simulates cooking  
- Status label and a beep when done

### 🚿 Sink (Enhanced Feature)  
- Button toggles water on/off  
- Blue stream drawn to simulate water  
- Feedback label updates accordingly

### ⏱️ Cooking Timer (Enhanced Feature)  
- 10-second countdown timer  
- Label updates every second  
- Beep when timer completes

---

## 🎨 Custom Graphics

The kitchen appliances are drawn using Java's `Graphics` object inside the overridden `paintComponent()` method:

- Appliances are represented with shapes (rectangles, lines, labels).
- Real-time changes like door movement, glowing heat, and flashing lights.
- Easily extendable with `ImageIcon` support for realistic textures/images.

---

## 🧪 How to Run

1. **Compile** the code:
   ```bash
   javac VirtualKitchen.java
   ```

2. **Run** the application:
   ```bash
   java VirtualKitchen
   ```

3. **Interact**:
   - Click the buttons and slider.
   - Watch the appliance graphics and feedback labels update live.

---

## 📈 Key Learning Outcomes

| Skill | Description |
|-------|-------------|
| **Swing Components** | Learned how to use buttons, sliders, labels, and layout managers effectively. |
| **Custom Painting** | Created dynamic, responsive graphics using Java 2D. |
| **Event-Driven Programming** | Implemented interactive behavior using listeners and timers. |
| **State Management** | Managed UI states for multiple elements (microwave, oven, etc.). |
| **Concurrency** | Used `javax.swing.Timer` safely within the Swing Event Dispatch Thread. |
| **Multimedia Integration** | Explored sound beeps and laid foundation for future audio/image asset use. |

---

## 📌 Future Improvements

- Replace shapes with **realistic images** via `ImageIcon`
- Add **drag-and-drop** appliance interaction
- Add **sound effects** using `javax.sound.sampled`
- Support **theme switching (dark mode / kitchen skins)**

---

## 📁 File Structure

```
VirtualKitchen.java   <-- Main Java class
README.md             <-- Project overview and instructions
```

---

## 🧠 Credits

Developed by **Marcus Workman**, Computer Science student and Software Engineer.  
Guided by project prompt requiring interactive Java Swing application development.

---

## 🔗 License

MIT License – free to use, fork, and enhance for educational purposes.
