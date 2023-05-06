Download Link: https://assignmentchef.com/product/solved-eec180-lab5-design-and-implementation-of-a-priority-arbiter
<br>
A priority arbiter is an important circuit in networking applications, where the next packet to send is selected according to some Quality-of-Service policy that gives each packet a score.

In this lab you will design priority arbiters and use Verilog to implement them.

<strong>Prelab  </strong>

Read the lab carefully and show the paper designs for Part II and III.

<h1>I.  Priority Arbiter</h1>

A four-input priority arbiter is shown below, which accepts four inputs and outputs the index of the input with the largest value. For example, if the four inputs are 28, 58, 19, and 37, the arbiter should output 1 (Out1 = 0, Out0 = 1), because input 1 has the highest value, 58.

Fig. 1 Four-input priority arbiter design (See Page 193 and 194 from your textbook)

<h1>II.  Four-Input Priority Arbiter Design and Implementation</h1>

<ul>

 <li>Modify the design shown in Figure 1 to break the tie in favor of <u>higher-numbered</u> input for a four-input priority arbiter.</li>

 <li>Implement the design in Verilog.</li>

 <li>The size of the inputs, <strong>n </strong>should be Verilog parameter, so that the same design can be used to create priority arbiters of different size.</li>

</ul>







<h1>III.  Eight-Input Priority Arbiter Design and Implementation</h1>

<strong> </strong>

<ul>

 <li>Modify the priority arbiter shown in Fig. 1 to take eight inputs and implement your eight-input priority arbiter design in Verilog using magnitude comparators and MUX.</li>

 <li>You should break ties in favor of the lower-numbered input.</li>

</ul>

<strong> </strong>

<strong> </strong>

<h1>IV.  Testing</h1>

<strong> </strong>

<ul>

 <li>Write Verilog testbenches for both Part II and III.</li>

 <li>Verify your designs for n=8 and n=16 with at least 100 random test inputs. You can use the Verilog task $random to generate random numbers in your testbench.</li>

 <li>You must include test cases to verify the “ties” conditions.</li>

</ul>




<h1>V.  Synthesis</h1>




<ul>

 <li>Synthesize your design using Quartus</li>

 <li>Tabulate the <u>resources</u> used and <u>delay</u> for the priority arbiters for n=8 and n=16 in section II.</li>

 <li>Optimize your design to reduce the resources and delay [Extra Credit]. You can take an additional week to submit the extra credit.</li>

</ul>




<h1>VI.  Lab report</h1>

For your lab report, include the following:

<ul>

 <li>Paper designs for Part II and III.</li>

 <li>Complete Verilog source code.</li>

 <li>Simulation waveforms/screenshot of the transcript window from your functional simulation.</li>

 <li>Statement of contribution of each team member.</li>

</ul>


