# Currency Converter using Java AWT

This project demonstrates a simple currency converter between INR (Indian Rupee) and USD (US Dollar) using Java AWT (Abstract Window Toolkit). The program provides a graphical user interface (GUI) with text fields for input, buttons for conversion, and labels for output. It allows conversion from INR to USD and vice versa.

## Features
- Converts between INR and USD based on a fixed conversion rate (1 USD = 65.25 INR).
- Provides an intuitive GUI with text fields and buttons for easy interaction.
- Uses AWT components such as `JFrame`, `JLabel`, `JTextField`, and `JButton` for building the interface.

## Examples
- **Input**: INR = 130.5  
  **Output**: 2.0 USD  
  **Explanation**: Since 1 USD = 65.25 INR, 130.5 INR = 2.0 USD.
  
- **Input**: USD = 4.5  
  **Output**: 293.625 INR

## Approach
1. **Create the Frame**: Use `JFrame` to set up the window frame.
2. **Add Labels and Text Fields**: Use `JLabel` to create labels and `JTextField` for input fields for INR and USD.
3. **Add Buttons**: Create buttons using `JButton` for the conversion actions between INR and USD.
4. **Event Handling**: Use `ActionListener` to handle button clicks. Inside the `actionPerformed` method, retrieve the input values from the text fields, convert them to the appropriate data types using `Double.parseDouble()`, perform the conversion, and set the result back to the appropriate text field.
5. **Set Text**: Display the converted value using `Object.setText()` to update the result in the output field.

## Prerequisites
- Basic understanding of Java programming.
- Java Development Kit (JDK) installed.
- Familiarity with AWT or Swing components for building GUIs.

## How to Run
1. Clone or download the repository.
2. Compile the Java code using the following command:

```bash

javac CurrencyConverter.java 
