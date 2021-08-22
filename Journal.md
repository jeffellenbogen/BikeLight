# Journal

### 08-20-2021
Worked in Onshape to continue initial 3D model of bike light enclosure to house the electronics components, battery, and diffusing cover and eventually mount to bike handles. Add features to the 3D model to hold the components and allow for a USB-C charging cord to plug in as well as a place for a simple external on/off switch that will attach to the LiPo battery Booster board. The current plan is for the battery to be glues to the platform on the backside of the enclosure opposite the Fib 64 LED PCB. On this same surface, I'll attach the Pixelblaze and battery booster. Here are a few pictures of the progress.

![Bike Enclosure 1](https://github.com/jeffellenbogen/BikeLight/blob/main/images/bike_enclosure1.png)


Conversation with Chris Suter and next steps...
Chris and I looked at the initial design and talked through a few of the design challenges that I run across while thinking through the first prototype.
#### Challenge 1: The Battery booster board placement.
The battery booster board has a place to plug in a USB-micro charger, but it will be difficult to place that plug flush against the side of the inside of the round enclouse and also difficult to mount it with the screw holes.
Potential solution: Use a USB-micro extension cable [like this](https://www.amazon.com/YCS-Basics-Cellphone-Charging-Extension/dp/B00B5HSC20) to allow the battery booster board to be more centrally located inside the enclouse and then I can route the USB-C extension plug right up to the hole in the side of the enclosure.

![Section view](https://github.com/jeffellenbogen/BikeLight/blob/main/images/section_view1.png)

#### Challenge 2: Accessing inside of enclosure to mount and hook up components.
There needs to be a way to get inside the enclosure on the back of the side where the LED PCB will be attached. My plan is to split the back of the enclosure into two parts that fit together, thus allowing the enclosure to be opened to mount parts and troubleshoot any issues. In the current design, the very back of the narrowest part of the enclosure is left open with an opposing part that fits inside. Chris and I have talked through using screws to hold the two part together, but in looking in this initial design, there will be very limit access to the inside through this hole because it is so narrow. 
Potential solution: I can move the place where the enclosure is split much farther forward toward the back of the LED PCB, thus giving a much larger hole for accessing and installing the components.

#### Next steps...
I plan to implement both of these potential solutions in the next design. I am going to take a different approach and make the main enclosure in one piece. Then I will use a plane to split the enclosure somewhere just behind the backside of where LED PCB is mounted. This should be flexible in that I can move the plane to adjust where the part is spliced into two pieces.

Then I will begin working on a way to connect the back piece to the bike handle bars.

#### Additional thoughts / goal
I was originally hoping to design the main enclosure to be milled out of wood on the CNC. I decided it would be better to prototype for 3D printing and then eventually shift to a milled wooden version. The benefit of the adjustment to the place the enclosure is split is I can make it so there are no internal overhangs and hopefully allow the parts to be milled down the road, hopefully without significant redesign...

### 08-18-2021
Started documenting the bike headlight project.
Began building out Github page for this project.
Created a 3D scan using Polycam iPhone app. Uploaded OBJ exported 3D file to Sketchfab. View the 3D model on [Sketchfab](https://skfb.ly/opvV9)

