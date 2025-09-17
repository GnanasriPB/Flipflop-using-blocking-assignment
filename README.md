# EXPERIMENT 3: Simulation of All Flip-Flops using Blocking Statement

## AIM
To design and simulate basic flip-flops (SR, D, JK, and T) using **blocking statements** in Verilog HDL, and verify their functionality through simulation in Vivado 2023.1.

## APPARATUS REQUIRED
- Vivado 2023.1
- Computer with HDL Simulator

## DESCRIPTION
Flip-flops are the basic memory elements in sequential circuits.  
In this experiment, different types of flip-flops (SR, D, JK, T) are modeled using **behavioral modeling** with **blocking assignment (`=`)** inside the `always` block.  
Blocking assignments execute sequentially in the given order, which makes it easier to describe simple synchronous circuits.

## PROCEDURE
1. Open **Vivado 2023.1**.  
2. Create a **New RTL Project** (e.g., `FlipFlop_Simulation`).  
3. Add Verilog source files for each flip-flop (SR, D, JK, T).  
4. Add a testbench file to verify all flip-flops.  
5. Run **Behavioral Simulation**.  
6. Observe waveforms of inputs and outputs for each flip-flop.  
7. Verify that outputs match the truth table.  
8. Save results and capture simulation screenshots.

---

## VERILOG CODE

### SR Flip-Flop (Blocking)

<img width="1920" height="1080" alt="Screenshot 2025-09-17 202556" src="https://github.com/user-attachments/assets/5e828155-65bd-4da7-9b93-e61b0721c4ca" />

### SR Flip-Flop Test bench 

<img width="1920" height="1080" alt="Screenshot 2025-09-17 203702" src="https://github.com/user-attachments/assets/aaa72521-455b-4060-8586-6101bed954fb" />

#### SIMULATION OUTPUT

<img width="1920" height="1080" alt="Screenshot 2025-09-17 203115" src="https://github.com/user-attachments/assets/274c38dc-f221-40fd-aeb2-d3fbdf6e909c" />

### JK Flip-Flop (Blocking)

<img width="1920" height="1080" alt="Screenshot 2025-09-17 103441" src="https://github.com/user-attachments/assets/d0a56522-98a9-40e8-8bd0-682d82b5f29e" />


### JK Flip-Flop Test bench 

<img width="1920" height="1080" alt="Screenshot 2025-09-17 104914" src="https://github.com/user-attachments/assets/57d5180b-a253-4957-a74a-0078b981a1ff" />


#### SIMULATION OUTPUT

<img width="1920" height="1080" alt="Screenshot 2025-09-17 112013" src="https://github.com/user-attachments/assets/b82f3211-8f31-4dac-aed8-4acee568961b" />

### D Flip-Flop (Blocking)

<img width="1920" height="1080" alt="Screenshot 2025-09-17 211641" src="https://github.com/user-attachments/assets/b834b4cf-ca88-4bca-b97a-456042dc8625" />


### D Flip-Flop Test bench 

<img width="1920" height="1080" alt="Screenshot 2025-09-17 213229" src="https://github.com/user-attachments/assets/08c07251-a717-41ce-8d07-abdb30e68d7f" />


#### SIMULATION OUTPUT

<img width="1920" height="1080" alt="Screenshot 2025-09-17 211625" src="https://github.com/user-attachments/assets/d20de359-4c94-46b9-b457-ae978c2d6677" />

### T Flip-Flop (Blocking)

<img width="1920" height="1080" alt="Screenshot 2025-09-17 204419" src="https://github.com/user-attachments/assets/3593906d-4b77-4bc0-9adf-598f621b56a5" />

### T Flip-Flop Test bench 

<img width="1920" height="1080" alt="Screenshot 2025-09-17 205920" src="https://github.com/user-attachments/assets/d4aec8d5-0dc2-4d80-8684-a3e23053dd7e" />


#### SIMULATION OUTPUT

<img width="1920" height="1080" alt="Screenshot 2025-09-17 205226" src="https://github.com/user-attachments/assets/70a615bd-50c2-498d-a32d-c16e64b8b291" />


### RESULT

All flip-flops (SR, D, JK, T) were successfully simulated using blocking statements in Verilog HDL.
The outputs matched the expected truth table values, demonstrating correct sequential behavior.
