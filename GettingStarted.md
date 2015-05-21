# Introduction #

Get the KKmulticontroller v5.5?
then start to play with it by following this guide.
`*`Please understand that this guide is written to supplement the official manual of KKmulticontroller board. Take your own risks!



# Before you start #

Please understand that it takes time and efforts to complete the whole setting. Do not suspect your KK board is defective unless you are really sure.




# What you need #
| **Name** | **Quantity** | **Remarks** |
|:---------|:-------------|:------------|
| KKmulticontroller | 1            | v5.5        |
| Radio System | 1            | At least 4 channels |
| ESC      | ->           | depends(tri/quad/hex/other) |
| Motors   | ->           | depends(tri/quad/hex/other) |
| Frame    | 1            | -           |
| Blade    | ->           | depends(tri/quad/hex/other) |
| Battery  | 1            | -           |
| Chargwe  | 1            | -           |




## Example configuration and price for reference ##
  * KKmulticontroller v5.5
  * WFLY 6 channels 2.4GHz Radio System
  * XXD 30A ESCs
  * XXD A2212 1000kV Motors
  * Full Glass-Fiber Quadcopter Frame
  * 1045 blades
  * ACE 11.1V 2200mAh 25C Lith Battery

<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/ctrlboard.png' width='200' height='148'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/rec.jpg' width='200' height='148'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/trans.jpg' width='200' height='148'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/escnmotor.jpg' width='200' height='148'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/1045.jpg' width='200' height='148'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/lcq400.jpg' width='200' height='148'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/ace.jpg' width='200' height='148'>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/rc301.jpg' width='200' height='148'>



<h1><b>FOR SAFETY, READ it</b></h1>
<ul><li>DO NOT install blades unless setting is completed.<br>
</li><li>Terminal +ve, -ve NEVER interchange! Lith Battery can be very dangerous</li></ul>


<h1>What is what</h1>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/clarboard.jpg'>


<h1>Test the KK board</h1>
Please load the firmware you need. You could refer to firmware transfer wiki page for more details.<br>
<br>
Here I use Quadrocopter, X mode<br>
<ul><li>Firmware: KKXcopter 1.0 Quad Firmware by Minsoo Kim</li></ul>

<h2>1. Connect receiver to KK board</h2>
<ul><li>Make sure the direction is correct!<br>
</li><li><code>[</code>Signal Vcc Gnd<code>]</code> or <code>[</code>Gnd Vcc Signal<code>]</code> ? DOUBLE CHECK IT!<br>
</li><li>Not only Check each pin!<br>
</li><li>Also Check which channel is AIL, ELE, THR, ROD!</li></ul>

<b>IT WONT WORK IF ANY STEP GO WRONG</b>


<h2>2. Connect 4 ESCs to KK board</h2>
<ul><li>Make sure the direction is correct!<br>
</li><li><code>[</code>Signal Vcc Gnd<code>]</code> or <code>[</code>Gnd Vcc Signal<code>]</code> ? DOUBLE CHECK IT!<br>
</li><li>Not only Check each pin!<br>
</li><li>Also Check which channel is which motor! It depends on which firmware you use!</li></ul>

<h2>3. Setting transmitter channels</h2>

<table><thead><th> <b>CHANNEL</b> </th><th> <b>Aileron</b> </th><th> <b>Elevator</b> </th><th> <b>Throttle</b> </th><th> <b>Rudder</b> </th></thead><tbody>
<tr><td> JR/SPEKTRUM    </td><td> REVERSE        </td><td> REVERSE         </td><td> NORMAL          </td><td> REVERSE       </td></tr>
<tr><td> WFLY/FUTABA    </td><td> NORMAL         </td><td> NORMAL          </td><td> REVERSE         </td><td> NORMAL        </td></tr>
<tr><td> HITEC          </td><td> NORMAL         </td><td> REVERSE         </td><td> NORMAL          </td><td> NORMAL        </td></tr>
<tr><td> Others         </td><td> ?              </td><td> ?               </td><td> ?               </td></tr></tbody></table>

- Make sure you do not have any mixing switches on your Transmitter enabled.<br>
<br>
IT WONT WORK IF ANY STEP ABOVE GO WRONG<br>
<br>
<br>
<br>
<h2>4.Stick Centering</h2>


<h3>1. set all to middle (50%)</h3>
<img src='http://dl.dropbox.com/u/23905563/projects/copter/wiki/getting%20started/centering.jpg'>

<h3>2. set YAW gain to minimal (0%), CLOCKWISE!!!</h3>

<h3>3. Put throttle stick to Full (100%) and turn on the transmitter</h3>

<h3>4. Power up the quadrocopter (receiver and kk board).</h3>
You will hear 3 beeps from ESCs and it beeps continuously with 3 states.<br>
<ul><li>beep<br>
</li><li>beep beep<br>
</li><li>beep beep beep</li></ul>

When the state is "beep beep", Put throttle stick to 0%.<br>
<br>
You will hear beep to confirm the choice.<br>
<br>
<h3>5. Restart and try to Arm you KK board.</h3>

<h1>Arming / Unarming</h1>
<a href='http://www.youtube.com/watch?feature=player_embedded&v=YoFoFq6s47w' target='_blank'><img src='http://img.youtube.com/vi/YoFoFq6s47w/0.jpg' width='425' height=344 /></a>