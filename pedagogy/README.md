#### Please use the [reference](https://github.com/virtual-labs/ph3-exp-dev-process/blob/main/pedagogy/README.org) document to fill this template.  Follow the [link](https://github.com/virtual-labs/ph3-exp-dev-process/tree/main/sample/pedagogy) to view a sample pedagogy document.

## Pedagogy
<p align="center">


<br>
<b> Experiment : Name of the experiment	 <a name="top"></a> <br>
</p>

<b>Discipline |Electrical Engineering <b> 
:--|:--|
<b> Lab |	Analog Circuits and Systems Virtual Lab <b> 
<b> Experiment| Full Interactive Simulink Experiments (e.g., linearity/non-linearity test)   <b>  
 

<h4> [1. Focus Area](#LO)
<h4> [2. Learning Objectives ](#LO)
<h4> [3. Instructional Strategy](#IS)
<h4> [4. Task & Assessment Questions](#AQ)
<h4> [5. Simulator Interactions](#SI)
<hr>

<a name="LO"></a>
#### 1. Focus Area : Reinforce theoretical concept
This experiment focuses on visualizing and understanding the transition between linear and non-linear regions in amplifier behavior. It strengthens conceptual understanding of gain, feedback, signal clipping, and bandwidth using real-time simulations in Simulink.
#### 2. Learning Objectives and Cognitive Level


Sr. No |	Learning Objective	| Cognitive Level | Action Verb
:--|:--|:--|:-:
 1.|Identify the transition from linear to non-linear operation in amplifier circuits.| Understanding | Identify

 2.|Construct and simulate custom amplifier circuits using Simulink.| Applying | Construct

 3.|Analyze waveform outputs and frequency responses of simulated circuits .| Analyzing | Analyze

<br/>
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="IS"></a>
#### 3. Instructional Strategy 
###### Name of Instructional Strategy: Interactive Simulation-based Learning
Assessment Method: Embedded quiz questions, waveform analysis tasks, and scenario-based simulation challenges.
###### Assessment Method:   

<u> <b>Description: </b>    </u>
<br>
 Students will engage in a guided, interactive simulation using Simulink to construct amplifier circuits, adjust parameters, and observe real-time changes in waveform behavior. Key concepts like gain, clipping, saturation, and bandwidth are explored through experimentation. Learners must diagnose non-linear behavior through waveform analysis and answer reflective questions integrated within the simulation path.
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
1.| Identify linear/non-linear behavior | Gradually increase input amplitude and observe output waveform | At what point does the amplifier output begin to clip?

2.| Construct amplifier circuits | Build a common-emitter amplifier using Simulink blocks | What happens to gain when emitter resistance is increased.?

3.| Analyze waveform and frequency response | Perform transient and frequency response analysis | How does feedback resistor value influence bandwidth?

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
1 .| Select amplifier type and build circuit using Simulink blocks | Display interactive circuit with configurable parameters | Familiarize with amplifier configuration

2 .| Change input signal amplitude | Display real-time waveform of output | Visualize impact on output and detect non-linearity

3 .| Adjust circuit parameters (resistors, feedback loop) | Simulate updated waveform and performance | Understand parameter effect on gain and linearity

4 .| Run Bode plot analysis | Display frequency response | Assess gain variation across frequency range

5 .| Trigger fault conditions (e.g., excessive input) | Display clipped or distorted output | Emphasize importance of design limits and signal constraints
