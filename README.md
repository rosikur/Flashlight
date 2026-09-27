# Flashlight

A DIY Flashlight^^

A flashlight ... whats that
Well a Flashlight is a long stick that produces Light
there are shitty ones that use AA batteries ,better ones that use Li Ion Batteries but with micro USb and shitty Colors and last but not least the best: a High Power High CRI Flashlight Perfect for Photography on the go it has 56 Volts with 18 Watts , which if you asked me,is insanely bright it got 3 18650 Cells and a (hopefully if i figure cnc out) metal chassis

I mentioned something that's called "CRI" CRI stands for "Color Rendering Index" in short it's just how pretty Colors are for example CRI of 70 is very Desaturated while a CRI of 98 looks amazingly Saturated we're using a CRI of 98 because I'm a Photographer and my Camera is awful at low light performance (it's 15 years old and mft)

Why three Cells and not less? Well the led needs a lot of Power which a singular Cell cant give out , it needs almost 15x that amount,soo what do we do? We will use a cc Boost Converter to make the Voltage Super High while the Amperage is super low

The led needs to be cooled too , I could add a fancy Noctua fan but the deadline is in 2 days so sowwie next time, but we will use a fan on my next project promise!
Instead we're just using a block of aluminium as a heatsink and a bit of thermal paste not elegant but gets the job done.

This is how the wiring diagramm will look like approx:

![electricity diagramm](https://cdn.hackclub.com/01a0e01d-15da-7614-a58a-2f712592f41c/screenshot_2026-09-27_000224.jpeg)

So whats next , next well mske the Bill of Materials so that my Fans can steal my Invention ^^
And then we'll make the case D:

Quick Messaurements for our Case

LED
19\*19 mm the diode is 17mm diameter
On the Corner there is a .4 mm diameter hole for the screws
Cells
the cells are 18650s which means 18 mm diametre 65 mm height
So the other components will smh fit soo

Alright I'm Completating Life rn , i got exams and 3 Deadloines in the next 2 days

So i finished the CAD, Yeah I'm not CNC'ing this shit .

Well Rosi how will you make it now?

We'll buy a metal tube, some metal Plating a switch, the rest of the components ideally a "lens" from like an old pair of glasses and some reflective white stuff no idea what its called also grab an external usb c female port we aint using the one on the Li ION charger

Wire it like on the schematic so first,

1. Wire the Batteries in Serial and to the bms if you cant figure it out there are great online diagramms which i wont link for copyright reasons
2. Wire the lipo charger to the bms p+ and P-
3. Wire a female usb c port to the input pins on the lipo charger
4. On the p+ pin you'll wire a Switch and then wire a CC STEP UP to the other swich pin and to P-
5. IMPORTANTTT Grab a Multimeter, plug it in and after a moment Wire it in paralel (+ - Ports ) and then screw the Potentiometer until its at 56 Volts,else it wont work
6. (make sure the switch is off or you'll get blind)Wire the LED also to the + and - Ports on the step up( If u use my design do this later)

If ur House burns down I am NOT taking responsibility

You could 3d Print it but im Using a metalltube

The Not so lazy way:
Grab a Metal tube and a Metal Plate
Grab Your Welder and your eye Protection
Weld the metal Plate to the tube , for best results on the inside.
Insulate Everything on the inside because we dont want boom
Put everything in and Drill 2 Holes on the side one for the female usb c port and one for the switch
drill a hole in the top plate to the LED and Solder it
Please for the Love of God Almighty PLEASE use a HEATSINK with THERMAL PASTE the LED WILL DESOLDER ITSELF
now weld the top plate and add another tube place the heat sink to it and add an optic if u like
thats it
Pray that it works and have Fun:D

THIS IS ONLY A PROOF OF CONCEPT
I WILL NOT TEST IT MYSELF
IF YOU TRY IT DM ME
BTW this is how the CAD looks
(I havnt added the usb c hole)
![cad](https://cdn.hackclub.com/01a0e405-fe89-751b-a67f-bc8473082f6b/img_2091.png)

Stay Creative!
