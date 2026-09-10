<h1 align="center">Before You Begin</h1>
 
<p align="center">
  Models related to the steering wheel (paddle shift, wheel encoder) are designed for this steering wheel:
  <br><br>
 <img width="449" height="441" alt="621088206-c9d27bfe-b4da-4281-bfc6-63039ef5ae99-Photoroom" src="https://github.com/user-attachments/assets/16e96729-bf80-4541-9500-fc57965cf35f" />
  <img width="200" height="441" alt="image2" src="https://github.com/user-attachments/assets/a815cc70-40b7-4f56-a009-1150a662146c" style="vertical-align: middle; margin: 10px;" />
</p>
<p align="center">
  (You can buy it secondhand; that's what I did.)
   </p>

# Full Build
<img width="1920" height="722" alt="zz" src="https://github.com/user-attachments/assets/e65df026-e9fd-4b08-9398-76ff06f114d8" />


<img width="1520" height="722" alt="Screenshot 2026-07-12 151130" src="https://github.com/user-attachments/assets/32c54c19-cdda-4622-9fa2-860ee5fee710" />


<img width="1520" height="722" alt="2e02f5b3-c47f-4aac-a90a-409e35e45135" src="https://github.com/user-attachments/assets/e9d0ab70-481c-40e9-94ac-123a34f56987" />

*You can take detailed measurements yourself using the full-build model.*



# Why Im Building This?

I'm building this project because I want a steering wheel, but they're expensive and you can actually make better than the ones on the market for cheaper (I mean, I guess?). and at the same time this project will teach you (and me) a lot.
and you might be wondering why I didn't use a 3D printer or buy new materials to make a case;

this drawer is useless. Why wouldn't I use it? (and stronger than 3D printed cases)

# 3D Part Guide

### Desk clamp

In the 76th layer, there is a stop. In this layer, you need to insert the M12 hex nut into this place:
<img width="856" height="465" alt="image" src="https://github.com/user-attachments/assets/dea53b1a-8956-484b-ac72-fca09810fd0a" />

Then resume printing.


### Thumb Screw Knob

Just print it as normal, then glue the M12 hex-headed screw into this spot.

<img width="290" height="257" alt="image" src="https://github.com/user-attachments/assets/2c407114-d339-4f69-a5b6-8d5c67d961ce" />



*There is nothing special about the other parts, but you need to use the 3MF file that I uploaded to GitHub because the settings for each part are different.*

# Build Guide

You can figure out how to build this project by reviewing the fullbuild model; I'm thinking of putting together a short guide after I build the project, but I'm not sure yet.


This is the schematic for this project
<div align="center">
<img src="https://github.com/user-attachments/assets/4edd468b-7f72-474d-85c8-245d2e56b416" width="1600">
 <p>(This schematic is not final and may change as the project progresses. And this is actually my first schematic.)</p>
</div>

The Arduino Leonardo will be sufficient for a project of this power, I'm not using the ESP32-3S or STM32 because the softwares made for these microcontrollers is usually for direct drive, but this project is not direct drive, so it does not require a lot processing power and there is a software for the Arduino Leonardo that is specifically designed for these modules and project purpose: https://github.com/ranenbg/Arduino-FFB-wheel This is the software and the original wiring diagram can be found at that link.

<div align="center">
 <p></p>
