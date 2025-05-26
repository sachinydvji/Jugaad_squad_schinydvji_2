#### Please use the [reference](https://github.com/virtual-labs/ph3-exp-dev-process/blob/main/storyboard/README.org) document to fill this template. Follow the [link](https://github.com/virtual-labs/ph3-exp-dev-process/tree/main/sample/storyboard) to view a sample storyboard document. 



## Storyboard
Experiment 1: Full Interactive Simulink Experiments (e.g., linearity/non-linearity test)


### 1. Story Outline

1. Story Outline
This experiment is designed to provide learners with an interactive platform where they can simulate amplifier circuits using Simulink. The core learning goal is to help students visualize and understand the behavior of amplifiers under different conditions—linear and non-linear—by altering parameters like gain, input amplitude, and component values.

The simulation provides a real-time response of the circuit, helping students detect phenomena such as signal clipping, saturation, and gain deviations. The interface is intuitive and enables both novice and experienced users to engage with the system by designing, simulating, and analyzing amplifier circuits through a structured pathway of experimentation.

### 2. Story
In this experiment, the learner enters a virtual lab built on Simulink’s visual interface. They are introduced to amplifier circuits and begin by selecting one of the common configurations (e.g., common-emitter, op-amp non-inverting amplifier). A visual schematic is presented, and the user is allowed to configure values such as resistances, input signal amplitude, and frequency.

After defining the parameters, the learner runs a simulation that displays the input and output waveforms. By modifying the input signal and observing output responses, the learner explores linear and non-linear regions of operation. The system gives real-time feedback, including plots, performance metrics, and hints in case of incorrect setup.

Over the course of the experiment, the learner is challenged with tasks like matching a given frequency response, determining gain cutoff, and identifying when and why signal clipping occurs.



#### 2.1 Set the Visual Stage Description:
When users enter the simulator, they see:

1.A circuit-building interface with drag-and-drop components (resistors, capacitors, op-amps, signal generators).

2.A live waveform viewer (time and frequency domain).

3.A side panel to input or change values like resistance, input voltage, or frequency.

4.Simulation controls: Run, Pause, Reset.

5.Hint/help system toggle and progress tracker.



#### 2.2 Set User Objectives & Goals:
The user will:

Build a simple amplifier circuit using Simulink blocks.

Configure component values and input signals.

Observe the linear and non-linear behavior through simulation.

Analyze waveform output to derive gain, bandwidth, and signal integrity.

Complete tasks such as determining clipping points and calculating linear range.



#### 2.3 Set the Pathway Activities:
Select the amplifier topology from a menu.

Configure the schematic using component blocks and parameters.

Define the input signal (sine wave) parameters.

Run the simulation and observe time-domain waveforms.

Adjust input values and re-run to detect clipping and saturation.

Answer simulation-based questions such as gain calculation and signal distortion points.

Complete quiz challenges tied to simulation results.




##### 2.4 Set Challenges and Questions/Complexity/Variations in Questions:
Challenge 1: Detect the threshold where amplifier shifts from linear to non-linear behavior.

Challenge 2: Calculate gain using simulation data.

Challenge 3: Compare multiple circuits for signal fidelity.

Challenge 4: Achieve a target frequency response by adjusting circuit parameters.

Variations in question difficulty depending on prior performance (adaptive questions).



##### 2.5 Allow pitfalls:
Users who ignore setting correct resistor values may experience distorted outputs.

Incorrect feedback configuration may lead to unstable or zero gain.

If a user inputs a signal with too high amplitude, they will experience clipping and must understand why.

A help/hint system is in place but penalizes score/marks if overused.



## 2.6 Conclusion:

At the end of the experiment:

The system summarizes performance: time taken, correct responses, hints used.

Feedback includes: gain accuracy, correct circuit implementation, and output waveform match.

Users reflect on their understanding of linear vs. non-linear operation and practical amplifier behavior.

A downloadable report is generated with user performance and learning outcomes.


##### 2.7 Equations/formulas: NA
Type equations here : (Guide : ( a separate sheet having equations / programs for the lab exper3ment to be shared along with the Story submissions (1) . You can mark it as numerical reference numbers within the story narration (like we cite in the research papers) and then separately share these equations/programs sheets as a reference, do not include the equations as a whole in the narration))
Tool can be used to integrate formula in Markdown <b> [here](http://latex.codecogs.com/eqneditor/samples/example3.php) </b>


### 3. Flowchart
Link to flow chart Here : Store in the  /flowchart folder within pedagogy folder in your repo
<br>
(Guide :The lab proposer should extract logic from the story, prepare a flowchart from the story narration and write the algorithm to execute the black box.  use Google Drawings https://docs.google.com/drawings/ (send the link to your flowchart and also attach .png by exporting it )

### 4. Mindmap
 Link to mindmap here : Store the mindmap in both .mm & .png extension in the  /mindmap folder and include link of only .pdf verison here
 <br>
 (Guide : An elaborate mind map (connecting all the points in the experiment flow ) should be prepared and submitted by the lab proposer. The mind map should be a clear and detailed document that takes into account all minute intri5acies involved in the development of virtual lab. The mindmap should be self-content and any developer across the globe should be able to code it with all those details. using only FreeMind http://freemind.sourceforge.net/wiki/index.php/Main_Page (send the .png file and also the original .mm extension project file. )

### 5. Storyboard

Link the storyboard (.gif file ) in here :
(Guide: This document should include sketching and description scene wise (duration, action, description). Software to be used for storyboarding : https://wonderunit.com/storyboarder/ (Its a FOSS tool).
