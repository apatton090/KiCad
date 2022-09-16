# KiCad
Personal KiCad Projects


Getting to Blinky 5.0 (GTB5)

https://contextualelectronics.com/courses/getting-to-blinky-5-0/

https://www.youtube.com/watch?v=BVhWh3AsXQs&list=PLy2022BX6EspFAKBCgRuEuzapuz_4aJCn&index=1

https://www.youtube.com/watch?v=n3rKSE2zIUQ&list=PLy2022BX6Eso532xqrUxDT1u2p4VVsg-q&index=5


![Blinky1](Blinky1.jpg?raw=true "Title")



Lessons learned:


Build:

- Soldering SMT components by hand is rather difficult. It works but it takes a fine touch: would not recommend for someone who it new to soldering. Need to have solder wick on hand to fix any mistakes (solder bridges.)

- Labeling all of your component bags with ref des. beforehand is a good idea. Make sure you have the ref des. in silkscreen on your board and have the schematic on hand for reference. Datasheets for any ICs also useful to check orientation and debugging.

- The battery holder does not allow the battery to make very good contact with the PCB ground pad. There was an issue where the LED would only blink if the battery was halfway inserted. This indicated either a short or no connection. A flat blob of solder should be applied to the ground pad to ensure good connection.

- The PCBs from Oshpark come with spurs protruding from the edges; they are not perfectly flush. A sharp knife can be used to saw them away but some kind of sandpaper should be used to achieve a really smooth finish. This should be considered when designing any mounting hardware.

- Check continuity and probe various points on the PCB to make sure everything is connected as intended.


Design:

- It would be helpful to select components and maintain a BOM during the schematic design. For this project, the components were not selected and ordered until after the PCB was sent to the fab. Electronics components are still seeing shortages, so it could take a while to get some components on a more complex design.

- It took about 2 weeks for Oshpark to send the design to the fab, then ship out from the fab. After the notification that they had shipped, I received the boards in 3 days.



