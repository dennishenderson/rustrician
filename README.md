# Rust Electric Circuits
This is a collection of Rust Electrical diagrams that can be used in the game Rust in order to help more securely defend your base.</br>
My goal is to help others that are new to rust electricity or perhaps seasoned players looking for more advanced wiring diagrams.</br>
Feel free to send me a message if you see anything that could be improved on, have questions, or would like me to review something you are working on

## Popular Circuit Designs:
<b>2 Battery Backup Circuit with Minimal Power Draw</b></br>
<i>(Approximately 8 Hours Of 100 rW Maximum Usage)</i></br>
![BackupBattery-2Batteries](batteries/images/BackupBattery-2Batteriesv2.png)
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=b75b8f5cf1336f12edf6e280d006b47f)
* [Github Link To Battery Diagrams](batteries)
* [XML Export](batteries/xml/BackupBattery-2Batteries.xml)

## Advanced Automatic Lights Circuit
![AdvancedAutoLights](lights/images/AdvancedAutoLightsv2.png)
This advanced automatic lighting lets you control roughly how dark you want the lights to come on by setting a required minimum amount of draw (4 rW).</br>
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=5cb2fdf4600dbf3edd42de5d13f5fa75)
* [Github Link To Lighting Diagrams](lights)
* [XML Export](lights/xml/AdvancedAutoLights.xml)

## 4 Story Base Defense v1.0
![4StoryBaseDefesnev1.0](bases/images/4StoryBaseDefensev1.0.png)
This is a base layout for a solo base with a goal to have minimal power draw and no windmills as to not draw too much attention.</br>
The sensors are all wired to draw additional power from the battery including a secondary battery to supply the tesla coils each 33 rW.</br> 
The system can sustain the full load of systems with some additional room to overprovision the rW.</br>
Additionally it includes a counter to let me know how many people walked by while I was out with a reset button when I get back on the server.</br>
Finally it includes automatic heating and lighting.  This is enough to scare most raiders though not enough for a full on rocket attack.</br>
<b>Links:</b>
* [Rustician.io Circuit Link](https://www.rustrician.io/?circuit=fd7c82fead5fe723aac485fc93aa125f)
* [XML Export](bases/xml/4StoryBaseDefensev1.0.xml)