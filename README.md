# engin341-lab-4-state-machines-solved
**TO GET THIS SOLUTION VISIT:** [ENGIN341 Lab 4-State Machines Solved](https://www.ankitcodinghub.com/product/engin341-lab-4-state-machines-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101258&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ENGIN341 Lab 4-State Machines Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Overview

</div>
</div>
<div class="layoutArea">
<div class="column">
Lab 4 – State Machines

</div>
</div>
<div class="layoutArea">
<div class="column">
In this lab students will use State Machines to design a Traffic Light Controller for an intersection with a main street, a side street, and a pedestrian crossing. The resulting output will be displayed using a series of LEDs on a proto-board connected via ZYBO PMOD ports.

Figure 1. Traffic Light Diagram

Traffic Light A should consist of 3 lights: Green (Ga), Yellow (Ya), and Red (Ra) Traffic Light B should consist of 3 lights: Green (Gb), Yellow (Yb), and Red (Rb) The Pedestrian Crossing should consist of 2 lights: White (Ww) and Red (Rw)

</div>
</div>
<div class="layoutArea">
<div class="column">
NOTE FOR 2021: You do NOT need to submit a report for this lab. You only need to build and

</div>
</div>
<div class="layoutArea">
<div class="column">
implement the design. Your grade will be based on the lab demo (in class) and your submitted

</div>
</div>
<div class="layoutArea">
<div class="column">
project code.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The normal repeating sequence of operation for each of the three lights should be:

Table 1. Traffic Light Sequences, When one light is Green, Yellow, or White, the others must be Red.

</div>
</div>
<div class="layoutArea">
<div class="column">
Street A

Green Yellow Red Red Red Red

The timing of this sequence will be:

</div>
<div class="column">
Street B Pedestrian

Red Red

Red Red Green Red Yellow Red

Red White Red Red

</div>
</div>
<div class="layoutArea">
<div class="column">
Street A

Green – 4 sec Yellow – 2 sec Red – 10 sec

</div>
<div class="column">
Street B

Green – 3 sec Yellow – 1 sec Red – 12 sec

</div>
<div class="column">
Pedestrian

White – 2 sec

Red – Flashes 4 seconds at 1Hz, then solid 10 sec

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 2. Traffic Light Sequence Timing

</div>
</div>
<div class="layoutArea">
<div class="column">
A Maintenance Mode will also be implemented. When Maintenance Mode is active, all three lights (R, Y, G) for each traffic light (A, B, P) should flash at 1Hz. When Maintenance Mode is switched off, all lights should reset to the starting mode of (Ga, Rb, Rw).

Extra Credit: Modify your design so that the Pedestrian Crossing only occurs when a “walk” button is pressed. In this case, the main sequence should only cycle through the sequence below when operating as normal. You will use the onboard pushbuttons to determine when walk has been pressed and released. Once this occurs, enable an on-board LED to indicate that the Pedestrian crossing is enabled. At the end of the next sequence, the walk sequence described in Tables 1 and 2 should occur. After the walk sequence, the on-board LED should turn off and the sequence should return to the sequence below.

</div>
</div>
<div class="layoutArea">
<div class="column">
Street A

Green Yellow Red Red

</div>
<div class="column">
Street B Pedestrian

Red Red

Red Red Green Red Yellow Red

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Lab Work

<ol>
<li>Design a state graph for the Traffic Light Controller, then convert this to a State Machine Chart. State transitions will automatically occur after the specified delay time.

For a review of State Graphs and State Machine Charts, refer to Chapter 5, Section 5.1 in your text book.</li>
<li>Write a VHDL file that implements your state graph.
<ol>
<li>Your file should have 3 inputs:
i. Clk

<ol start="2">
<li>Rst – Reset should return your traffic lights to the initial state
(Ga, Rb, Rw)
</li>
<li>Mode – When Mode = 1, your Traffic Controller should enter
Maintenance Mode, When Mode is switched to ‘0’, your Traffic

Controller should reset to the initial state (Ga, Rb, Rw)
</li>
</ol>
</li>
<li>Your design should have 8 outputs:
<ol>
<li>StreetA (3 bits)

1. Ga – Green light for traffic light A 2. Ya – Yellow light for traffic light A 3. Ra – Red light for traffic light A</li>
<li>StreetB (3 bits)

1. Gb – Green light for traffic light B 2. Yb – Yellow light for traffic light B 3. Rr – Red light for traffic light B</li>
<li>Pedestrian (2 bits)

1. Ww – White light for walk sign/pedestrian crossing light 2. Rw – Red light for walk sign/pedestrian crossing light</li>
</ol>
</li>
</ol>
</li>
<li>Write a top level Lab4 module that connects your Traffic Controller, generic clock divider, and any other modules you choose to implement.</li>
<li>Design the constraints file using the I/O Planning tool.</li>
<li>Construct the Traffic Light circuit using the provided LEDs, resistor arrays, and a
breadboard. Connect the circuit to a ZYBO PMOD using jumpers/wires, according to your constraints. Make sure your lab report includes a detailed wire list and circuit implementation diagram for your constructed circuit.
</li>
</ol>
Deliverables

Your Lab 4 project directory, containing all sources, simulation waveforms, bit files and Lab 4 Report, are to be turned in as a zip file labeled “ENGIN341_LAB4_LastName_FirstName.zip”.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Part 1. State Graphs

You have been given some room for creativity with this lab. The main requirements are that the “Traffic Lights” your program controls must follow the sequence given with the specified timing, and it must implement a maintenance mode.

With this in mind, you can approach the problem in a couple of different ways. You could have a single large state machine that controls all three sets of lights, or a state machine for each set of lights. Whichever direction you go in, make sure that it is reflected in your FSM graph, and then your ASM chart. A simple example of a state graph and its state machine chart equivalent are shown below in Figures 2 and 3.

Figure 2. A simple Finite State Machine (FSM) Graph.

Figure 3. An Algorithmic State Machine (ASM) Diagram Equivalent of the FSM in Figure 1.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Part 2. State Machines in VHDL

In VHDL, State Machines are implemented inside processes sensitive to a clock and/or a reset signal, using a combination of ‘if’ and ‘case’ statements. To the right is an example of a VHDL implementation of the simple State Machine shown in Figures 1 and 2.

The first line to take note of is the “TYPE statetype is (S0, S1);”. This is a TYPE declaration, and its purpose is to create a new enumerated data type. In this case, we have created a new data type called statetype, which only has two enumerated values, S0 and S1, equivalent to the integer values of 0 and 1 respectively. Any signals/variables that are declared as statetype can only assume one of the two (S0 or S1) enumerated values. For example, on the next line, is a signal declaration, “SIGNAL state : statetype;”. We have now created an internal signal of type statetype, which can change its value between S0 and S1. The state signal is a state register, because it only changes on a clock edge, and is used to store the present state value. The next state value of the state register is determined within the case statement inside the FSM process, based on conditional statements encapsulated by if/elsif/else statements.

This method of state encoding using

enumerated data types is called enumerated

state encoding. Rather than explicitly encoding

each state to a series of bits, which yields hard-

to-read VHDL code, especially for large FSMs, using enumerated state encoding allows Vivado’s Synthesis tool to set the actual state bit encodings according to the synthesis options at synthesis time.

The X_Out process (sensitive only to the state signal, which in turn changes only on a rising clock edge) defines the behavior of the output signal x. This is an example of a Moore-type state machine. The output of Mealy-type state machines would be sensitive to both the current state and the explicit state machine inputs.

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Part 3. Top Level Design Implementation

Your top level file should, at a minimum, contain modules for your clock divider and traffic controller. You can either directly connect the output of your Traffic Controller module to the output of your Top level file. Or you can implement an LED driver.

Part 4. Designing the Constraints

When designing your constraints file, make sure to consider which PMOD connector on the ZYBO you will be using. This will affect your pin assignments.

This design contains three inputs. For your mode input, you should use SW0 on the ZYBO, and for the reset, you can use one of the onboard buttons.

Part 5. Connecting to the ZYBO PMOD Ports

You are expected to put together a “Traffic Light” circuit, containing a set of LEDs for Street A, Street B, and the Pedestrian Crossing. This is a simple circuit, but you are also expected to connect this circuit via jumpers/wires to one of the PMOD ports on the ZYBO.

Figure 4. Port Numbering for PMOD Connectors

As shown in the ZYBO Reference Manual, a single PMOD connector has 12 ports. The ports you should be using are J1-J4, and J7-J10, as well as either J5 or J11 for your ground. J6 or J12 provide Vcc.

It is important that your circuit wiring and connection to the PMOD ports matches your constraint files. Refer to the ZYBO Reference Manual for the pin numbers of whichever set of PMOD ports you use.

</div>
</div>
</div>
