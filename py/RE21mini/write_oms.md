<h1> RobocadSim.RE21mini.write_oms(lift: float, big: float, small: float)  </h1>
  
<strong>write_oms</strong> function is used to transmit actions of OMS to robot  
  
<h2><strong> Inputs: </strong></h2> 
<strong><em>lift: </em></strong>Speed to lift motor  

<strong><em>big: </em></strong>Angle to big servo motor  
<strong><em>small: </em></strong>Direction of small servo rotation  
  
<h2><strong> Output: </strong></h2>
<strong><em>Null</em></strong> 

<h2><strong> Additional info: </strong></h2>
<ul>
<li><strong>Range of speed is from -50 to 50</strong></li>
<li><strong>Range of angles for big servo motors</strong></li>
<ul>
  <li><strong>RE21mini range is from 1490 to 1750</strong></li>
</ul>
<li><strong>Direction of small servo rotation</strong></li>
<ul>
  <li><strong>Open/Close 1400</strong> // depends on the robot</li>
  <li><strong>IDLE 1500</strong></li>
  <li><strong>Open/Close 1600</strong> // depends on the robot</li>
</ul>
</ul>
