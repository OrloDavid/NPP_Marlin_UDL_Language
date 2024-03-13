# Features of My Notepad++ User Defined Language (A.K.A. Syntax Highlighting) 

- Compatibility: Works with various editors/UDLs. , specifically made for Notepad ++

- Language Support: Handles a mix of CPP , Wiring (like in Marlin, Arduino), .ino files.

- Targeted Use: Primarily for Marlin Config code, but also effective with cpp, h, and c files.

- Color Coding:

- Single and multi-line comments in different shades.

- DEFINEstatements in red, varying intensity based on status.

- Gcode in bright baby blue.

- Basic text in white.

- Light blue for text in If statements.

- Yellow for digits, green for data in brackets.

- Bright green and red for section headers.

## Issues Encountered

- Color Coding Errors: Post-editing, files may show incorrect comment color coding. Toggling tabs can temporarily fix this.

- Nested Statements: Struggles with nested #IF, if, ifdefstatements, especially when they end with ;instead of endif. This complexity arises from the limitations of UDL in NPP.

## About Me

I'm not professionally trained in software engineering or programming. My approach involves extensive research, trial and error, and consulting various sources, including AI. Any inaccuracies are not reflective of my personal opinions but rather an attempt to demonstrate my dedication to my work.

## Motivation Behind Creation

- Background: Previously created a UDL for NPP while working on PowerShell programming for Cisco switches. The UDL significantly improved my coding efficiency.

- Necessity: Faced challenges with Marlin code for my AnyCubic printer, leading to the development of another UDL. The mixed language nature of the code and the need for efficient scanning were key motivators.

- UDL Programming: I view UDL programming as a blend of creativity and critical thinking. It's like planning several steps ahead in chess, considering the nested nature of coding.
