# jk_flip_flop

AIM:

To implement JK flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

JK Flip-Flop

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.


<img width="630" height="418" alt="image" src="https://github.com/user-attachments/assets/34b48bbd-70d1-4584-a07e-d01c31a467b6" />


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.


<img width="447" height="332" alt="image" src="https://github.com/user-attachments/assets/2522f360-b47b-443e-8757-3bc964cc9a22" />


Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State


<img width="628" height="533" alt="image" src="https://github.com/user-attachments/assets/42bc5b37-a54f-4d07-997d-566b28462699" />

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.


<img width="667" height="257" alt="image" src="https://github.com/user-attachments/assets/2c478c51-382d-4288-a14d-e1b393548c43" />


The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

Procedure

/* write all the steps invloved */

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by: R. Keerthika

RegisterNumber: 25017601

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS


