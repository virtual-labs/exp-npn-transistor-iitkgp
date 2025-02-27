## Theory
**Introduction:**  
Bipolar junction transistor (BJT) is one of the most widely used semiconductor devices in manufacturing integrated circuits and electronic components. Because of its superior speed performance, such a device has found wide applications in high-speed switching and digital electronics systems. The conventions for terminal naming, voltage and current notations, and the various regimes of operation for an npn BJT are all shown in Figure 1:  
  <div align="center">
<img src="images/man1.jpg"/>

**Fig. 1.Circuit diagram**
  </div>
  
Important note: For all measurements, hold V<sub>BE</sub> between 0 and 0.9 V, and V<sub>CE</sub> between 0 and 5 V.  
  
In this experiment, you will characterize the current-voltage characteristics of an npn bipolar junction transistor (BJT) using the IIT-Kharagpur Lab-on-Demand. This experiment involves measurement of current-voltage characteristics (Output characteristics). Typical output characteristics are shown in Figure 2. </br>

<div align="center">
<img src="images/man2.jpg"/>

**Fig. 2. Circuit diagram**
</div>
  
**About BJT**  
A Bipolar Junction Transistor, or BJT is a three terminal device having two PNjunctions connected together in series. Each terminal is given a name to identify it and these are known as the Emitter (E), Base (B) and Collector (C). There are two basic types of bipolar transistor construction, NPN and PNP, which basically describes the physical arrangement of the P-type and N-type semiconductor materials from which they are made. Bipolar Transistors are "CURRENT" Amplifying or current regulating devices that control the amount of current flowing through them in proportion to the amount of biasing current applied to their base terminal. The principle of operation of the two transistor types NPN and PNP, is exactly the same the only difference being in the biasing (base current) and the polarity of the power supply for each type.  
  
**Transistor Configurations and Characteristics:**  
There are three possible configurations possible when a transistor is connected in a circuit: (a) Common base, (b) Common emitter (c) Common collector. We will be focusing on the Common emitter configurations in this experiment. The behaviour of a transistor can be represented by d.c. current-voltage (I-V) curves, called the static characteristic curves of the device. The three important characteristics of a transistor are: (i) Input characteristics, (ii) Output characteristics and (iii) Transfer Characteristics. These characteristics give information about various transistor parameters, e.g. input and out dynamic resistance, current amplification PNP NPN factors, etc.  
  
**Common Emitter Transistor Output Characteristics**  
The variation of the collector current I<sub>C</sub> with the collector-emitter voltage V<sub>CE</sub> is called the output characteristic. The plot of I<sub>C</sub> versus V<sub>CE</sub> for different fixed values of IB gives one output characteristic. Since the collector current changes with the base current, there will be different output characteristics corresponding to different values of IB. Output Dynamic Resistance (ro): This is defined as the ratio of change in collector-emitter voltage (Δ V<sub>CE</sub>) to the change in collector current (Δ I<sub>C</sub>) at a constant base current IB. The high magnitude of the output resistance (of the order of 100 kW) is due to the reverse biased state of this diode.

  <div align="center">
<img src="images/formula.jpg"/>
 
<img src="images/oc.jpg"/>
 
**Fig. 3. characteristic graph**
</div>
  
**Output characteristics:**  
Plot V<sub>CE</sub> Vs I<sub>C</sub>, for different IB and determine the output dynamic resistance in each case at suitable operating points in the active region.  

<div align="center">
<img src="images/inout.png"/>

**Fig. 4. comparision**
</div>
  
**RESULT**  
Thus the input and output characteristics of an NPN transistor in Common Emitter mode is studied using pspice simulation. Input characteristics: V<sub>BE</sub> Vs I<sub>B</sub>, for different V<sub>CE</sub> and determine the input dynamic resistance in each case at suitable operating points. Output characteristics: V<sub>CE</sub> Vs I<sub>C</sub>, for different IB and determine the output dynamic resistance in each case at suitable operating points in the active region.  
  
**Secondary Sweep :**  
<div align="center">
<img src="images/ssgraph.jpg"/>

**Fig. 5. instrument output graph**
</div>
 <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3.2.2/es5/tex-mml-chtml.js"></script>    
 
