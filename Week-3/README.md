# **4-Bit Full Adder**

## Logic:
We will be using the hierarchical layout concepts to build our 4-bit Full Adder, where we go from top to bottom conceptually but build the lowest level first and come upwards. The Heirarchy of a 4-bit Full Adder is shown ahead.

Stage 4: A 4-bit Full Adder consists of 4- bit full adders.Hence we need to build a Full Adder.

<p align="center">
  <img src="Pictures\4-bit-Ripple-Carry-Adder.png"> 
</p>

Stage 3: A full adder is made using 2-Half Adders and an OR gate. Hence, we need to build OR Gates and Half Adders.
<p align="center">
  <img src="Pictures\FullAdderUsingHalfAdders.png"> 
</p>

Stage 2: A half adder is built using XOR gates and AND gate. An OR gate can be built using a NOR and an Invertor (Exp 1 and 2)
<p align="center">
  <img src="Pictures\HalfAdder.png"> 
</p>

Stage 1: A XOR gate can be built using NAND Gates and an AND gate can be built using NAND and an Invertor (also EXP 1 amd 2)
<p align="center">
  <img src="Pictures\XOR.gif"> 
</p>
<hr/>

## OR Gate:

Circuit Design-
<p align="center">
  <img src="Pictures\OR.png"> 
</p>

IRSIM Window-
<p align="center">
  <img src="Pictures\OR-SIM.png"> 
</p>

Analyzer Window-
<p align="center">
  <img src="Pictures\OR-ANA.png"> 
</p>

## AND gate:

Circuit Design-
<p align="center">
  <img src="Pictures\AND.png"> 
</p>

IRSIM Window-
<p align="center">
  <img src="Pictures\AND-SIM.png"> 
</p>

Analyzer Window-
<p align="center">
  <img src="Pictures\AND-ANA.png"> 
</p>

## XOR Gate:

Circuit Design-
<p align="center">
  <img src="Pictures\XOR.png"> 
</p>

IRSIM Window-
<p align="center">
  <img src="Pictures\XOR-SIM.png"> 
</p>

Analyzer Window-
<p align="center">
  <img src="Pictures\XOR-ANA.png"> 
</p>

## Half Adder:

Circuit Design-
<p align="center">
  <img src="Pictures\HA.png"> 
</p>

IRSIM Window-

Analyzer Window-

## Full Adder:

Circuit Design-
<p align="center">
  <img src="Pictures\FA.png"> 
</p>

IRSIM Window-

Analyzer Window-

## 4-bit Full Adder:

Circuit Design-
<p align="center">
  <img src="Pictures\4bitFA.png"> 
</p>

IRSIM Window-

Analyzer Window-
