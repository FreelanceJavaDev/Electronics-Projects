# DIY Laser Pointer
Of all the things to make, a laser pointer provides hours of entertainment.  Especially if you have a cat.  Unfortunately store bought ones are either cheap and die quickly or are over $20 and use funky button cell batteries that are nearly impossible to find at in the size needed at a decent price.  Perhaps someone should design a better, cheaper laser pointer?  Well look no further than this page. All told this laser pointer can be made for as little as $5.

## Overview
  To begin a new concept has to be introduced, the Blocking Oscillator, which is simply a transformer with the two induction coils connected at one end and wire and the other two ends are connected to an NPN transistor's Base and Collector with a couple of resistors. This particular use of a Blocking Oscillator is nicknamed "Joule Thief". This particualr circuit drives a 3.0V red laser diode using a single standard 1.5V AA battery.  The Joule Thief's true power is that it pulses the AA battery to a higher voltage as required by the circuit. The method by which this occurs comes from the complementary nature of the behavior of a transistor and a transformer wired in this manner.  The transistor is on when the Base and collector voltage are unequal, a transformer is off when the voltage is constant.  This creates a circuit that constantly pulses on and off at a rate that to the human eye seems to be always on.  It's a simple little trick that can create circuits that shouldn't work appear to work.  The actual oscillation can be viewed using an oscilloscope.
  This circuit is highly reccomended for soldering to post-hole board for portable use.

## Making a Joule Thief
  A Joule Thief is easily made.  Two lengths of insulated copper wire of 24 AWG or less with thin insulation.  Different colored insulation is a must to avoid confusion, and a ferrite torroid (a magnetic doughnut-like shape).  The ferrite torroid is how the transformer part of the blocking oscilator works.
    1.  Begin by tightly wrapping the two wires around the torroid, take care to make sure wires cannot cross eachotehr in any way (it will disrupt the magnetic field).
    2.  Wrap the two wires as a pair as many times (Typically 7-10 wraps) as possible without crossing over other wire wraps with 4 decent lengths of wire left over to connect to the circuit.
    3.  Wrap the wire wound torroid in electrical tape to keep the wires in place.
    4. Strip and tin the ends of the wires.
    5. pick two different colored wires from each of the two pairs to connect together.
    
    
## Parts
  - 1 3.0V Red Laser Diode
  - 1 NPN Transistor
  - 1 1k-ohm resistor
  - 1 100-ohm resistor
  - 1 contact push button
  - 1 1.5V alkaline AA battery
  - 1 ferrite torrid 
  - Wire
  - superglue (to fix laser diode in place)
  - Duct tape
  - 1 1x AA battery holder (optional)
  - 1 1ft 1.2" diameter PVC pipe (optional)
  - 2 1.2" PVC pipe caps (only w/ PVC pipe)
  
  
  
  ## Application limitations of Joule Thiefs
    The Joule Thief creates rapid pulses of electricty. These pulses will cause issues with some components.  It may even destroy them.

    - Without additional components Joule Theifs should not be used with:
     - Integrated Circuits
     - Computers
     - CPUS
     - Flash memory devices
  
  Joule Thiefs cannot be bought, but are easily made.  Just use two lengths of insulated copper wire (24 AWG or smaller) of different colors and a ferrite torroid.
  **Do not use with any components senstive to magnetic fields.**
