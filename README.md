## Aim : Design and Analyze the MOS differential amplifier circuitfor the following specifications 

## Components Required :
N-MOSFET(nmos4),Resistors(3.5k,0.5k,voltage source)
## Definiton:
A differential amplifier is a type of electronic amplifier that amplifies the difference between two input voltages while rejecting any voltage that is common to both inputs. 
It is a fundamental building block in analog circuits, commonly used in operational amplifiers (op-amps) and instrumentation amplifiers.
 ## 1. Basic Principle
The differential amplifier operates on the principle of differential mode gain and common-mode rejection:
   1.Differential Mode: The amplifier amplifies the difference between two input signals.
    2.Common Mode: Signals that are common to both inputs (such as noise or interference) are ideally rejected.
Mathematically, the output voltage of an ideal differential amplifier is given by:
Vout =Ad(V1−V2)
Ad= Differential mode gain
V1=Non inverting Terminal
V2=Inverting Terminal
A basic differential amplifier circuit consists of two identical transistors (BJTs or MOSFETs) or operational amplifiers, forming a symmetrical configuration
3. Modes of Operation:A differential amplifier operates in two primary modes:
   
   (a) Differential Mode
    Inputs:V1=+V,V2=-V
    The output voltage is proportional to the difference between the inputs.
    Provides high gain.
   (b) Common Mode
   Inputs: V1=V2 (same signal applied to both inputs)
   Ideally, the output should be zero (common-mode rejection).
   Practical circuits have a Common-Mode Rejection Ratio (CMRR) to measure the effectiveness of common-mode noise rejection.
## Procedure :

1.Open the LTspice software, merge the library file for getting accurate values of NMOS.

2.Select the components which are needed to us like for circuit 1 we need 1.9k & 0.4k resistor,2 CMOSN, three voltage sources(1.2v,2.2v),ground from the components list.

3.Place them all components in necessory way which is helpfull, connect all the components as in given circuit .

4.Link the specification of list of properties of mosfet like threshold voltage, temperature etc.

5.Lets do the DC Analysis first by opting a simulation, we get .op so after placing it we will get the values of it, thet will displayed.

6.After that lets take Transient analysis of 5m cycle so in input and output waveforms in 5 complete cycle, so here we get and seperate and combined waveforms of input and output.

7.For AC analysis, we should do some changes like converting DC SOURCE to sinosoidal waveform (1.2,50m,1T),after that select the AC simulation from the given options of simulation after giving values of (Decade,20,01,1T). So we will get a output after placing node to output waveform .
## Circuit 1 : 
   ![Screenshot 2025-03-03 182032](https://github.com/user-attachments/assets/f4a71dd3-2725-45f5-8a47-11833991f2fa)
## DC analysis

     ![Screenshot 2025-03-03 182044](https://github.com/user-attachments/assets/cd4afe09-7fd0-4815-9d64-2514cf1ddbf6)
## Transient  analysis:
     ## Input Waveforms:
     
      ![Screenshot 2025-03-03 185554](https://github.com/user-attachments/assets/0db92f33-0a03-4d82-9189-e875bb43f12b)

     ## Output Waveforms:
     
        ![Screenshot 2025-03-03 185622](https://github.com/user-attachments/assets/be82d428-b96c-4b95-9d78-02b8e48ddca3)
        




