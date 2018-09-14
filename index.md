---
layout: default
---


<h3>Hi! I am a mechanical engineer at Cornell University.</h3>

I will graduate with a PhD in 2019. I'm looking for interesting new projects to pursue - please contact me with opportunities at <u>rjs492@cornell.edu</u>

I hope the following information gives you a better idea of how I am qualified for a variety of engineering projects. I've tried to include descriptions on each image - just click on them!

<br>

<h2>I love building things!</h2>

<br>

<hr style="height:3px">
<h3>Doctoral research projects:</h3>
At Cornell, I was fortunate enough to be awarded a NSF Graduate Research Fellowship, which gave me the flexibility to research a variety of interesting topics. Generally, my research has focused on <u>thermal systems</u>. Click on the images below for more information on each of my recent projects.

<a href="/tiny">Solar thermal diagnostic system (TINY)<br><img src="assets/img/TINY400x150.png" style="border:1px solid black"></a>

<a href="/elastocaloric">Elastocaloric refrigeration<br><img src="assets/img/elastocaloric400x150.gif" style="border:1px solid black"></a>

<a href="/sma">Heat-driven shape memory actuators<br><img src="assets/img/SMA400x150.jpg" style="border:1px solid black"></a>

<br>
<br>
<hr style="height:3px">

<h3>Places I've worked:</h3>
I have a variety of professional experiences, both in industry and at universities. <u>I am a talented engineer and an adept research scientist</u>.

I worked with robotics at both Honda and Dow AgroSciences. It's hard for me to showcase my work from this topic because of IP limitations; however, I'd be happy to discuss the topic. I have experience with Motoman and EPSON 6-axis robots, vision algorithms for control, and process control for manufacturing.

<h4>
<ul>
  <li>Honda Engineering North America</li>
  <li>Dow AgroSciences</li>
  <li>Cornell University</li>
  <li>IMTEK, University of Freiburg, Baden-Württemberg, Germany</li>
  <li>Ohio State University</li>
</ul>
</h4>
<br>

<hr style="height:3px">

<h3>Engineering skillset:</h3>


