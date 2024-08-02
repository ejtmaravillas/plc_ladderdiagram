# PLC Fiddle Exercises

This repository contains a series of exercises designed to help you get familiar with PLC (Programmable Logic Controller) programming using the online ladder logic simulator, PLC Fiddle.

## Exercise 1: Introduction to PLC Fiddle

1. In a web browser, navigate to [PLC Fiddle](https://www.plcfiddle.com/)
   - **NOTE:** PLC Fiddle is an online ladder logic simulator supported on Firefox, Chrome, and Safari browsers. Microsoft EDGE does not fully support PLC Fiddle.
   - You do **NOT** have to create an account.
2. Click and drag a variable and place it on a rung.
3. Select a tagname from the drop-down menu.
4. Add additional variables by entering a name (tagname) and selecting the data type.

   **PLC Fiddle Data Types:**
   - **Bool:** ON/OFF = TRUE/FALSE
   - **Number:** 0 – 9999…
   - **Timer:** 0 seconds - 9999…seconds
   - **Counter:** counts up or down = 0 – 9999 or 9999 to 0

5. Turn the motor on and off – just to get your feet wet.

## Exercise 2: Basic Control Logic

Create a new rung(s) to accomplish the following:

1. **Window Alarm:** An alarm that will sound unless the window is closed (alarm when OFF).
   - Add a new variable, name it “window” and select Boolean for the type.
   - Drag and drop a normally closed contact, select “window” from the dropdown list.
   - Create a new Boolean variable, name it “alarm”.
   - Drag and drop a coil, select “alarm” from the dropdown list.

2. **Doorbell Simulation:** A momentary push button that rings a bell only when initially pressed. This is different from a light switch that stays on until turned off.

3. **Counter:** A counter to turn on a motor when the start button has been clicked 3 times.

4. **Timer:** A timer to turn on a motor after a 3-second timer has expired.

## Exercise 3: Simulated Speedometer

Create a simulated speedometer with the following features:

- **On/Off button**
- **Rate:** Current speed
- **SP:** Setpoint = desired speed
- **Coast:** Lets your current speed slowly decrease
- **Incr:** Increases your setpoint by 1 mph

## Getting Started

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ejtmaravillas/plc_ladderdiagram.git
