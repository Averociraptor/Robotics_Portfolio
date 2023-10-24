# Avery's Robotics Portfolio

Team Members: Matthew Sorensen, Avery Oremland, Corbyn Becker, Will Bond, Nash Hale, Ben Goetsch *Unofficially*, Xander Gonzalez

This is going to be a robot with a 2-speed manual transmission powered by 2 motors behind a friction plate clutch in order to prevent the transmission from ripping itself. This will also have front steering like a real car.

9/7/2023 1:00 PM ish, I'm going to test whether or not we actually need a clutch for the system, if we don't that will cut an extra motor and a lot of work.

9/7/2023 1:40 PM, We discovered a clutch is not actually needed, it shifts perfectly without the clutch even being present on the module.

9/8/2023 9:30 AM, I need to work on the gearing system to mount the 2 motors for propelling the machine. Once I get that done I can work on either improving the drive shaft by cutting it down and hoping that solves the problem of it being unstable, or entirely replacing that axle with a new stable one. my current plan after that consists of just having a 1:1 gear ratio coming off the output axle to power the rear wheels. I see one main problem with the rear axle the way I plan to have it, but it could be fixed by using 2 axles and 2 outputs off the transmission. The problem I see at the moment is the lack of any plan to have a rear differential to allow for better steering. The frame of the car is already very wide so I'm going to have to come up with a way to mount the wheels and axles, or instead of having them on the outside of the robot, we instead have them on the inside. this is just something I'm going to have to figure out how to do on Tuesday next week, 9/12/2023

9/12/2023 *doing this a bit later* 6:13 PM, Unfortunately, it took me way longer than I had hoped to mount both motors to the transmission, so on 9/14/2023 I'll have to mount the transmission somehow and build a differential or attach 2 different axles somehow.

9/14/2023 *doing this earlier today* 7:47 AM, Today my current goal is to at least mount the brain, battery, and transmission. After that, I want to wire everything and work with a teammate to program the second motor. If I still have time after that I'm going to spend the rest of the class thinking and maybe building prototype parts for the output system from the transmission. When I have a design set out I can begin building or prototyping that system. Once  feel confident with the design I can work on putting it on the robot.

9/19/2023 7:34 AM, I've quickly and honestly shoddily built an output from the transmission to one wheel as a demonstration of the idea that it works. Also what I need to do today is to finish the rear axle, where I've decided I don't want to try to build/design a differential so it's going to be a solid axle. On top of that Matt *the programmer* needs to reverse the motor's programmed direction so that pushing the stick forward drives the wheel forward. I also need to add a tensioner to the chain that is actively driving the axle. This is all going to be determined based on the time Matt takes to program, and how long it takes me to build the tensioner and to stabilize both the transmission and drive axles.

9/19/2023 11:54 AM, Forgot to mention this, the tensioner is going to be a very small sprocket on an axle that's held by a panel that is mobile, on the other side of the drive chain is going to be a solid mounting for rubber bands to go from the sprocket to the other side in order to keep the chain tense so it won't shake off. The Axles are going to be stabilized very simply, literally consisting of a C-bar and a pillow block.

9/21/2023 8:30 AM, Decided a tensioner was unnecessary after stabilizing the axles. I also added the second wheel and finished the solid axle. We did a speed test in the halls 2 days ago and it worked until the battery ran too low and the single motor could no longer overcome the torque of the second gear. Now I have charged the battery fully and added a second motor. This won't increase speed or velocity but it will affect first-gear torque and second-gear acceleration. Today we will do a second speed test to attempt to find its top speed, which means we might need to borrow a radar gun from one of the physics teachers. In terms of tooling or object manipulation, as a new assignment asks, we will be trying to have a plow of sorts. I also made a dumb move yesterday in my attempt to get out of the school faster, I forgot to save the new program file, luckily for me and my programmer it was like 2 lines and a toggle switch in the program to reverse the motor direction. Basically, our goal today is just to make programming fixes, and I am going to make sure the axle is stable.

9/26/2023 7:45 AM, Today I will be stabilizing the other front wheel so steering becomes easier, and I will be working on building the plow as part of the assignment for an object manipulator.

9/28/23 12:50 PM, Okay, I procrastinated a little bit, I will work on the plow today

10/19/2023 12:45 PM, We gave up on the differential for now, also one of the other builders is starting to work on building a 4-speed transmission rather than our current "basic" 2-speed.

10/24/2023 11:30 AM, Once the other builder finishes, and proves the functionality of the 4-speed, we will rework motor positions, shifter systems, and basically the entire drive train. When he proves its effectiveness I will work on retrofitting the rear axle and actually add the differential in a better way. I will also be forced to reposition the rear right tire (looking at it from the back) at the moment it is actively bending that axle because of some stupid vex designed misalignment. Same parts on both sides right now, and it's still not lined up properly. So I'll fix that and then I can very easily put in the differential, with an axle coming off the transmission to a set of bevel gears which will power the gear used to run the differential.. this one is going to way infinitely more than the current 2 speed based on the sheer amount of metal and plastic being used.

10/24/2023 2:03 PM, Prototype differential system and shifter sprockets are built but the 4-speed is still giving problem after problem. ETA: maybe sometime next week

![Diagram](https://github.com/Averociraptor/Robotics_Portfolio/blob/main/images/1692995499.337287.jpg?raw=true)

![Diagram](https://github.com/Averociraptor/Robotics_Portfolio/blob/main/images/20230829_134524.jpg?raw=true)

![Diagram](https://github.com/Averociraptor/Robotics_Portfolio/blob/main/images/20230831_140558.jpg?raw=true)

![Operation-Video](https://youtu.be/obedb8HNvTE?si=c3B1iHHwUU4Q1qLj)

![Diagram](https://github.com/Averociraptor/Robotics_Portfolio/blob/main/images/bot1.jpg?raw=true)

![Diagram](https://github.com/Averociraptor/Robotics_Portfolio/blob/main/images/20230921_130219.jpg?raw=true)

![Diagram](https://github.com/Averociraptor/Robotics_Portfolio/blob/main/images/20231010_125151.jpg)
