RC Poofer
=========

***Build instructions for a remote controlled flame poofer***


[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/poofie-trans-450x488.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/poofie-trans-450x488.jpg)


**
Disclaimer: This project is dangerous, and should only be attempted by an adult, it involves moving, high pressure, large balls of fire.  You will need common sense and a knowledge of [fire safety](http://www.firesafety.gov/kids/flash.shtm) before proceeding. If at any point something feels wrong stop and think about it for a while. Test things before igniting as much as possible, and work in a very well ventilated or outside location when fuel is involved. I am not liable or responsible for any damage you inflict or incur with this information. If you attempt this project you do so at your own risk.
**










# Tools


** **

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/tools.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/tools.jpg)



**
**









	
  * Vise grip 10WR

	
  * Phillips head screw driver

	
  * Plyers or a set of wrenches

	
  * 1/4" pipe cutter

	
  * Soldering Iron with flux and solder

	
  * Dremel with cut off wheel or small hack saw




# Materials


1. Remote(radio) controlled monster truck - this needs to be a modern hobby shop enthusiast quality truck, not one from Wallyworld or Radioshack.  I highly recommend buying this and the other RC gear [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/ruckus-box-300x225.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/ruckus-box-300x225.jpg)from you local hobby shop, the guys at my local shop where invaluable in teaching me what I needed to know to put the RC side of this project together. I chose the [Ruckus 1/10th Monster Truck from Electrix RC ](http://www.electrixrc.com/Products/Default.aspx?ProdId=ECX2000)this is a beginner model which includes everything to get an RC truck going, I chose this because of its low cost and large size, which is big enough to hold a camp size propane cylinder on its back. I changed out a lot of the things it came with but, I like having the extra parts.

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/spektrum-dx5e-300x225.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/spektrum-dx5e-300x225.jpg)2. Five channel RC airplane radio and receiver - the controller for a stock RC truck only has two channels, one for steering and the other for throttle, in order to trigger extra things like a flame effect you will need to change the receiver and transmitter with something that has more channels like the [Spektrum DX5e  5-channel 2.4GHz radio and receiver](http://www.spektrumrc.com/Products/Default.aspx?ProdId=SPM5510)





[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/escs-248x148-150x148.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/escs-248x148.jpg)3. An  extra ESC (electronic speed controller) - your monster truck should come with an ESC for controlling its motor, we will add an extra ESC to turn the servo control into a voltage that we can use to trigger the solenoid valve for the flame effect, the [ECX1070 by Electrix RC](http://www.horizonhobby.com/Products/Default.aspx?ProdID=ECX1070) is inexpensive and does the job. Electronics nerds will note that this is electrically dirty because we're sending a pulsed voltage to something that expects a straight voltage, but, this does work because the solenoid doesn't react fast enough to notice the pulse at full throttle. If you want this to be cleaner you could put a capacitor across the two lines but, if you really cared you'd build  a custom circuit for it anyway.

4. Thre[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/deans-connector.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/deans-connector.jpg)e pair of [deans connectors](http://www.wsdeans.com/products/plugs/ultra_plug.html),  these connectors were recommended by the guy at the Hobby shop and they seem to work very well, I replaced all of my connections with these, this takes a bit of soldering but, it's well worth the effort

5. Make or [buy](http://www.allerc.com/deans-ultra-one-battery-to-two-esc-adapter-cable-p-5665.html) a Y connector to connect one battery to two ESCs, if your making it you'll need about a foot each of 14 or 16 gauge wire of two different colors (red + and black -). This should have one male plug going to two female plugs.

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/y-connector.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/y-connector.jpg)









[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/refill-adapter.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/refill-adapter.jpg)6. Disposable propane tank refill adapter - [Mr. Heater Model No: F276172](http://www.mrheater.com/product.aspx?catid=357&id=98)

7. 1/[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/fourth-inch-to-throwaway-200x165.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/fourth-inch-to-throwaway-200x165.jpg)4" Male Pipe Thread x 1" - 20 Female Throwaway Cylinder Thread - [Mr. Heater Model No:F273754](http://www.mrheater.com/product.aspx?catid=356&id=65)

8. H[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/soleniod-valve-205x263.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/soleniod-valve-205x263.jpg)igh pressure 12V solenoid valve - it is important that this valve be "normally closed" meaning it stays closed until you give it voltage, it is also important that the pipe fittings fit the adapters you're using, in my case I'm using 1/4" NPT, I ordered the [SV-1 High Pressure 12 Volt Solenoid Valve](http://www.suremarineservice.com/SV-1.aspx) which seems to be readily available from marine supply stores

9. Camp s[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/baby-mapp-300x366.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/baby-mapp-300x366.jpg)ize or smaller propane tank with 1" - 20 Male Throwaway Cylinder Thread, the little cylinder made for the Quickfire MAPP torch fits perfectly and is light weight, you should be able to find this in the welding section of your local hardware store  [QUICKFIRE Max Power Propylene Fuel Cylinder (QF5)](http://www.bernzomatic.com/PRODUCTS/FUEL/tabid/212/ctl/Detail/mid/1148/xmid/6998/xmfid/3/Default.aspx)

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/gas-tape-150x143.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/gas-tape-150x143.jpg)10. Gas pipe joint tape (the stuff in the little yellow spool), or pipe joint compound. **Use pipe tape and tighten down all fittings that have gas running through them.**

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/steel-wool-200x220.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/steel-wool-200x220.jpg)11. Stainless steel wool, coarse, a piece about the size of a golf ball

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/copper-tube-200x48.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/copper-tube-200x48.jpg)12. 1/4" OD copper tube, a two foot length

13. Craft or bailing wire to attach steel wool to the end of the pilot tube [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/craft-wire.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/craft-wire.jpg)



14. Brass[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/brass-tee-200x221.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/brass-tee-200x221.jpg) pipe tee, Male x Female x Female, 1/4" NPT, [McMaster-Carr Part Number 50785K226](http://www.mcmaster.com/#50785k226/=cr4mfj)





15. Needle valve or something like it, I used a valve from this saddle valve kit [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/saddle-valve-kit-150x150.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/saddle-valve-kit.jpg)

what you're looking for is a valve to go from the side of the Tee to the 1/4 inch OD copper tube for making a pilot light [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/saddle-valve-with-tube-150x150.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/saddle-valve-with-tube.jpg)







16.  A fitting to connect the 1/4" Tee to your needle valve, the valve I'm using has an 1/8" MIP on the side that goes to the Tee so I used a 1/4" MIP x 1/8" FIP [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/fourth-inch-mip-to-eighth-inch-fip-205x300.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/fourth-inch-mip-to-eighth-inch-fip.jpg)







17. Some combination of fittings for your desired flame effect, if you ignite fuel straight out of the solenoid you get a loud and raw burst, playing around with different fittings on the end you can get different effects, a 1/2" FIP x 1/4" FIP with a 1/2" x 2 1/2" brass pipe nipple makes a cuter poof with a possible smoke ring [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/half-inch-fip-by-fourth-inch-fip.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/half-inch-fip-by-fourth-inch-fip.jpg)[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/half-inch-by-two-and-a-half-inch-brass-nipple.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/half-inch-by-two-and-a-half-inch-brass-nipple.jpg)







18. A method of securing the gas cylinder with it's fittings and solenoid valve to the RC vehicle, you will need to figure this out when you have the vehicle in hand, for Poofie I built a little cage from an erector set that screws in to some holes in the chassis, and made a custom belt to strap around the top of the cylinder, this is a good place to get creative, whatever you come up with make sure it keeps everything secure while the vehicle is in action [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/erector-cage-300x225.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/erector-cage.jpg)[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/cylinder-strap-300x51.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/cylinder-strap.jpg)





19. One twenty pound refillable propane tank for refilling the little cylinder

**Optional (highly recommended)
**

20. Set of heavy duty shock springs for the RC truck to help with the extra weight

21. High capacity RC vehicle battery [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/5000mah-battery.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/5000mah-battery.jpg)



22. Quick charger for the battery [![](http://aaronmcsorley.com/wp-content/uploads/2011/06/quick-charger.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/quick-charger.jpg)






# **Build**


Solder a male Deans plug (4) to the solenoid valve wires, polarity doesn't matter with the solenoid. Follow the instructions on the Deans plug package on how to solder them, don't forget the heat shrink.

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/solder-deans-plug.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/solder-deans-plug.jpg)









Replace the battery connector with a female Deans plug

Replace the battery connectors on the two ESCs with male Deans plugs

Secure the two ESCs (3) to the vehicle chassis with double sided tape, zip ties or Velcro where they will be close enough to be wired to the battery, solenoid valve, and motor. The ESCs also have a three wire servo control cable that needs to reach the radio receiver[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/esc-location.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/esc-location.jpg)











Replace the radio receiver in the truck with the five channel receiver (2), on the Ruckus the receiver is located in front under a plastic hood panel that comes off with two phillips head screws

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/under-hood.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/under-hood.jpg)











Connect the servo control wires from the two ESCs and the steering servo to the new receiver, this configuration will put the throttle and steering all on the right joystick, and trigger the flame effect when the left joystick is pushed all the way left or right. Do not connect an airplane receiver throttle to a truck if it has a failsafe mode,  RC airplanes can have a failsafe mode on their throttle which puts them into auto pilot in case they go out of range, if you wire a trucks motor ESC to this type of airplane throttle and accidentally turn the controller off first, the truck will run away from you at full throttle, this becomes much worse if the truck has a lit flame.

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/receiver.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/receiver.jpg)









    
    RUDD -> solenoid ESC
    ELEV -> motor ESC
    AILE -> steering servo




Connect the battery to the Y (5), and the two ends of the Y to the ESCs, the motor side of one of the ESCs should be connected to the motor, connect the motor connector of the other ESC to the solenoid vavle (8)

At this point you should be able to test the battery wiring, radio receiver, and functionality of the soleniod. Turn the controller on, then turn both ESCs on, throttle and steering should work through the right joystick, and you should hear the solenoid click open when you push the left joystick all the way to one side. After everything checks out hide the receiver and servo wires under the hood and screw it down, disconnect the solenoid valve and battery to avoid any accidents.

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/solenoid-test.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/solenoid-test.jpg)