<table class="talenttable">
  <tr>
    <td>
      <a href="assets/img/Crosssection.PNG" data-lightbox="image-1" data-title="This cross section shows the inside of the TINY diagnostic device. I designed all of the components pictured here (minus the standard parts). I also fabricated the first versions of the device in the machine shop. The center of the device is an optical measurement system which monitors fluorescence during a nucleic acid assay. The white material in the center is a phase change material, which is used to store heat isothermally. You can also see some of the printed circuit boards (also designed by myself) towards the bottom of the picture.">Mechanical design<br><img src="assets/img/Crosssection_small.png"></a>
    </td>
    <td>
      <a href="assets/img/Manufacturing1.jpg" data-lightbox="image-1" data-title="These are two parts I designed and machined myself. I use Solidworks for CAD, but have also used Autodesk Inventor and CATIA. I have 8+ years of experience using Solidworks and maching my own parts. These parts are for the elastocaloric refrigeration project. The part in the foreground is used to mount a linear actuator, while the other part holds a load cell.">Manufacturing<br><img src="assets/img/Manufacturing1_small.jpg"></a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="assets/img/Program.PNG" data-lightbox="image-1" data-title="This is the main loop for the elastocaloric refrigerator. What you can't see here is the host of functions the main loop calls to do things such as: update the load and position of the actuator; update thermocouple measurements; check for user input commands; and control fluid pumps. I wrote this in Arduino, which is really C but with a multitude of libraries available. I also am adept at programming in MATLAB and Python.">Programming<br><img src="assets/img/Program_small.png"></a>
    </td>
    <td>
      <a href="assets/img/PCB.PNG" data-lightbox="image-1" data-title="This is one of the PCBs I designed for the TINY system, made in EAGLE. There are a variety of fun components I designed into this board, such as: thermocouple amplifier, Teensy microcontroller, safety switch, MOSFET for heater control, MOSFET for reverse polarity protection.">Electronics<br><img src="assets/img/PCB_small2.png"></a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="assets/img/Thermal.png" data-lightbox="image-1" data-title="All of my doctoral research projects have implemented clever heat transfer and themodynamic principles. Pictured here is TINY being heated by an open flame. The device can also accept heat from sunlight or a cartridge heater (electrical). All three heat sources can be used with no effect on the diagnostic performance of the device. Making the system flexible to such a variety of heat sources was a difficult but interesting design challenge.">Thermal systems<br><img src="assets/img/Thermal_small.png"></a>
    </td>
    <td>
      <a href="assets/img/Mechsim.png" data-lightbox="image-1" data-title="I'm experienced with Finite Element Analysis using both Ansys and Solidworks. Here is a simulation I made to find the factor of safety for one of my actuator mounting pieces in the elastocaloric refrigeration project. Here I'm applying a load much larger than ever expected to be put on the piece, so the factor of safety is more than pictured.">Mechanical simulation<br><img src="assets/img/Mechsim_small.png"></a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="assets/img/ThermalSim.png" data-lightbox="image-1" data-title="This is a simulation I produced in COMSOL to determine how long TINY could stay isothermal if allowed to cool at room temperature. I used the simulation for initial design of the device, and later confirmed the results via experiment (right). I'm also performing simulations for my other projects: for example, I'm using Simulink to estimate expected stroke length from my heat-driven, shape memory alloy actuator.">Thermal simulation<br><img src="assets/img/Thermalsim_small.png"></a>
    </td>
    <td>
      <a href="assets/img/Sensors.jpg" data-lightbox="image-1" data-title="An S-beam load cell for measuring the tensile force on NiTi (Nitinol) wires used in the elastocaloric refrigeration project. This is 2.5 kip load cell. I'm using a 24-bit ADC that has an effective sampling rate of ~ 1 kHz. Rapid sampling is important so that I can tell the actuator to break at precisely the right time: high strain rates are essential for the largest temperature changes in the refrigerator, but overloading the sample is bad for material fatigue.">Sensors<br><img src="assets/img/Sensors_small.jpg"></a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="assets/img/Robotics.jpg" data-lightbox="image-1" data-title="I've implemented many safety features for the elastocaloric refrigerator. Here is a mechanical E-stop if the systems needs to absolutely be shut down rapidly. You can also see the safety enclosure I've built around the system. This is mostly unnecessary, but we plan for the worst. I have handled all the mechanical, electrical, and thermal design for this refrigerator. The large black object is a linear actuator with 3 inch stroke, 1.6 kip max dynamic load, and 0.7 inch/s speed. I've written the code for control of the actuator as well. What a fun system to build! (minus the inevitable hiccups) You can also see that I have machined all the mounting parts for a second actuator, which I am eager to implement.">Robotic systems<br><img src="assets/img/Robotics_small.PNG"></a>
    </td>
    <td>
      <a href="assets/img/Optics.PNG" data-lightbox="image-1" data-title="On the left is a simplified schematic showing how light travels through the TINY device. I used a centrally-located LED to illuminate multiple sample wells (because of space constraints), and there is an array of very sensitive photodiodes on a PCB placed beneath the samples to detect changes in both fluorescence and absorbance. On the right you can see a simplified transmission spectra for a dual-bandpass optical filter which makes it possible to measure multiple signals with no mechanical movement.">Optics<br><img src="assets/img/Optics_small.PNG"></a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="assets/img/Publication.PNG" data-lightbox="image-1" data-title="My work has been published in highly respected journals such as Nature Biomedical Engineering.">Publishing my work<br><img src="assets/img/Publication_small.png"></a>
    </td>
    <td>
      <a href="assets/img/Deployed.jpg" data-lightbox="image-1" data-title="I deployed my TINY system to Uganda during two field trials (one in 2016, another in 2017). The device performed flawlessly during the field trial - an accomplishment I am very proud of. With me in this picture are two of my colleagues from Weill Cornell Medicine in NYC. This picture was taken in Kampala, Uganda.">Deploying my work<br><img src="assets/img/Deployed_small.png"></a>
    </td>
  </tr>
</table>

<br>

<hr style="height:3px">
<h3>Professional interests (incomplete list):</h3>

<ul>
  <li>Energy</li>
  <li>Refrigeration (especially solid state)</li>
  <li>Automation</li>
  <li>Actuators (especially shape memory)</li>
  <li>Portable devices</li>
  <li>Design and manufacturing (both mechanical/electrical)</li>
  <li>Sensors/measurement</li>
  <li>Mechanisms</li>
  <li><i>Any engineering topic that is cutting-edge, unusual, innovative </i></li>
</ul>
<br>

<hr style="height:3px">
<h3>Hobbies:</h3>

I am a very self-motivated individual (it's easy to be motivated when having fun), and my work is important to me. However, I also have a variety of hobbies, and I value a balanced lifestyle.

<ul>
  <li>Camping</li>
  <li>Hiking</li>
  <li>Basketball</li>
  <li>Running</li>
  <li>Rock climbing</li>
  <li>Improv comedy</li>
</ul>

<p class="rec">
  <a href="assets/img/Canoe.jpg" data-lightbox="image-1" data-title="Summer 2018. Canoeing trip in Algonquin Provincial Park. A pleasant morning on Rain Lake."><img src="assets/img/Canoe_small.jpg"></a>
  &nbsp;
  <a href="assets/img/Paul.jpg" data-lightbox="image-1" data-title="August, 2018. This is Paul and I treating ourselves to ice cream on Cornell's campus. Paul was a student from Germany working with me during the summer of 2018. For two summers I recruited and mentored German engineering students as part of the DAAD/RISE Worldwide program. I also went to Germany myself in 2013 and completed a research internship as part of the DAAD/RISE program."><img src="assets/img/Paul_small.jpg"></a>
  &nbsp;
  <a href="assets/img/Basketball.jpg" data-lightbox="image-1" data-title="Saturday morning basketball is a tradition for many graduate students at Cornell. A great group of guys!"><img src="assets/img/Basketball_small.jpg"></a>
</p>
