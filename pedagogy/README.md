#### Please use the [reference](https://github.com/virtual-labs/ph3-exp-dev-process/blob/main/pedagogy/README.org) document to fill this template.  Follow the [link](https://github.com/virtual-labs/ph3-exp-dev-process/tree/main/sample/pedagogy) to view a sample pedagogy document.

## Pedagogy
<p align="center">


<br>
<b> Experiment : Name of the experiment	 <a name="top"></a> <br>
</p>

<b>Discipline |Electrical Engineering <b> 
:--|:--|
<b> Lab |	Analog Circuits and Systems Virtual Lab <b> 
<b> Experiment|  	Simulation of Amplifier Circuits (custom circuit building) <b> 
 

<h4> [1. Focus Area](#LO)
<h4> [2. Learning Objectives ](#LO)
<h4> [3. Instructional Strategy](#IS)
<h4> [4. Task & Assessment Questions](#AQ)
<h4> [5. Simulator Interactions](#SI)
<hr>

<a name="LO"></a>
#### 1. Focus Area : Reinforce theoretical concept
The experiment helps students connect theoretical amplifier concepts—such as gain, feedback, linearity, and clipping—with practical outcomes through simulation.
#### 2. Learning Objectives and Cognitive Level


Sr. No |	Learning Objective	| Cognitive Level | Action Verb
:--|:--|:--|:-:
1.|Identify and explain the linear and non-linear behavior of amplifier circuits.|Understanding	|Explain
2.|Simulate amplifier circuits to test linearity and analyze outputs.|Applying	|Simulate
3.|Interpret simulation results to evaluate amplifier performance.|Analyzing	|Interpret

<br/>
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="IS"></a>
#### 3. Instructional Strategy 
###### Name of Instructional Strategy  :  Interactive Simulation-based Learning 
###### Assessment Method:   

<u> <b>Description: </b>    </u>
<br>
    Learners will engage with an interactive Simulink-based virtual environment where they can construct, simulate, and analyze amplifier circuits. Emphasis is on understanding how circuit configurations influence linearity and output behavior. Simulation runs will help visualize theoretical concepts and real-world constraints such as gain saturation and signal clipping.

<br/>
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="AQ"></a>
#### 4. Task & Assessment Questions:

  
<br>

Sr. No |	Learning Objective	| Task to be performed by <br> the student  in the simulator | Assessment Questions as per LO & Task
:--|:--|:--|:-:
1.|Identify and explain linear/non-linear behavior.	|Vary input signal amplitude and observe output waveform.|What happens to the output when input exceeds a certain threshold?
2.|Simulate amplifier circuits.	|Design a custom amplifier and run transient analysis.	|How does changing the feedback resistor affect gain?
3.|Interpret simulation results.|Compare output signals from linear and non-linear simulations.	|What does clipping in the output waveform indicate?


<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="SI"></a>

#### 4. Simulator Interactions:
<br>

Sr.No | What Students will do? |	What Simulator will do?	| Purpose of the task
:--|:--|:--|:--:
1.|Select amplifier type (e.g., common-emitter), and define parameters.	|Construct the circuit and display schematic.	|To enable circuit configuration and setup.
2.|Modify input signal amplitude and observe output.	|Simulate and display time-domain waveform.	|To visualize linear vs. non-linear output behavior.
3.|Change component values like resistor or capacitor.	|Update output dynamically.	|To understand parameter impact on amplifier performance.
4.|Run frequency response analysis.	|Plot Bode plot of gain vs. frequency.	|To assess bandwidth and frequency behavior.
