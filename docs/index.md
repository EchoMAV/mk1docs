# MK1 Documentation

## Overview

The MK1 is a Class II Hybrid-Power VTOL. 

![EchoPilot AI](assets/mk1_image1.jpg)

       

## Maintenance

### Servo Replacement

The instructions below can be used to program and replaced a damaged servo. 

| Position                | Servo |
|-----------------------|--------|
| Ruddervator              | Hitec HS-5086WP  |
| Aileron                 | Hitec HS-5086WP     |
| Throttle              | Hitec HS-5086WP   |


!!! warning

       The Ruddervator and Aileron servos must be programmed using the instructiosn below prior to installation in the vehicle. Failure to do so may result in damage to the airframe, improper flight characteristics or crashes.
     
#### Ruddervator Servo Replacement

1.  Using a 2mm hex wrench and a 5mm socket wrench remove control arm from the servo horn.  
![Servo 1](https://github.com/EchoMAV/mk1docs/assets/155487175/a81854f3-c6ca-43ea-9103-8147a8b254c4)  
2.  Using a 2 mm hex wrench remove servo hold down bracket screw.  
![Servo 2](https://github.com/EchoMAV/mk1docs/assets/155487175/c4def55a-1d54-4fd7-b0d2-113682bfef1c)  
3. Remove servo hold down bracket.  
![Servo 3](https://github.com/EchoMAV/mk1docs/assets/155487175/8cf9c761-9ff0-4ef8-a4b9-9d4a68f85a99)  
4. Gently remove servo from Ruddervator.  
![Servo 4](https://github.com/EchoMAV/mk1docs/assets/155487175/ac2f1a1d-92e1-4f87-bfa8-7437149cae01)  
5. Remove servo control horn.  Inspect to make sure horn is not damaged or bent. If no damage is found horn can be reused.  
![Servo 5](https://github.com/EchoMAV/mk1docs/assets/155487175/adf0074d-ce28-4580-8756-dd81a61277e2)  
6. De-solder the 3 servo wires allowing the servo to be removed from the Ruddervator.  
![Servo 6](https://github.com/EchoMAV/mk1docs/assets/155487175/0fb6caf5-b208-45d9-9d31-c4a85485a032)  
7. Install new (or reused) servo horn on servo and move servo clockwise as far as it will go. Pay attention to this position.
See pic.  
![Servo 7](https://github.com/EchoMAV/mk1docs/assets/155487175/f30f0e81-5340-4647-987a-cda5b4273f27)  
8. Move servo horn counterclockwise as far as it will go.  Pay attention to this position.  
![Servo 8](https://github.com/EchoMAV/mk1docs/assets/155487175/4cebe606-e30a-4552-a101-570d2b38d909)  
9. Rotate the servo horn to the halfway point between the two positions found in steps 7 & 8. This should position the servo aproximatly to the 9 o'clock position pointing to the left.
!!! note

       The servo control horn 9 o’clock position pointing to the left side is for the Right Ruddervator.  For the left Ruddervator the servo horn will be in the 3 o’clock position pointing to the right side.
      
![Servo 9](https://github.com/EchoMAV/mk1docs/assets/155487175/55d87f4b-0870-4250-bcd6-590159109e65)  
10. Plug in power source to Servo Programmer and plug in new servo to programmer.  
Set the programmer to prog mode using the slide switch on the right side of programmer.
Using the Adjust set knob rotate until the 5/7 position is selected then press the adjust knob.  
![Servo 10](https://github.com/EchoMAV/mk1docs/assets/155487175/264d55d6-b986-406a-af8c-160c49680412)  
11. Using the pulse knob slowly rotate the knob until arrows are indicated on both sides of the “Pulse Center” display.  
![Servo 11](https://github.com/EchoMAV/mk1docs/assets/155487175/b0a16421-b43e-491d-9e11-e08032b2f19b)  
12. After centered the programmer will return to the programming screen.  
![Servo 12](https://github.com/EchoMAV/mk1docs/assets/155487175/2fa35279-f97f-4a48-9e48-de4fc830c785)  
13. Place the new servo into the servo jig.  Note the servo horn might not be perfectly centered in the slot in the jig.  
![Servo 14](https://github.com/EchoMAV/mk1docs/assets/155487175/2538649a-6607-45e4-910e-decb8907e6be)    
14. Press the adjust knob then rotate the pulse knob to center the servo horn to the slot in the jig.  In this position the servo horn is 90 deg to the servo when the servo is in the neutral position. Press the adjustment knob when servo horn is centered. 
!!! note

       The servo control horn 9 o’clock position pointing to the left side is for the Right Ruddervator.  For the left Ruddervator the servo horn will be in the 3 o’clock position pointing to the right side.
![Servo 13](https://github.com/EchoMAV/mk1docs/assets/155487175/e8f9e857-408d-4ab7-a17f-c6ce1f20be99)  
15. Using the adjustment knob select the left position then press the adjustment knob.  Slowly turn the pulse knob until value is set to -90 then press the adjust knob.
Using the adjustment knob select the right position then press the adjustment knob.  Slowly turn the pulse knob until value is set to 90 then press the adjust knob.
Then press the back button.

Verify that the following values are set:

| Parameter             | Setting |
|-----------------------|--------|
| Limits                | -90/90 |
| Deadband              | 1      |
| Speed                 | 64     |
| Failsafe              | Off    |
| High Res              | Off    |
| Over Limit Protection | Off    |

You can now switch the programmer to the test position and select manual mode. Turning the pulse knob should rotate the servo. 

Reinstall the servo into the Ruddervator reversing steps 1-6. Use blue (242) lock tight when reinstalling the bolts and nuts. Make sure to use heat shrink on all solder connections.  
![Servo 15](https://github.com/EchoMAV/mk1docs/assets/155487175/af3c3532-e41a-483f-be7d-8f9f1e2a0965)  
16. Control arm length should not change during servo replacement.  Length from screw head to screw head should be ~ 79mm. 
![Servo 16](https://github.com/EchoMAV/mk1docs/assets/155487175/28cbd84a-a6c2-482a-95ec-8d7a372bd3fb)  

**VERIFY ALL CONTROL SERVICE MOVEMENT AND DIRECTION USING AIRCRAFT CONTROLLER.**   


#### Aileron Servo Replacement
1. Remove servo following Ruddervader steps 1-9.   
!!! note

       In step 9 - The servo control horn 9 o’clock position pointing to the left side is for the Right Aileron.  For the left Aileron the servo horn will be in the 3 o’clock position pointing to the right side.  
2. Program the servo folloowing Ruddervader steps 10-14.  
!!! note

       In step 14 - The servo control horn 9 o’clock position pointing to the left side is for the Right Aileron.  For the left Aileron the servo horn will be in the 3 o’clock position pointing to the right side.
3. Using the adjustment knob select the left position then press the adjustment knob.  Slowly turn the pulse knob until value is set to -50 then press the adjust knob.
Using the adjustment knob select the right position then press the adjustment knob.  Slowly turn the pulse knob until value is set to 50 then press the adjust knob.
Then press the back button.

Verify that the following values are set:

| Parameter             | Setting |
|-----------------------|--------|
| Limits                | -50/50 |
| Deadband              | 1      |
| Speed                 | 64     |
| Failsafe              | Off    |
| High Res              | Off    |
| Over Limit Protection | Off    |

You can now switch the programmer to the test position and select manual mode. Turning the pulse knob should rotate the servo.   

4. Reinstall the Aileron servo into the wing reversing removal steps. Use blue (242) lock tight when reinstalling the bolts and nuts. Make sure to use heat shrink on all solder connections
Verify all control service movement and direction using aircraft controller.  
5. Control arm length should not change during servo replacement.  Length from screw head to screw head should be ~ 61mm.
     
**VERIFY ALL CONTROL SERVICE MOVEMENT AND DIRECTION USING AIRCRAFT CONTROLLER.**   
  
### Battery Replacement

### Fuel Filter Check/Clean  
1. Remove Air scoop from engine using a 3mm hex wrench.  
![Filter 1](https://github.com/EchoMAV/mk1docs/assets/155487175/ec69df49-d745-4cab-bd04-88cc5df99202)
2. Remove fuel plug/filter by rotating clockwise then gently pulling to remove from fuel tank.
![Filter 3](https://github.com/EchoMAV/mk1docs/assets/155487175/edec07b3-539d-43a9-892a-eccbd3513c7d)
![Filter 4](https://github.com/EchoMAV/mk1docs/assets/155487175/65fd9600-152c-410c-9715-69510224a446)
3. Unscrew filter housing from plug and remove filter. Note the orentation of the fuel filter.  
![Filter 5](https://github.com/EchoMAV/mk1docs/assets/155487175/2d2ac276-b791-4a20-b0dc-e9182b7224f1)
4. Inspect filter for contamination and damage. Clean or replace as necessary.  
5. Inspect the white o-rings on the plug.  If damaged replace. **Worn or damaged o-rings can cause a fuel leak.**      
6. Reverse steps to reinstall filter and plug. Make sure to replace fuel filter in original orentation.  
Be sure to use locktight 242 (blue) on air scoop bolts.





### VTOL Prop Replacement
!!! warning

       **The VTOL prop orentation is very important to ensure proper operation of the MK-1. Please note the prop type and location in below digram.**    
       
![Prop Orentation 3](https://github.com/EchoMAV/mk1docs/assets/155487175/73eb499a-3286-4ffc-90c0-219d7e7f6460)

1. Make sure aircraft is turned off and battery is disconnected. Position boom and motor to allow access to the prop area. Clean top area to remove any dirt or debris.  
![image](https://github.com/EchoMAV/mk1docs/assets/155487175/076244c1-e5c4-4b0d-973b-b992717166cf)

2. Using a 2.5mm allen wrench remove the 2 prop hold down bolts and prop hold down washer.  
![image](https://github.com/EchoMAV/mk1docs/assets/155487175/e56d060b-a377-4f8d-b1cf-132a7cc1eeb4)  
![image](https://github.com/EchoMAV/mk1docs/assets/155487175/5251549c-a0e3-4569-b6e3-e39f117effce)  
3. Remove old prop and clean the prop mounting area to free any dirt or debris. Note location of prop mount and be careful not to move out of position.  
![image](https://github.com/EchoMAV/mk1docs/assets/155487175/b0599a9d-40b1-429f-a005-9848f0cb08de)    
5. Replace damaged prop with correct new prop (L or R) depending on potition. See prop location diagram in warning note at the beginning of this section.  Reattach new prop reversing above steps making sure to use Blue Lock Tight (242) on bolts.    


   



### Engine Prop Replacement

### Landing Gear Replacement