Crimp one end of the copper tube (12) closed, and cut five small slits on each side of the crimped end of the tube with a Dremel or a small hack saw, this will be the pilot light

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/slits-in-tube-2.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/slits-in-tube-2.jpg)









Attach the other end of the copper tube to the tube side of the needle valve (15). This type of connection works by sliding the tube into the collar inside the nut and compressing the collar onto the tube while screwing down the nut. Wrap a piece of pipe tape around the threads and screw the tube to the valve pretty darn tight.

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/tube-and-valve.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/tube-and-valve.jpg)













Wrap a piece of stainless steel wool (11) around the crimped end of the tube, wrap some wire (13) around the steel wool to secure it to the tube, steel wool around the pilot will help the pilot avoid blowing out

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/steel-wool-on-tube.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/steel-wool-on-tube.jpg)









Attach the 1/4″ MPT x 1″ – 20 Female Throwaway Cylinder Thread adapter (7) to the bottom of the brass Tee (14), remember to always use pipe tape on these gas connections

Attache the top of the Tee to the bottom of the solenoid valve (8) , do not turn the solenoid valve by its body to screw it together or you will break it, use a wrench or plyers on the nut of the valve to tighten it down

Attach whatever end fittings you selected for your flame effect to the top of the solenoid valve (17)

