# Rust Admin Commands
This is a collection of commands for issuing to a rust server if you are an administrator

## Server Commands
- env.time - Shows in-game time. If value declared, will change the server time (values: 0 - 24)
- weather.clouds
- weather.fog
- weather.wind
- weather.rain - Modify rain intensity, values between 0-100 (auto)

## Inventory Commands
- inventory.give
- inventory.giveall
- inventory.giveto
- inventory.giveid
- inventory.givearm

### inventory.give
Tools:
- inventory.give building.planner
- inventory.give hammer
- inventory.give wiretool

Raw Materials:
- inventory.give wood 1000
- inventory.give stones 1000
- inventory.give metal.fragments 1000
- inventory.give metal.refined 100

Food:
- inventory.give pumpkin 20

Doors:
- inventory.give door.hinged.wood
- inventory.give door.double.hinged.wood
- inventory.give door.hinged.metal
- inventory.give door.double.hinged.metal
- inventory.give wall.frame.garage.door
- inventory.give door.hinged.toptier
- inventory.give door.double.hinged.toptier

Energy Sources:
- inventory.give electric.fuelgenerator.small
- inventory.give electric.solarpanel.large
- inventory.give generator.wind.scrap
- inventory.give electric.generator.small

Batteries:
- inventory.give battery.small
- inventory.give electric.battery.rechargable.small
- inventory.give electric.battery.rechargable.medium
- inventory.give electric.battery.rechargable.large

Electricity Logic & Switches:
- inventory.give electrical.branch 5
- inventory.give electrical.combiner 5
- inventory.give electric.blocker 5
- inventory.give electrical.memorycell 5
- inventory.give electric.splitter 5
- inventory.give electric.random.switch 5
- inventory.give electric.andswitch 5
- inventory.give electric.orswitch 5
- inventory.give smart.switch 5
- inventory.give electric.switch 5
- inventory.give electric.timer 5
- inventory.give electric.xorswitch 5
- inventory.give electric.button 5

Electricity Sensors:
- inventory.give electric.counter 5
- inventory.give door.closer
- inventory.give electric.doorcontroller 5
- inventory.give electric.hbhfsensor
- inventory.give electric.laserdetector 5
- inventory.give electric.pressurepad

Electricity Lights and Sound:
- inventory.give electric.audioalarm 5
- inventory.give electric.flasherlight 5
- inventory.give electric.sirenlight 5
- inventory.give ceilinglight 10

Defense:
- inventory.give guntrap
- inventory.give autoturret
- inventory.give electric.teslacoil
