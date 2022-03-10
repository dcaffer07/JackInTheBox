# Motion Sensored Jack in the Box (Dom and Zac)

## Table of Contents 
* [Planning Stage](#planning-stage) 
* [CAD Renderings](#cad-renderings)
* [Base Construction](#base-construction)
* [Gear Construction](#gear-construction) 
* [Arduino Code](#arduino-code)
* [Milestones](https://github.com/dcaffer07/JackInTheBox/blob/main/README.md#milestones-by-week)
* [Problems, Miscalculations, and Corrections](https://github.com/dcaffer07/JackInTheBox/blob/main/README.md#final-designproduct)
* [Final Design/Product](https://github.com/dcaffer07/JackInTheBox/blob/main/README.md#final-designproduct)
___

## Planning Stage
#### Purpose & Expectations
> To work diligently in order to create a product that improves and expands our overall knowledge of how basic engineering operates.  We are expected to work professionally, using our time and resources wisely.  We are expected to work with our partners efficiently to create an object that operates under the parameters provided. With this we will create a device that incorporates all of the aspects of engineering we have learned about to scare and startle those who aren’t scared and startled enough in an effort to make the world a less scared-and-startle-free space.

#### Description (establishing the foundation)
> While planning, we knew that we wanted a device that would fit all of the parameters and requirements, while still being creative by adding our own twist to the project.  This is where the "JacK in the Box'' idea (credited to Zac) came in.  So at this point we had established a vision, however we needed to execute this.  After many plans and ideas we decided that a servo motor would be the most efficient and discreet way to turn the gears, creating the sound and giving that unnoticable and unsettling effect. This would be facilitated through a gear to the interior, and this servo would be initiated by the ultrasonic sensor detecting movement.  However at this point we needed a way to stop the device at the correct time, so we plan to use a photoresistor to stop the box by detecting light with its opening.  So now we have a plan, and only have to make it happen. 

#### Planning Document
[Here is the planning doc that was created pre-creation](https://docs.google.com/document/d/1VZ0yBxpb9KwrkzfvlptIvGs4Mx1cKSWb2F__tJyYy9g/edit#)

#### Initial Sketch (Ended up being VERY close to final)
<img src="https://github.com/dcaffer07/JackInTheBox/blob/main/jackInBox.png?raw=true" alt="wiring2" style="width:318px;">  <img src="https://github.com/dcaffer07/JackInTheBox/blob/main/JIBINterior.png" alt="wiring2" style="width:290px;">  <img src="https://github.com/dcaffer07/JackInTheBox/blob/main/JIBImage.png" alt="wiring2" style="width:280px;">

#### Reflection of Planning (done post project)
> Overall I think we did a very good job with establishing a plan and going through with it, but some takeaways...
> - Be more exact and strict with milestones in planning and follow strictly.
> - Account for time to complete notebook or to deal with any issues.
> - Do not expect to be able to 3D print everything!!, try to use as much cheap material as possible.
>
> As stated, all in all I think we are super happy with how our planning went and how we were able to stick with that plan.


## Materials Used

>- Acrylic (base of box)
>- 3d printer (gears)
>- Axle Hub (for shaft attachment)
>- Wires 
>- Ultrasonic Sensor (input for when to start servo)
>- Photoresistor (signals servo to stop)
>- Servo (to turns drum which makes music and opens box)
>- Resistors
>- Wires
>- Arduino
>- Battery pack
>- Screws

## CAD Renderings 
### Base Construction
#### Description
> In order to fit all of the necessary aspects incorporated with the Box such as the wires, battery mount (power supply), arduino and breadboard, and photoresistor, we needed an area to store all of this.  This is where the base came in, as we decided that with a base we would be able to fit all of the necessary components while still having a singular box, as the jack and the base would attach to each other.  We did this using a friction fit style, creating a 5 side box with an open top, using 3mm acrylic to reserve material and resources.  Next, in order to make the box stay on the box we had to make a shelf, aligned across the inside of each wall that the Jack in the Box could sit on.  Then, we extruded and cut as necessary in order to provide holes for screws, switches, ect.  Finally, we needed a top to this box that was removable for adjustments but sturdy to provide something for the springs to push against; we did this also using acrylic, and we provided open spaces for the photoresistor and breadboard as necessary, while designing it so that it would fit snug across to shelf designed on the walls of the base.
#### Evidence
[Base in OnShape](https://cvilleschools.onshape.com/documents/0683eb52a22173b51047934c/w/f86c45cb89f616eb262b8ff8/e/189681eae29da1fce519768c)
#### Image
<img src="https://user-images.githubusercontent.com/71406831/153493685-90b107be-2091-4427-8590-cf9d1f6e740c.png" alt="wiring2" style="width:290px;"><img src="https://github.com/dcaffer07/JackInTheBox/blob/main/ToptoBase.png?raw=true" alt="wiring2" style="width:290px;"><img src="https://github.com/dcaffer07/JackInTheBox/blob/main/layout.png?raw=true" alt="wiring2" style="width:180px;"><img src="https://github.com/dcaffer07/JackInTheBox/blob/main/topsketch.png?raw=true" alt="wiring2" style="width:250px;">


#### Reflection
> All in all the construction and printing itself was relatively easy despite a few hiccups, however after going through it, here are a few takeaways from my experience creating this...
>- When possible, always try to use acrylic and laser cut. We had originally planned to 3D print the entire thing, however that would have cost almost 10 times the amount of, which was especially helpful considering the fact that we had to reprint.
>- Friction fit is an extremely efficient and easy way to attach things such as a box together.
>- Always leave yourself more room than anticipated. This came up as we had originally not left ourselves enough space to make the actual Jack attach to the base, however we were able to fix this through extruding the walls 3mm's up and then reprinting.
>- Mentaly walk through the design and the CONSTRUCTION OF THE OTHER PIECES TO THE BOX! I say this because we had trouble attaching the different aspects because they seemed to fit on OnShape; however when doing it by hand it was much more difficult, so just double check.
>All in all it was a fun build and I am super happy with the way it came out.
___

### Gear Construction
#### Description
> To run our Jack in the Box on a servo we had to attach our servo to a shaft that connected to the drum which made the music and opened the box. To achieve this we created a gearbox with two 3d printed gears. One of the gears was screwed onto a metal axle hub. The axle hub had a hole in it that the shaft  of the jack in the box would go through. However the shaft and hole of the axle hub had different diameters, so we needed to print a smaller piece that could compensate for the difference in diameters. The second gear was screwed onto a servo head. To get the gears onto the shaft we had to remove the shaft from the box and then put the gears on. We then used a bracket to hold the gears in the correct position so that when the servo spinned, the shaft also spinned creating music and triggering the opening mechanism for the box. 
#### Evidence
[Gearbox in OnShape](https://cvilleschools.onshape.com/documents/423806bfa6dff149a997954e/w/4dd89bd35a6ce4db869d6986/e/77e276e17288adce5d357a35)
#### Image
<img src="https://github.com/dcaffer07/JackInTheBox/blob/main/Screenshot%20(17).png?raw=true" alt="FinalAssembly" style="width:320px;"><img src="https://github.com/dcaffer07/JackInTheBox/blob/main/servoGeer.png?raw=true" alt="FinalAssembly" style="width:340px;"><img src="https://github.com/dcaffer07/JackInTheBox/blob/main/shaftSleeve.png?raw=true" alt="FinalAssembly" style="width:340px;">

#### Reflection
> The gears were a very time consuming process as there were many measurements to take in order to ensure the gears would fit in the box without interfering with the puppet. The gears when put together work incredibly well, the singing is very smooth and the speed of the servo is perfect, however looking back on the design process here are some things we learned or could have changed ...
>- When making holes oftentimes because they were so small they cave in on themselves, so sometimes we had to manually enlarge them with a drill. In the future we could make the holes slightly larger than needed in the attempt, that is if they cave in they will still be the right size.
>- Think through all of your CAD design because there was one time when we just started creating holes for the servo before realizing that the servo had to be on the other side of the gearbox for it to fit within the jack in the box. 
>- When first making the gears we tried to make them by hand which was going to take a very long time. Then we learned of an OnShape tool that would create the gears for us and this saved a lot of time. Always see if there is an onshape tool that might help you complete a repetitive task that other people have probably encountered before. 
>- To mount one of our gears we used a metal axle hub which worked fine, but it probably would have worked better if we had 3d printed a part that would have had the same effect. If we did this we could have printed it and the gear all in one piece which would have eliminated some of the trouble attaching the gear to the axle hub. 
>- Our servo is spinning very close to max speed in order to play the song at a pace that makes it sound good. If we had made our gear attached to the servo slightly larger we could have made the song play at the same speed without spinning the servo so fast. 
___

## Arduino Code
#### Description
> The goal of our code is to turn our servo when the Ultrasonic sensor detects a hand and stop the servo when the photoresistor detects an increased light level indicating the box has opened. To do this we used various if statements. In order to control at what distance the ultrasonic sensor would tell the servo to turn and at what brightness to turn off, we wrote a statement with the chosen distance or brightness. However, it took several tests with different values to get one that would correctly tell the servo when to start turning and when to stop.  

#### Evidence

```
#include <Servo.h>
Servo myservo;
const int trigPin = 9;
const int echoPin = 10;
float duration, distance;
int light = 0; // store the current "light" value

void setup() {
  pinMode(trigPin, OUTPUT);
  pinMode(echoPin, INPUT);
  Serial.begin(9600);
  myservo.attach(11); //attaches the servo on pin 11
  pinMode(8, OUTPUT);
}

void loop() {
  light = analogRead(A0);// Reads "light" level from photoresistor and prints it.
  Serial.println(light);
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2);
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin, LOW);
  duration = pulseIn(echoPin, HIGH);
  distance = (duration * .0343) / 2; //Calculates distance from hand to sensor
  Serial.print("Distance: "); // prints the distance
  Serial.println(distance);
  delay(100);
  if (distance < 15) { // If hand is close to sensor rotate servo
    myservo.write(155); 
  } 
  if (light > 200) {
    Serial.println("Light");//If the "light" level is greater than 600 turn the "light" off and print "light".
    digitalWrite(8, LOW);
  
    myservo.write(90); //Turns of servo
  }
}

```

#### Image
<img src="Wiringdiagram.png" alt="Wiringdiagram" style="width:500px;">
Wiring Diagram

#### Reflection
> We expected the code to be very challenging because of the many components we had but it was probably the easiest part of the project and we completed it in a couple class periods. However when writing future code here are some lessons ...    
>- Always double check your pin holes to make sure they are in the correct spot. You can waste a lot of time trying to find an issue with your code when it might be a problem with your wiring.
>- Be very careful with short circuits. We had a lot of trouble connecting and uploading our code to the arduino because the metal nuts we were using to attach our arduino to the base were creating a short circuit in the arduino. 
>- Talking through what your code is going to do in english really helps you understand the ordering of your functions and what your code is supposed to accomplish.    
___

## Milestones (by week)
> - Week 1 (11/15 - 11/22): Finish research, get jack in the box, and begin deconstruction of the box to get an idea of what's inside. (documentation throughout)
> - Week 2 (11/22 - 11/29): Finish deconstruction of box and based on findings adjust plan accordingly (such as mechanism for wheel turn). (documentation throughout)
> - Week 3 (11/29 - 12/06): Begin construction of the base on github using knowledge of the inner box. All prior adjustments have been made. (documentation throughout)
> - Week 4 (12/06 - 12/13): Continue work on base, start devising plan of action for gear mechanism. (documentation throughout)
> - Week 5 (12/13 - 12/20): Continue base work and begin CAD renderings for the gear mechanism as needed. (documentation throughout)
> - Week 6 (12/20 - 12/27): Winter Break - work on documentation as needed (documentation throughout) (documentation throughout)
> - Week 7 (12/27 - 1/03): Winter Break - work on documentation as needed (documentation throughout) (documentation throughout)
> - Week 8 (1/03 - 1/10): Continue work on base and gears on CAD.  Also establish an idea of what needs to be accomplished moving forward. (documentation throughout)
> - Week 9 (1/10 - 1/17): Finish CAD renderings of base and begin laser cutting process.  Continue CAD work on gears. (documentation throughout)
> - Week 10 (1/17 - 1/24): Construct box and all of its add ons such as arduino battery mount.  Continue gear work. (documentation throughout)
> - Week 11 (1/24 - 2/01): Finish gearbox on onshape.  Begin 3D printing process.  Begin code. (documentation throughout)
> - Week 12 (2/01 - 2/08): Finish gear 3D printing process and continue work on code/ wiring. (documentation throughout)
> - Week 13 (2/08 - 2/15): Attach gear mechanism to the box and continue to work on code and wiring. (documentation throughout)
> - Week 14 (2/15 - 2/22): Get box fully assembled with all aspects such as gears and base and complete wiring and code. (documentation throughout)
> - Week 15 (2/22 - 2/25): Complete Project.  upload and submit. (documentation throughout)

## Problems, Miscalculations, and Corrections
#### Design/ Initial Stage Issues
##### Opening the Box
+ Problem: Initially it was hard to open the box for adjustments while still preventing too much damage. But we had to open it to make the build work, and as a result we had an extremely uneven bottom of the box while cutting it.
- Solution: To fix this we had to use a combination of filing down the edges along with using the press/clamp to compress it to a point that it would sit flat.
##### Gear Mechanism
+ Problem: We were originally struggling to find a way to make the gear turn while still fitting everything in the box.
+ Solution: Zac came up with a way to feed the shaft through the gears so that when the servo turned the gears would and therefore music would play.
#### CAD Issues
##### 3D Print vs Laser Cut
+ Problem: We had originally planned to use 3D printed material to construct the box, however this would leave no room for error as this print would cost over 60 dollars.
+ Solution: We used acrylic material and laser cutting technology to construct the box in a more efficient and time sensitive way, which would prove essential when having to recut.
##### Walls Height
+ Problem: Initially the walls for the box to sit on which were attached to the base were too low, which prevented the box from staying connected and in place. 
+ Solution: WE had to reprint the walls,keeping the same base but raising the edges 3 mm.
#### Code/Wiring Issues
##### LED & Switch Attachment 
+ Problem: After getting the product to seemingly work, we noticed that the battery was dying rather quickly.  This was the case due to the fact that as we integrated the LED and Switch we had attached the switch to the LED only, making it so that the batteries were supplying juice to the servo and photresiter at all times, however the LED was only on command.
+ Solution:  With a small bit of rewiring and code adjustment, we were able to easily fix this problem, preventing the unnecessary use of energy and resources (the battery).
##### Photoresistor Light Value
+ Problem: THe calibrations on the photrestore were off, making both too sensitive or not sensitive enough at any given time.
+ Solution: We solved this using trial and error, testing it until we found the perfect calibration that allowed for the function that we were going for.
#### Build Issues
##### Rechargeable Battery
+ Problem: We wanted to install a rechargeable battery in our box but we did not have a hole in our acrylic to insert the charger. 
+ Solution: We lowered the base of the laser cutter so we could fit the box in on it's side. We then cut a small rectangle on the side of the box.
##### Dealing with a BEAT UP Box
+ Problem: Although it may ot seem this way at a first glance, our box was bent significantly, leading to an uneven bottom that did not allow for it to sit in its mold (base).
+ Solution: Using a mixture of sanding as well as hammering and compressing, we were able to return the box to its original state (or close enough), so that it fit on the box snug and as intended.
## Final Design/Product
### Reaction to completed project
##### Zac
##### Dom
### Final project images
<img src="https://github.com/dcaffer07/JackInTheBox/blob/main/GIFJB.gif" alt="wiring"  style="width:199px;"> <img src="https://github.com/dcaffer07/JackInTheBox/blob/main/sideJB.jpg?raw=true" alt="wiring"  style="width:265px;"> <img src="https://github.com/dcaffer07/JackInTheBox/blob/main/jbside.jpg?raw=true" alt="wiring"  style="width:265px;"> <img src="https://github.com/dcaffer07/JackInTheBox/blob/main/J&Bfront.jpg?raw=true" alt="wiring"  style="width:265px;">
