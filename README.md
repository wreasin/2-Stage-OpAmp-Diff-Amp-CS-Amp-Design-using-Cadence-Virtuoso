# 2 Stage OpAmp (Diff-Amp + CS-Amp) Design with Layout using Cadence Virtuoso
### 2 Stage OpAmp (Diff-Amp + CS-Amp) Design and Analysis With Layout Using Cadence Virtuoso

---
<!-- Cadence Project (Transient, DC, AC, Noise Response, Power Consumption (Average Power) With Layout) -->

I’m really glad to share that, this is my eighth project on __Cadence Virtuoso__. I am designing here a 2 Stage OpAmp (Diff-Amp + CS-Amp) Design and Analysis With Layout Using Cadence Virtuoso.

___Before I start explaining my project in details, you should know a few things !___     

### What is 2 Stage OpAmp (Diff-Amp + CS-Amp)?  
hfhhhfhhf.

### The Project details of mine :

I'm using 45nm GPDK :-

1. Three pMOS1v & Five nMOS1v.
2. Here I am doing five types of Analysis :  
    i ) Transient Response  
    ii ) DC Response  
    iii ) AC Response  
    iv ) Noise Response
    v ) Stability Analysis
3. I'm Calculated the Bandwidth, Power Consumption (Average Power) of this circuit using Calculator.
4. In Layout - Metals Used ( Metal1, Metal2 & Poly for gate )
   - The Layout done by following steps -  
   i) Floorplan ii) Placing iii) Routing iv) Verification
5. DRC and LVS clean (there are no error)  

So I designed a Schematic of the 2 Stage OpAmp (Diff-Amp + CS-Amp), where the whole thing is based on gpdk45nm. I have use 3 PMOS1v & 4 NMOS1v. I also designed a symbol of it, so that i can utilise that for further schematic creation.  

The below figure shows a 2 Stage OpAmp (Diff-Amp + CS-Amp) Circuit.  

![Scametic](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Scametic.PNG)
![Symbol](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Symbol.PNG)

#### Transient, DC, AC, Noise Response & Stability Analysis :
_Here I am doing five types of Analysis - Transient, DC, AC, Noise & Stability Analysis_.  
In DC and Transient Analysis i have measured Va, Vb & Vout as Voltage, and Current (I) in VDD node. In AC Analysis i have measured Va, Vb & Vout as Voltage Frequency and Current (I) Frequency in VDD node. For DC and Transient Analysis the plots of _Va_ , _Vb_ and _Vout_ shows the _voltages_, on the otherhand _VDD(I4)_ shows the _current (I)_. For AC Analysis the plots of _Va_ , _Vb_ and _Vout_ shows the _voltage frequency_, on the otherhand _VDD(I4)_ shows the _current (I) frequency_. 
![Symbol_Scametic](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Symbol_Scametic.PNG)
![output](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Transient_AC_DC_Noise%20Analysis.PNG) 

#### Calculating Power Consumption also Average Power of this circuit using Calculator. :  
Calculating Power Consumption Calculator for an 8T 1-bit Full Adder. The calculator allows you to calculate both the total power consumption and the average power of the circuit. By inputting relevant parameters, you can quickly determine the power requirements of the circuit, aiding in design and optimization processes.  
![All Power Consumption](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/All%20Power%20Consumption.PNG)
![Sum Carry_Aver_Power Consumption](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Sum_Carry_Aver_Power%20Consumption.PNG)
![Sum Power Consumption](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Sum%20Power%20Consumption.PNG) 
![Carry Power Consumption](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Carry%20Power%20Consumption.PNG)

#### Layout :
In Layout i have use Metal1, Metal2 and Poly layer for gate. I have use here X & Y snap spacing is 0.005m and also the minimum width of metal utilized for routing is 0.12.  
![Layout](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/Layout.PNG)

#### Design Rule Check (DRC)  
DRC is clean. There are no error in DRC.  
![DRC](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/DRC%20Cheack.PNG)

#### Layout Versus Schematic (LVS)  
LVS is clean. There are no error in LVS.  
![LVS](https://github.com/wreasin/8T-1-Bit-Full-Adder-With-Layout-Using-Cadence-Virtuoso./blob/main/Image/LVS%20Cheack.PNG)
