## Features of My Notepad++ User Defined Language (Syntax Highlighting)

### Compatibility
- Works with various editors/UDLs, specifically designed for Notepad++

### Language Support
- Handles a mix of CPP, Wiring (like in Marlin, Arduino), .ino files.

### Targeted Use
- Primarily for Marlin Config code, but also effective with cpp, h, and c files.

### Color Coding
- Single and multi-line comments in different shades.
- `DEFINE` statements in red, varying intensity based on status.
- Gcode in bright baby blue.
- Basic text in white.
- Light blue for text in If statements.
- Yellow for digits, green for data in brackets.
- Bright green and red for section headers.

## Issues Encountered

### Color Coding Errors
- Post-editing, files may show incorrect comment color coding. Toggling tabs can temporarily fix this.

### Nested Statements
- Struggles with nested `#IF`, `if`, `ifdef` statements, especially when they end with `;` instead of `endif`. This complexity arises from the limitations of UDL in NPP.


## Screenshots of Notepad++ User Defined Language (UDL)

### Screenshot 1
![NPP Marlin UDL 01](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/blob/main/Screenshots/NPP_Marlin_UDL_01.png)

### Screenshot 2
![NPP Marlin UDL 02](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/blob/main/Screenshots/NPP_Marlin_UDL_02.png)

### Screenshot 3
![NPP Marlin UDL 03](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/blob/main/Screenshots/NPP_Marlin_UDL_03.png)

### Screenshot 4
![NPP Marlin UDL 04](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/blob/main/Screenshots/NPP_Marlin_UDL_04.png)

### Screenshot 5
![NPP Marlin UDL 05](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/blob/main/Screenshots/NPP_Marlin_UDL_05.png)

### Screenshot 6
![NPP Marlin UDL 06](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/blob/main/Screenshots/NPP_Marlin_UDL_06.png)

### Screenshot 7
![NPP Marlin UDL 07](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/blob/main/Screenshots/NPP_Marlin_UDL_07.png)




## About Me
I'm not professionally trained in software engineering or programming. My approach involves extensive research, trial and error, and consulting various sources, including AI. Any inaccuracies are not reflective of my personal opinions but rather an attempt to demonstrate my dedication to my work.

## Motivation Behind Creation

### Background
- Previously created a UDL for NPP while working on PowerShell programming for Cisco switches. The UDL significantly improved my coding efficiency.

### Necessity
- Faced challenges with Marlin code for my AnyCubic printer, leading to the development of another UDL. The mixed language nature of the code and the need for efficient scanning were key motivators.

### UDL Programming
- I view UDL programming as a blend of creativity and critical thinking. It's like planning several steps ahead in chess, considering the nested nature of coding.

This customization is tailored for the Marlin firmware to handle the Arduino/Wiring language and CPP, focusing primarily on Marlin code and the config files. Changes make finding things in the configs super easy. Reworked config files with section headers can be found [here](https://github.com/OrloDavid/NPP_Marlin_UDL_Language/tree/main/Better%20Marlin%20Configs). These files feature organized sections with easy-to-find headers, grouped similar items, child-like items for faster browsing, and sections organized by machine-specific details, kinematics, steppers, etc.

The UDL features highlighted Define items, even when disabled, they are highlighted in a dimmer color. Multiline comments are a darker set of colors than the single line, allowing for faster skipping past well-known multi-line comments. Gcode has its own color scheme but may not work well if mixed within a comment. The open and close of `If` statements are highlighted, but this can sometimes be confused due to the use of `#ifdef`, `#elif`, `#ifndef`, `#if`, `else`, and their overlapping on closing brackets, which can confuse the UDL. This UDL has evolved over time to accommodate the looping/nested nature of the UDL language, looping through all options and nesting other options as needed, adding to the complexity.
