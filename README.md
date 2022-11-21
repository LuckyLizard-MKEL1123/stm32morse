# Milestone1.2: stm32morse
Group Name: **Lucky Lizard** :lizard:

Group Member: 
1. **Andi Nur Asyikin Binti Andi Zainuddin**
2. **Lim Yong Chuan**
3. **Nur Fatini Binti Isa**

## Ojective
STM32 toolchain checkout
## Equipment
- [x] Board used: **NUCLEO-F411RE**
- [x] Software used: **STM32CubeIDE**
## Procedure
1. STM32CubeIDE is used as development platform throughout this course
2. For this milestone, letters **A, F, Y** is translated into morse code and transmitted through the blink of LED on the nucleo board.
3. The source code is generated in C language: [stm32morse.c](pastelink)
   
  - Port A, Pin 5 represent the green LED on the nucleo board
  - An array is declared to determine the Pin toggling

| Letter | Morse code | How it's coded ** *() represents delay*|
| ----------- | ----------- | ----------- |
| A | • -| ON(500) OFF(500) ON(800) |
| F | • • - • | ON(500) OFF(500) ON(500) OFF(500) ON(800) OFF(500) ON(500) |
| Y | - • - -| ON(800) OFF(500) ON(500) OFF(500) ON(800) OFF(500) ON(800) |
  - There is 2000us delay set between each letter
  
## Results
Link for milestone 1.2 demo: [title](pastelink)
## References