Attach the needle valve to the side of the Tee, using the 1/4″ MIP x 1/8″ FIP  fitting (16)

Carefully and slowly, bend the copper tube to a position where the pilot light will be in range of the gas that comes out of the solenoid valve, I like to use a longer tube and make it into sort of an S shape, giving me room to play around with the pilot position, you could also make the tube really short and run the pilot tube straight up.

You should end up with a gas blaster that looks something like this

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/gas-blaster.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/gas-blaster.jpg)





















At this point you can check for gas leaks. In a well ventilated area, close the needle valve and attach the gas cylinder to the bottom of the gas blaster, if you hear or smell any leaks unscrew the cylinder, tighten any loose connections and make sure the needle valve is turned the correct way to be closed. You can check for small leaks by applying soapy water to the fittings, it will bubble out where there are leaks.

After confirming there are no leaks, you can test the pilot. With the cylinder screwed on, turn the needle valve on very slowly (9) , you may need to turn it up and then down to get it real low, light the pilot with a long lighter or a welding flint spark igniter. Play around with the valve, try to find the lowest valve setting that will keep the pilot low but will not die out.

[![](http://aaronmcsorley.com/wp-content/uploads/2011/06/pilot-lit.jpg)](http://aaronmcsorley.com/wp-content/uploads/2011/06/pilot-lit.jpg)

















Figure out some way to mount the cylinder and gas blaster assembly on the back of the truck, this is a good place to get creative, I used an old erector set and some leather (18)

At this point the system should be fully operational, go outside, attach the gas cylinder to the blaster assembly, mount it to the top of the truck, make sure the battery is connected, connect the solenoid valve to the ESC, light the pilot, turn the radio controller on, turn both ESCs on, back away, and make a poof!


