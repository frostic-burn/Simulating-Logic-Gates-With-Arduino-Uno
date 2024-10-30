# Simulating-Logic-Gates-With-Arduino-Uno
Simulating the Function of Logic Gates With Arduino Uno R3

This project is a digital simulation of logic gates using an Arduino. It allows users to experiment with fundamental logic operations, such as AND, OR, NAND, NOR, XOR, and XNOR, by using push buttons as inputs and LEDs to display both input states and the output of each logic gate. Here’s an overview of its components and working:

### **Components and Circuit Layout**
- **Arduino Uno**: Serves as the control unit, executing logic operations based on input and providing output through LEDs.
- **3 Push Buttons**:
  - **Button A and Button B** act as input signals for the logic gates.
  - **Button Select** cycles through the logic gates.
- **9 LEDs**:
  - **3 LEDs** represent the inputs (A, B) and the output of each logic gate.
  - **6 LEDs** act as indicators, showing which logic gate is currently selected.

Each LED is connected to a specific pin on the Arduino, with 220Ω resistors in series to limit current and protect the LEDs. The Arduino reads the button inputs, processes them according to the selected logic gate, and lights up the output LED accordingly. Users can easily switch between gates to observe the behavior of various logic operations.

### **Working**
1. **Button Inputs**: Button A and Button B represent the two binary inputs for the logic gates. Pressing each button changes the input state (HIGH/LOW) for logic operations.
2. **Gate Selection**: The third button cycles through each logic gate. When a gate is selected, its respective indicator LED lights up.
3. **Logic Calculation**: Based on the gate selected, the Arduino performs the appropriate logic operation on inputs A and B.
4. **Output Display**: The output LED lights up based on the result of the selected logic gate's calculation.

This project provides a practical and visual way to learn about basic digital logic gates, using Arduino to control and visualize the operations digitally.
