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
  ![Screenshot 2025-03-03 182044](https://github.com/user-attachments/assets/a779d09f-cdef-4901-9508-51ba2d0aa34d)

  
##  ID=0.45ma
##  ID=0.45ma
##  vicm=1.65V
## vicm=1.65V

## Transient  analysis:
  ##  Input Waveforms:
   ![Screenshot 2025-03-03 185554](https://github.com/user-attachments/assets/c8bb644c-d745-4865-b7c9-e32cdd8cd2f9)

   ##   Output Waveforms:
   ![Screenshot 2025-03-03 185622](https://github.com/user-attachments/assets/6ca62960-9f69-4321-8adb-db5ff95439f6)

   ##   Input & Output Waveforms
   ![Screenshot 2025-03-03 185925](https://github.com/user-attachments/assets/61a435c1-ce8c-43bf-9e61-8f4eff27ead3)

## AC analysis
   ![Screenshot 2025-03-03 193142](https://github.com/user-attachments/assets/fbccdbd3-a18f-4d00-9489-12cc5142d96f)

   ## Circuit 2 : 
   ![Screenshot 2025-03-03 193752](https://github.com/user-attachments/assets/c4c251fd-e6fa-4967-afbd-721e38ac6f74)

   ## DC analysis
   ![Screenshot 2025-03-03 182044](https://github.com/user-attachments/assets/d2e5eb08-88cf-42d5-ba51-910d5987b728)
   ##  ID=0.45ma
   ##  ID=0.45ma
   ##  vicm=1.65V
    ## vicm=1.65V

   ## Transient  analysis:
   ## Input Waveforms:
   ![Screenshot 2025-03-03 185554](https://github.com/user-attachments/assets/c8bb644c-d745-4865-b7c9-e32cdd8cd2f9)

   ##   Output Waveforms:
   ![Screenshot 2025-03-03 185622](https://github.com/user-attachments/assets/6ca62960-9f69-4321-8adb-db5ff95439f6)

   ##  Input & Output Waveforms
   ![Screenshot 2025-03-03 185925](https://github.com/user-attachments/assets/61a435c1-ce8c-43bf-9e61-8f4eff27ead3)

   ## AC analysis
   ![Screenshot 2025-03-03 193142](https://github.com/user-attachments/assets/fbccdbd3-a18f-4d00-9489-12cc5142d96f)

   ## Circuit 3 :
   ![Screenshot 2025-03-03 201952](https://github.com/user-attachments/assets/970e26a1-75f3-4045-8803-67e496df2135)

   ## DC analysis

   ![Screenshot 2025-03-03 185147](https://github.com/user-attachments/assets/b40d8f64-a805-491a-b9bd-d7e4c3291afe)
   ##  ID=0.45ma
   ##  ID=0.45ma
   ##  vicm=1.65V
   ## vicm=1.65V

   ## Transient  analysis:
     Input Waveforms:
   ![Screenshot 2025-03-03 185554](https://github.com/user-attachments/assets/c8bb644c-d745-4865-b7c9-e32cdd8cd2f9)

   ## Output Waveforms:
   ![Screenshot 2025-03-03 185622](https://github.com/user-attachments/assets/6ca62960-9f69-4321-8adb-db5ff95439f6)

   ## Input & Output Waveforms
   ![Screenshot 2025-03-03 185925](https://github.com/user-attachments/assets/61a435c1-ce8c-43bf-9e61-8f4eff27ead3)

   ## AC analysis

   ![Screenshot 2025-03-03 195221](https://github.com/user-attachments/assets/133158a1-3a67-436b-8294-6aea69a26047)



   


        




