# Clinic Simulation System

## Overview
This project simulates a clinic environment where patients arrive, consult with doctors, and interact with a waiting room system. The simulation uses semaphores for synchronization and multithreading for real-time operations. This allows the simulation to model and analyze clinic workflows efficiently, providing insights into patient flow and resource utilization.

## Features
Multithreaded Simulation: Patient arrivals, doctor consultations, and waiting room interactions happen concurrently, simulating real-time clinic activities.
 
Semaphore-Based Synchronization: Ensures proper coordination between threads, simulating the limited availability of doctors and waiting room spaces.
 
Customizable Parameters: The number of doctors, patients, and waiting room capacity can be adjusted to reflect different clinic scenarios.

Efficiency Analysis: The system tracks the time spent by each patient in the clinic and provides reports on overall clinic efficiency.

## Technology Stack
### Java: Core programming language.
### Semaphores: For synchronization between patient, doctor, and waiting room interactions.
### Multithreading: For handling real-time interactions between multiple patients and doctors.
### CLI Interface: Provides real-time feedback on patient flow and doctor availability.

## How to Run
Clone the repository:
### ` git clone https://github.com/your-repo/clinic-simulation.git`
Navigate to the project directory:
###  `cd clinic-simulation`
Compile the Java files:
### `javac ClinicSimulation.java`
Run the simulation:
### `java ClinicSimulation`
## Usage
Upon running, you'll be prompted to input:
The number of patients.

The number of available doctors.

The capacity of the waiting room.

The simulation will begin, displaying real-time updates of patient arrivals, doctor consultations, and waiting room status. 

## Future Enhancements
Implement a graphical user interface (GUI) for visualizing patient flow.

Add logging functionality for detailed time tracking and performance analysis.

Introduce patient prioritization based on urgency.

