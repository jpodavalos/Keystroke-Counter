# Keystroke-Counter
A simple C# app that reads and counts keyboard keystrokes.

![alt text](https://github.com/jpodavalos/Keystroke-Counter/blob/master/images/keystroke_counter_light.JPG?raw=true)
![alt text](https://github.com/jpodavalos/Keystroke-Counter/blob/master/images/keystroke_counter_dark.JPG?raw=true)

## Requirements:
* Visual Studio 2017
* MetroFramework Modern UI installed

## How to add keys:
Navigate to Keystroke_Counter.cs and add the following with desired Key
```
gkh.HookedKeys.Add(Keys.A);
```

## References:
* A Simple C# Global Low Level Keyboard Hook by StormySpike https://www.codeproject.com/Articles/19004/A-Simple-C-Global-Low-Level-Keyboard-Hook
* MetroFramework Modern UI https://github.com/dennismagno/metroframework-modern-ui

