Download Link: https://assignmentchef.com/product/solved-cs2110-timed-lab2-finite-state-machines
<br>
In this timed lab, you will be creating a <strong>one-hot finite state machine </strong>in CircuitSim. This Finite State Machine will take in one 1-bit input, and it will output three 1-bit outputs. Diagrams and detailed instructions are provided below.

<h1><a name="_Toc3706"></a>3           Instructions</h1>

Please make sure you have <strong>CircuitSim 1.7.4 </strong>or <strong>CircuitSim 1.8.0 </strong>downloaded on your computer. It can be found <a href="https://www.roiatalla.com/public/CircuitSim/"><strong>here</strong></a><a href="https://www.roiatalla.com/public/CircuitSim/">.</a>

<h2><a name="_Toc3707"></a>3.1         State Transition Diagram</h2>

Figure 1: Transition diagram.

<h2><a name="_Toc3708"></a>3.2         Restrictions</h2>

Your main register MUST be named ”stateReg”, and the input / output pins we have given you in the skeleton file must not be renamed. Do not add any additional input / output pins other than the ones we have given you. Do not rename the sub-circuit we have given you. If you have issues, check out the ”Common Errors” section below.

If you have any questions on what you may not use then assume you can’t use it and ask a TA.

You are only allowed to use the following components in CircuitSim:

<ul>

 <li>Basic logic gates (AND, OR, NOT)</li>

 <li>Registers (for this assignment, exactly ONE)</li>

 <li>Wires, splitters/joiners, tunnels, constants, plexers</li>

</ul>

<h1><a name="_Toc3709"></a>4           Common Errors</h1>

Use the autograder’s output to determine where you have gone wrong. The names of the tests you fail should usually (but not always) point you in the right direction. Some silly errors and their remedies:

<ol>

 <li>Make sure you haven’t added extra any input / output pins to your circuit. It is common to confuseconstants with input pins, and probes with output pins.</li>

 <li>Make sure the input / output pins are named the way they were when we gave you the file. If youchange the names of the pins (including from upper-case to lower-case, etc), the autograder will not be able to feed input in, and read your circuit’s output.</li>

 <li>Make sure your register is named the way we have asked you to name it. The autograder locates yourregister based on its name.</li>

 <li>Make sure you haven’t changed the name of your sub-circuit. Keep it the same as what was given toyou.</li>

 <li>A common cause of short-circuits is two pins (on an AND gate, splitter, etc) being unintentionallyconnected. These are often hard to spot, since the pins are so close to each other, but if you zoom into your circuit you may find such an error and fix it.</li>

 <li>Sometimes the bits on your splitter may be not be ordered correctly. For example, if the bits areordered opposite to what you intended, you may fail all your tests (that depend on the splitter) since for each case, its complementary case is being tested.</li>

 <li>Make sure the names on your tunnels match. The tunnel labels are case-sensitive, and they do nottrim off whitespace. If two tunnels look the same but for some reason they aren’t connecting, there may be a ”space” hidden in the tunnel’s label.</li>

</ol>