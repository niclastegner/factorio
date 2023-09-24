# Steel age

## Intro

It's assumed that you have a mall and have automated red- and green science up and running.

## Automated steel production

Your task is to setup automated steel production, but while building it you should do the following research in this order:  
- Steel
- Optics
- Stone wall
- Military
- Electronics
- Heavy armor
- Fast inserter
- Engine
- Automation 2
- Fluid handling
- Logistics 2

Create the following design (while at the same time always researching according to the list):  
<details>
  <summary>:abc: Blueprint string</summary>

  ```
  todo
  ```
</details>

![steel-smelting](images/steel-smelting.png)

# Trains and oil

While building the train capabilities make sure that the research list is ticked off.  
Add the following to the research list:  
- Railway
- Electric energy distribution 1
- Oil processing
- Automated rail transportation
- Fluid wagon
- Plastics
- Sulfur processing
- Advanced electronics

Go to the coal patch and add two more drills to increase the coal production consumed by the smelters.

Create by hand:
- 1 x Boiler
- 2 x Steam engine

Increase the electric power capacity by adding another set of bolier/steam engine:  
![increased-electric-power-2](images/increased-electric-power-2.png)

Go to the stone patch and place four drills and a transport belt.  
Extend the stone belt and also the steel belt and its adjacent coal belt to the area of your mall and red/green science.  
![belts-steel-coal-stone](images/belts-steel-coal-stone.png)

Extend the mall with engines and rails by building the following design (restrict boxes - engines 1 stack, rails 6 stacks):  
<details>
  <summary>:abc: Blueprint string</summary>

  ```
  todo
  ```
</details>

![engines-and-rails](images/engines-and-rails.png)

Pick up a stack of steel from the steel belt and some green circuites and iron cogs from the mall.  
Create 11 x Assembling machine 2 and place them on the red/green science setup to upgrade their speed.  
Create 4 x Lab and extend the lab setup:  
![faster-research](images/faster-research.png)

Use the map to find the nearest cluster of oil patches and build one pumpjack for every oil patch by picking up items from the mall and belts.  
Pick up a stack of pipes and a stack of underground pipes from the mall. Make sure you have a couple af stacks of copper-, iron- and steel plates.  
Pick up all stacks of rail from the mall. Also pick up an engine and create one Pump and one Tank.  
Head over to the oil patches and place a Pumpjack one each oil patch. Bind all Pumpjack outlets to one single fluid network and end it with a Tank and a Pump.  
Create a rail roundabout adjacent to the Pump:  
![oil-station](images/oil-station.png)

Build a railway path to your base and end it with a roundabout near your mall:  
![oil-station-base](images/oil-station-base.png)

Create 2 x train stop and about 15 big electric poles.  
Pick up 20 x engine from the mall and create one locomotive and one fluid wagon.  
Place the train stop in the roundabout, then place the locomotive at the stop (it should snap in place) and finally connect the fluid wagon to the locomotive.  
![oil-base-station-stop-placement](images/oil-base-station-stop-placement.png)
![oil-base-station-stop-locomotive](images/oil-base-station-stop-locomotive.png)

Click on the locomotive and select the fuel tab in the ui. Add 3 stacks of coal to the locomotive.  
Connect one big electric pole to the electric grid but as close to the train stop as possible.  
Step into the train by standing close to it and pressing the enter key. Use the normal forward and back keys to manually drive the train.  
While in the train, select the big electric poles from your inventory and start slowly driving the train forward while at the same time placing poles alongside the rail track.
![big-electric-poles-placement](images/big-electric-poles-placement.png)

After a while you'll reach the oil patches. Place one final big electric pole near the pumpjacks, step out of the train (also by using the enter key)
and connect the Pump and all Pumpjacks to the electric grid. The Pumpjacks should now all start to move and the Tank should be filling up.  
Place a train stop in the roundabout but make sure it also connects the fluid wagon to the pump:  
![oil-station-with-power-and-train-stop](images/oil-station-with-power-and-train-stop.png)

Click the train stop and select the rename button, then rename the stop to "Oil". While you're at it, open the map, select the train stop at the base 
and rename it to "Oil Base".  
![rename-train-stop](images/rename-train-stop.png)

Now it's time to setup an automatic train schedule. Step into the train, then click the locomotive to bring up the train ui.  
First add the "Oil" stop, then the "Oil Base" stop. Add wait conditions as follows:
![oil-train-schedule](images/oil-train-schedule.png)

While still in the ui, press the play button next to the "Oil" stop. The train should now automatically drive to the "Oil" stop, the pump should
fill up the fluid wagon (if it doesn't you may need to move the train stop one tile) and then automatically drive to the base where it should stop.

## Summary

By following the guide above you have now set up:  
- Automated steel production
- Increased Research rate by having faster Assemblers and more Labs
- Mall extension: Rails and Engine
- Automated Oil production via Train
