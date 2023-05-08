Download Link: https://assignmentchef.com/product/solved-uwee538-homework-1-analog-circuits-for-sensor-systems
<br>
<h1>Problem 1: Circuit loading, filtering</h1>

Design the bandpass RC filter to achieve &gt;20dB attenuation at 1MHz and less than 0.1dB attenuation from 1 Hz to 10 kHz

<ol>

 <li>First, ignoring loading effects, determine 3dB frequencies (f<sub>3dB,HP</sub> and f<sub>3db,LP</sub>) that meet the specifications.</li>

 <li>With R<sub>s</sub> = 100Ω and R<sub>L</sub> = 10MΩ, choose R<sub>1</sub>, R<sub>2</sub>, C<sub>1</sub>, and C<sub>2</sub> to minimize loading effects<em>.</em></li>

 <li>Simulate the frequency response (V<sub>o</sub>/V<sub>s</sub>) in Ltspice and plot it together with the ideal response in MATLAB/Python.</li>

</ol>

<h1>Problem 2: Current sources, frequency response, loading</h1>

Use the circuit and variables (no values) for the following.

<ol>

 <li>Sketch the frequency response (magnitude and phase) V<sub>out</sub><em>/</em>I<sub>s</sub><em> for </em>Z<sub>L</sub> → .</li>

 <li>Sketch the frequency response (magnitude and phase) V<sub>out</sub>/I<sub>s</sub> together with the unloaded response (part a) for the two conditions

  <ol>

   <li>Z<sub>L</sub> = C<sub>L</sub></li>

   <li>Z<sub>L</sub> = R<sub>L</sub></li>

  </ol></li>

 <li>Sketch the transient response of <em>V</em><sub>out</sub> for I<sub>s</sub> as a current step from 0 to I<sub>max</sub> (Z<sub>L</sub> → ).</li>

</ol>

<h1>Problem 3: Sampling, settling, power dissipation</h1>

The clock waveform shown above is used to drive the switch open and closed (<em>clk</em> = 1 → switch closed, <em>clk</em> = 0 → switch open). <em>T<sub>clk</sub></em> is the clock period (50% duty cycle), where <em>T<sub>clk</sub></em> = 1/<em>f<sub>clk</sub></em>. <em>V<sub>in</sub></em> = 1V, <em>R</em> = 100 Ω, and <em>C</em> = 10 pF

<ol>

 <li>What is the maximum clock frequency, <em>f<sub>clk</sub></em>, that allows 0.1% settling precision of <em>V<sub>cap</sub></em> each period?</li>

 <li>Given this clock frequency, what is the average current delivered to the capacitor?</li>

 <li>Verify your answers to a) and b) using Ltspice. To do this using a DC source fo V<sub>in</sub>, you need to use an initial condition (0V) on <em>V<sub>cap</sub></em>. Include any relevant plots in your submission.</li>

 <li>Perform an AC simulation on the circuit in Ltspice (switch closed). Relate the frequency response to the settling time and include any relevant plots.</li>

</ol>





