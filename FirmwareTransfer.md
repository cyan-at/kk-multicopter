# What you need #
notice that power is supplied directly from the AVR programmer. No external power supply is required.


## Hardware ##
  * AVR USB Programmer **1
  * 10p-6p Cable**1

<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/firmware%20transfer/4.jpg' width='320' height='240'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/firmware%20transfer/5.jpg' width='320' height='240'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/firmware%20transfer/1.jpg' width='320' height='240'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/firmware%20transfer/2.jpg' width='320' height='240'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/firmware%20transfer/3.jpg' width='320' height='240'>

<h2>Software</h2>
<ul><li>kk flashtool</li></ul>

Please visit <a href='http://lazyzero.de/en/modellbau/kkmulticopterflashtool'>kk flash tool</a> flashing tutorial.<br>
<br>
Demo Video on WinXp<br>
<br>
<a href='http://www.youtube.com/watch?feature=player_embedded&v=CoaV_h7XSRE' target='_blank'><img src='http://img.youtube.com/vi/CoaV_h7XSRE/0.jpg' width='425' height=344 /></a><br>
<br>
<br>
Demo Video on Mac from Die Molls<br>
<br>
<a href='http://www.youtube.com/watch?feature=player_embedded&v=qhwIkf1620E' target='_blank'><img src='http://img.youtube.com/vi/qhwIkf1620E/0.jpg' width='425' height=344 /></a><br>
<br>
<h1>Download Firmware</h1>

According to the firmware <a href='http://www.kkmulticopter.com/index.php?option=com_content&view=category&id=58:firmware-downloads&Itemid=65&layout=default'>download</a> page of kk multicopter's web, there are total 12 firmwares available.<br>
<br>
Download the one you need.<br>
MCU of the black version is atmega168.<br>
<br>
Skip this part "Download Firmware" if you use kkmulticopterflashtool.<br>
<br>
(kkmulticopterflashtool does not require users download firmware manually)<br>
<br>
<br>
<h1>Download flash tool</h1>

kkmulticopterflashtool is highly recommended<br>
Benefits :<br>
<ul><li>No need to set fuses<br>
</li><li>No need download firmware manuanlly<br>
</li><li>Compatible with almost all USBASP<br>
</li><li>Support Mac OSX, Linux and Windows</li></ul>

<a href='http://lazyzero.de/en/modellbau/kkmulticopterflashtool'>Download here</a>


<h1>1. connect the usbasp adapter</h1>
<h1>2. install the usbasp driver (if not installed)</h1>
For Windows: <a href='http://www.fischl.de/usbasp/'>http://www.fischl.de/usbasp/</a>
<h1>3. run the kk flash tool (.cmd)</h1>
<h1>4. connect to kk board</h1>
Confirm the direction!<br>
<h1>5. set options</h1>
choose "usbasp", "blackboard", and the firmware you need.<br>
<h1>6. Program it</h1>
Watch the Demo Video on WinXp for step by step tutorials<br>
<br>
<h1>Debug/Problem/Error</h1>
If you see your device signature = 0x1e940b while expected signature = 1E 94 06, you should tick FORCE FLASHING. (device id of atmega168 & atmega168pa)