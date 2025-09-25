# COMPENG 2DX3 – Microprocessor Systems Project
Microprocessor Systems Project - Microprocessor systems, introduction to the design process, project development by small teams of students, oral presentations and engineering report writing.
This repository contains my written deliverables for COMPENG 2DX3: Microprocessor Systems Project, including:
- Theme Reports (Observe, Reason, Act).
- Pre-Lab Reports.
The hands-on labs were completed in person on lab computers using the MSP432E401Y ARM Cortex-M4F LaunchPad, the Keil µVision IDE, and supporting peripherals (keypads, LEDs, stepper motors, sensors, etc.). While lab source files were not retained, this README documents the scope and objectives of each laboratory exercise from the official lab manual.

📘 Course Overview: 
2DX3 is a project-based embedded systems course structured around the themes:
- Observe – capturing and interpreting digital/analog signals.
- Reason – processing data with microcontrollers, state machines, and timing.
- Act – implementing system-level integration, peripheral control, and event-driven programming.

Weekly labs built directly toward the final individual project, reinforcing lecture and studio content with hands-on practice.

🔬 Laboratory Summaries:
- Lab 0 – Introduction to 2DX Labs
  - Setup of the MSP432E401Y development environment (Keil MDK).
  - Completed lab safety quiz and formed teams of two.
  - Ran and modified the “BlinkLED” example project.
  - Practiced GPIO output by toggling Port M pins to LEDs.
  - Learned debugging with Keil (stepping through code, breakpoints, register inspection).

- Lab 1 – Digital Signals (Observe)
  - Introduced assembly programming for GPIO.
  - Wrote an assembly “Hello World” program to blink an onboard LED.
  - Connected a push button with pull-up resistors and wrote code to control LED states.
  - Learned fundamentals of digital input/output handling on the microcontroller.

- Lab 2 – Finite State Machine and Digital Design (Observe)
  - Designed digital locks using GPIO and assembly.
  - Parallel I/O Lock: Configured push buttons as inputs and LEDs as outputs for a combinational lock.
  - Sequential I/O Lock: Implemented a state-machine approach to accept serial input codes.
  - Applied FSM design principles to embedded systems.

- Lab 3 – Analog Signals (Observe)
  - Transitioned from assembly to C programming for embedded development.
  - Configured and used the MSP432E401Y ADC (12-bit).
  - Measured and digitized DC, sinusoidal, and square wave inputs using the AD2 Wavegen.
  - Learned quantization, sampling, and interpreting ADC values.

- Lab 4 – Duty Cycle and Pulse Timing (Reason)
  - Generated PWM signals to control LED brightness.
  - Programmed PWM outputs for stepper motor control.
  - Gained experience with timing loops, duty cycle adjustment, and motion control.
  - Introduced motor driver interfacing.

- Lab 5 – Peripheral Interfacing (Reason)
  - Interfaced a 4×4 keypad with the microcontroller using GPIO and internal pull-up resistors.
  - Implemented key decoding logic.
  - Displayed inputs via LED array outputs.
  - Optional extension to 7-segment display for numeric output.

- Lab 6 – Project Deliverable 1 (Early Integration) (Reason → Act transition)
  - Integrated multiple subsystems toward the final project.
  - Demonstrated preliminary hardware + software functionality.
  - Conducted milestone interview with TAs to validate system design and debugging process.

- Lab 7 – Interrupts and Event Programming (Act)
  - Implemented periodic timer interrupts to structure program tasks.
  - Programmed GPIO interrupts to handle button presses without polling.
  - Introduced event-driven programming for efficiency and responsiveness.

- Lab 8 – Collecting Distance Data (Act)
  - Interfaced the VL53L1X Time-of-Flight (ToF) distance sensor over I²C.
  - Read sensor ID, module type, and real-time distance measurements.
  - Extended to logging data and (optionally) visualizing results in Python.
  - This lab directly supported the Act theme report and final project integration.

✍️ Notes:
- All labs were completed in-person on lab computers with TAs verifying milestone demonstrations.
- This repo contains only my written deliverables (theme reports & prelabs).
- The Final Project (individual) is in a separate repository.

📜 Acknowledgements:
- Course: COMPENG 2DX3 – Microprocessor Systems Project
- Instructors: Dr. Shahrukh Athar, Dr. Thomas Doyle, Dr. Yaser Haddara
- 2DX3 Lab Manual
- Labs built upon the MSP432E401Y ARM Cortex-M4F platform and Digilent Analog Discovery 2 instrumentation.
