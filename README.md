# Rust Electric Circuits
This is a collection of Rust Electrical diagrams that can be used in the game Rust in order to help more securely defend your base.</br>
My goal is to help others that are new to rust electricity or perhaps seasoned players looking for more advanced wiring diagrams.</br>
Feel free to send me a message if you see anything that could be improved on, have questions, or would like me to review something you are working on

## Diagram Links
* [Bases](bases/)
* [Batteries](batteries/)
* [Lights](lights/)
* [Tesla Coils](teslacoils/)
* [Timers](timers/)

## Popular Circuit Designs:
### 2 Battery Backup Circuit with Minimal Power Draw
<i>(Approximately 8 Hours Of 100 rW Maximum Usage)</i></br>
![BackupBattery-2Batteries](batteries/images/BackupBattery-2Batteriesv2.png)
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=b75b8f5cf1336f12edf6e280d006b47f)
* [Github Link To Battery Diagrams](batteries)
* [XML Export](batteries/xml/BackupBattery-2Batteries.xml)

### Advanced Automatic Lights Circuit
![AdvancedAutoLights](lights/images/AdvancedAutoLightsv2.png)
This advanced automatic lighting lets you control roughly how dark you want the lights to come on by setting a required minimum amount of draw (4 rW).</br>
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=5cb2fdf4600dbf3edd42de5d13f5fa75)
* [Github Link To Lighting Diagrams](lights)
* [XML Export](lights/xml/AdvancedAutoLights.xml)

## Extreme Parallel Battery Circuit - 2 Batteries
![ExtremeParallelBatteries-2](batteries/images/ExtremeParallelBatteries-2.png)
Due to the way Root Combiners work only allowing energy from a main power source such as a windmill or a battery,</br>
you can create transfer batteries to re-combined energy.  It comes at a cost of 30% energy loss per large battery.</br>
For each large battery you add to this circuit, you get roughly 70 rW of energy (1 medium, and 2 small).</br>
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=27818aeb23837a8d121852b6402d36d3)
* [Github Link To Battery Diagrams](batteries)
* [XML Export](batteries/xml/ExtremeParallelBatteries-2.xml)

### 4 Story Base Defense v1.0
![4StoryBaseDefesnev1.0](bases/images/4StoryBaseDefensev1.0.png)
This is a base layout for a solo base with a goal to have minimal power draw and no windmills as to not draw too much attention.</br>
The sensors are all wired to draw additional power from the battery including a secondary battery to supply the tesla coils each 33 rW.</br> 
The system can sustain the full load of systems with some additional room to overprovision the rW.</br>
Additionally it includes a counter to let me know how many people walked by while I was out with a reset button when I get back on the server.</br>
Finally it includes automatic heating and lighting.  This is enough to scare most raiders though not enough for a full on rocket attack.</br>
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=fd7c82fead5fe723aac485fc93aa125f)
* [Github Link To Base Design Diagrams](bases)
* [XML Export](bases/xml/4StoryBaseDefensev1.0.xml)

### Fireworks Display - Staggered Timers
![FireworksDispaly](timers/images/FireworksDisplay2.png)
The following Circuit uses the igniters on a staggering setup to ignite fireworks on 5, 20, and 45 seconds after hitting the button.</br>
This circuit could be used for anything you need to happen after a certain amount of time once you hit a button.</br>
The Max timer must be set longer than the igniter timers</br>
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=44cda47c2666384e6310b578fd08d657)
* [Github Link To Timer Design Diagrams](timers)
* [XML Export](timers/xml/FireworksDisplay.xml)