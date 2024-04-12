<h1>Digital Thermostat System using Intel 8086 Microprocessor</h1>

<h2>Table of Contents</h2>
<ul>
    <li>Introduction</li>
    <li>Requirements Analysis and Problem Specification</li>
    <li>Design Overview</li>
    <li>System Procedure and Results</li>
    <li>Conclusion</li>
    <li>References</li>
</ul>

<h2 id="introduction">Introduction</h2>
<p>This project aims to automate temperature control using the 8086 Microprocessor and associated components. The system utilizes a temperature sensor interfaced with ADC to provide real-time temperature readings to the microprocessor. Based on the temperature data, the microprocessor controls the heating or cooling systems accordingly.</p>

<h2 id="requirements-analysis-and-problem-specification">Requirements Analysis and Problem Specification</h2>
<h3>Requirements:</h3>
<ul>
    <li>Maintain room temperature within specified ranges (Heating below 18°C, Cooling above 24°C).</li>
    <li>Control fan direction (left to right and right to left).</li>
</ul>

<h2 id="design-overview">Design Overview</h2>
<h3>Architecture:</h3>
<p>The system consists of the following components:</p>
<ul>
    <li>Microprocessor (Intel 8086)</li>
    <li>Temperature Sensor (LM35)</li>
    <li>ADC (Analog-to-Digital Converter)</li>
    <li>DAC (Digital-to-Analog Converter)</li>
    <li>Peripheral devices (fan, heater)</li>
</ul>

<h3>Hardware Components:</h3>
<ul>
    <li>Microprocessor (Intel 8086): Controls system operation and interfaces with external components.</li>
    <li>Temperature Sensor (LM35): Measures room temperature.</li>
    <li>ADC (Analog-to-Digital Converter): Converts analog temperature readings into digital values.</li>
    <li>DAC (Digital-to-Analog Converter): Generates control signals for heater or cooler.</li>
    <li>Latch (74HC373): Stores data temporarily for address buses.</li>
    <li>Latch (74HC245): Bidirectional buffer for data flow control.</li>
    <li>Darlington Transistor: Provides high current gain for driving loads.</li>
    <li>Stepper Motor: Moves in discrete steps for precise positioning.</li>
    <li>AC Motor: Converts electrical energy into mechanical motion.</li>
    <li>Bulb (Heating Element)</li>
</ul>

<h2 id="system-procedure-and-results">System Procedure and Results</h2>
<p>The microprocessor processes temperature data and activates heating or cooling based on programmed thresholds.</p>
<h3>Example Scenarios:</h3>
<ul>
    <li>If temperature rises above 24°C, the fan starts and adjusts direction using a stepper motor.</li>
    <li>If temperature falls below 18°C, the heating element activates to increase temperature.</li>
</ul>

<h2 id="conclusion">Conclusion</h2>
<p>The digital thermostat system successfully achieves temperature control using the Intel 8086 microprocessor and associated components. The project demonstrates practical application of temperature sensing, control logic, and interfacing techniques.</p>
<p>Future extensions could include:</p>
<ul>
    <li>Remote control for setting desired temperature.</li>
    <li>Integration of fire suppression and temperature alert systems.</li>
    <li>Addition of pushbuttons to control fan direction.</li>
</ul>

<h2 id="references">References</h2>
<ul>
    <li>PPI 8255 Interfacing with 8086 (eeeguide.com)</li>
    <li>ADC0804 ADC Pinout, Description, Features & Datasheet (components101.com)</li>
    <li>DAC0808 Pin Diagram, Features, Circuit, Working & Datasheet (components101.com)</li>
    <li>Stepper Motor Drive Circuit in Proteus ISIS - The Engineering Projects</li>
    <li>ULN2003A IC Working, Datasheet, Proteus Simulation, Its Use with Arduino as Relay, LED, Solenoid Driver (youtube.com)</li>
</ul>
