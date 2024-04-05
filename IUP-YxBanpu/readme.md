## Step 1: Introduction to Low Pass Filters

Definition: Low Pass Filter (LPF) or High Cut is a frequency filter that allows low-frequency waves to pass through while cutting off higher-frequency waves.
Purpose: LPF filters sound within a frequency range, cutting off frequencies exceeding a defined threshold, commonly referred to as "High Cut."

## Step 2: Designing a Low Pass Filter

Overview: The design process involves analysis of provided data and graphs to select appropriate values for designing LPF.
Design Objective: Achieve maximum insertion loss (IL max) at 0–2.4 GHz (< 3 dB) and minimum rejection level (RJ min) at 4.8–6.0 GHz (>3 dB).
Cut off 2GHz, ATTN 3GHz > 30dB

#### 1.By using the data from this table to design STEPPED-IMPEDANCE LOW-PASS FILTER

<img width="502" alt="Screenshot 2567-04-05 at 22 56 52" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/cfb82dde-d40c-424b-9fc1-fcedb8f58a8f">


#### 2.We are choosing n = 9 from this graph

<img width="394" alt="Screenshot 2567-04-05 at 22 58 12" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/e35377f4-0e9e-48af-b1a1-d2bfb1ab2981">

#### 3. From criteria given ATTN 3GHz > 30dB so from the graph above we are choosing n = 9 we will get (w/wc)-1 = 0.5 Calculation:

<img width="235" alt="Screenshot 2567-04-05 at 22 59 33" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/723e00df-27bb-4487-9076-1318f3e0a83e">
 	f = 3 GHz, fc = 2 GHz, (w/wc) - 1 = 0.5

#### 4.Calculate g from the 1.) and 2.) to get the value to insert in the excel below to get the L and C value
<img width="499" alt="Screenshot 2567-04-05 at 22 59 59" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/d0a4e864-9736-40af-9f46-9954f3b68140">

#### 5. Insert the data from above in sonnet to generate and get the lowpass graph below
<img width="577" alt="Screenshot 2567-04-05 at 23 00 04" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/64fcfd33-0896-437a-808b-99c000bb0748">

## Step 3: Evaluation of Cases<br><br>
<img width="509" alt="Screenshot 2567-04-05 at 23 03 51" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/b0f8ee15-4f34-4f8a-8f15-0b00d3f4c1ee">


Use Excel to calculate the value to put in the transmission line


Analyze three cases using Sonnet software for visualization and comparison:<br>
Case 1: Zh=100Ω, Zl=25Ω<br>
<img width="505" alt="Screenshot 2567-04-05 at 23 01 06" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/416eb57d-ae11-4f4f-b531-259d76309f25">

Case 2: Zh=200Ω, Zl=25Ω<br>
<img width="520" alt="Screenshot 2567-04-05 at 23 05 28" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/84e1ab66-17b9-4d56-af56-eab060e7fa89"><br>
Case 3: Zh=150Ω, Zl=25Ω

<img width="627" alt="Screenshot 2567-04-05 at 23 05 36" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/35f93ea2-f6d9-425b-a261-c03ec940a4c8">



Compare cases at f = 2 GHz.
Consider practical implications alongside theoretical analysis.
Select the most suitable case (Case 3) for design.

## Step 4: compute and design

Use TxLine to compute PLC of board




<img width="293" alt="Screenshot 2567-04-05 at 23 06 40" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/c15865ef-fa9f-44ad-8278-51f5d92b094e">

<img width="246" alt="Screenshot 2567-04-05 at 23 07 07" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/de383ac4-3fc7-44c5-b911-598d0eb9f871">




Design Geometry Sonnet


<img width="254" alt="Screenshot 2567-04-05 at 23 07 48" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/f51beacd-00f5-4b58-b8dd-40f2a31d9f94">


Graph from geometry

<img width="283" alt="Screenshot 2567-04-05 at 23 07 54" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/fb61c4ac-78a8-47a9-9171-1aafc11dc836">



## Step 5: design PLC by using EasyEDA

<img width="165" alt="Screenshot 2567-04-05 at 23 09 56" src="https://github.com/manmanagogo/01205381-2023-2/assets/115552356/feda9695-f457-4991-810c-ef7e91141c49">


## Conclusion

From an experiment in Filter Design, starting with designing in the Sonnet program first, then designing in the EasyEDA program to order the real board. By experiment Values ​​obtained
from simulation in the program It has a value similar to the real thing for which it was designed. There may be some fluctuations in the expected values ​​in some parts. from the expected design or where the legs are soldered into the copper of the L, causing the value to change.
