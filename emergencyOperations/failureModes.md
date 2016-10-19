#emergencyOperations/failureModes.md
##Synopsis
**IT WILL NOT FAIL to fail given enough time**  
But, most likely in one of the ways described here. The purpose of this article is not always to prevent the failure but to make user aware of what can go wrong and to raise attention to remedies and safe practices to minimize these unhappy events.  
Also, the listing order of these dire predictions are not particularly significant to the likelihood or severity of each event.  
On the positive side, the system has a lot of built in buffer. The most severe flood will be contained within the room and the plants will survive for 2-3 days without being flooded on the moisture stored in the buckets.

##The grim list
* **Operator error**  
Yes, the first item just happens to be most likely and damaging event. In particular, valve manipulations are very error prone. Among variety of unpredictable results of a mistake is flooding the room with the full content of a tank and/or drying the plants to death.  
Besides expending a lot of money and effort to automate all valve operations the cheapest but, perhaps, not the easiest thing to do is to be extremely careful and focused while operating these valves.
A great progress can be made in the future by alleviating operator errors.  
A few possible approaches:
    * Automating manual valve operations  
This will involve replacing manual valves with a lot of gravity fed solenoid valves at $50 a piece and writing a lot of software to operate them. Not trivial but can be done.
    * Installing sensors for early detection.  
This is a cheaper alternative but still would require some software to handle alarms and notifications.
* **a leaky manual valve**  
Not likely but happens. These valves will not catastrophically fail but might develop a slow leak if operated too many times, they are just plastic. The effects can be a slow flooding on the floor, mixing of nutrient solution with RO water or/and slow transfer of RO water into the nutrient tank.  
A difficult task for computer detection. However, a much easier one if you are a human. Just open valve [M10](Valve diagram) once in a while and see if it is oozing the juice. Make sure to close it before the next flood/drain cycle.
* **solenoid valve ([S1](Valve diagram)) failure**  
not too likely but it would be a bad solenoid and valve would fail to open. Can not be detected directly unless replaced with a very fancy expensive valve. However, a moisture sensor in the bucket can provide an effective alarm before the plants dry up.
* **Power outage**  
The effects are obvious. The way to help it is a battery backup. Running the lights on batteries will not work. Running the main pump on battery will not work for too long, perhaps will add a day or so to the life of the plants W/o batteries they would have 2-3 days.  
The most efficient use of battery backup is keeping the computer alive provided it can detect power failures and send alarms over the web. A nice bonus is to have some sensors to report on conditions of the plants, e.g. a moisture sensor in one of the buckets.
* **Computer failure**  
Least likely event unless in a fire. Again, given a web connection, a phone or a web app can detect an absence of a keep alive signal and raise an alarm. 
* **A bucket drain clogged up with roots**  
This can result in some buckets not being fully flooded and killing part of the root system. Another effect is uneven filling of buckets where some of them might start overfilling.
Judged by experience so far, it is not a problem. However, with more successful grows and root systems a lot more developed, there is a reason for concern. Would not be a bad idea to disconnected bucket hoses and check during the later part of the grow.  
If that becomes a nuisance, some clear hosing connected to bucket drains is a good idea. Roots hate light.
* **overdeveloped root systems**  
It is possible for the root mass to fill the buckets to an extent of overflowing them in the later part of the grow. Decrease flood interval if necessary as described in [software guide](software guide)
