## Recursive-Pi-Hole-DNS
Adblocker and self service DNS

# Hardware
  I wanted a dedicated ad blocker for my home network, so I decided to set up a Pi-hole.  The first consideration was hardware.  Which raspberry pi was appropriate for both the scope of the project and for my budget?  I wanted wireless capabilities because the fewer wires laying around for my dogs to chew on the better.  That ruled out most options except the 4 and the 3, with the 3 being the cheaper of the two.  The extra power and storage of the 4 was overkill for my purpose so I settled on the v3.1b+.
  To connect the pi to the network and get it set up I needed a few things
  - a way to view what's going on in the pi during configuration, since this pi does not have an on board monitor
  - a mouse and keyboard
  - MicroSD storage for flashing the OS on
  - a case for the pi to prevent damage
  - thermal paste for the heat sinks 

I had an HDMI cable, a mouse, and a keyboard on site, but I ended up going to walmart to get a microsd card and amazon had a cute little nintendo NES shaped case for it I knew I had to have.  My laptop had an SD slot so I didn't need a card reader thankfully.  Once I had all the required components I needed assembly was fairly straightforward.  The pi bolted into the case via 4 small screws, and to engage the fan that came with the case I needed to put the connectors on the correct pins according to the instructions shipped with the case.  There were also two small heat sinks that needed thermal paste to apply them to the QFPs/BGAs.
  
# Software
Checking the Pi-hole documentation website, they recommended ubuntu as the OS so I installed that on my microSD card.  After installing it, I transferred it over to the pi and booted it up for the first time.  

# Configuration
Issues I had
