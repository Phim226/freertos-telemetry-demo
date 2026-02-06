# FreeRTOS Telemetry Demo

This project is a simple FreeRTOS satellite telemetry demo using the FreeRTOS blinky demo. It implements a simple telemetry receiver and manager. 

# Build Instructions

1. Clone the FreeRTOS repository as per their instructions.
2. Copy the files in this repository to the Posix_GCC folder, making sure to overwrite main_blinky.c. 
3. Run 
```bash 
make CC=gcc USER_DEMO=BLINKY_DEMO
```
