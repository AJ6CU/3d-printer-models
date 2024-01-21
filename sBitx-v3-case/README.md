# A 3d printable case for the HF Signals sBitx board

## Revision History
Jan 21, 2024:	Initial v1

## Overview
This is a design for a 3d printable case for the HF Signals sBITX. Hams that have just purchased the single motherboard might find this design useful. To print it, you will need a 3d printer with at least 270mm x 170mm bed. If you do not have such a large printer, there are multiple 3d printing services that can print it for you. Unfortunately, I do not offer such a service. 

I printed in petg. With 50% infil, it will take approximately 8-10 hours to print all the pieces. I did not need to use any supports (although some screw holes came out somewhat oval...)

3mm screws are used everywhere. Depending on your printer, you may need to pre-tap some of the holes. 

This was designed using Fusion 360. My thanks go out to Mike - KW1ND that provided the base design from which I started. It would have been much more difficult to have started from scratch. The Fusion 360 archive file is provided in the Bitx-case-3d-printer-files folder. You will find the ready to print stl files there too.

## Assembly
### Step 1: Print all pieces. 
You need to print all the parts. Make sure you print 2x of the lcd brace.

![step1-printed_parts](https://github.com/AJ6CU/3d-printer-models/assets/70183884/02d0f8e6-e5b1-4860-b22e-0165b237ce7d)

### Step 2: Preparation of hold downs and Speaker Attachment
You may need to use a 3mm tap for the 5 holes in the bottom of the case and the two that hold the PI HDMI cover. Make sure all these holes accept a 3mm screw. 

The V1 desigm has no attachment holes for an internal speaker. The position of the speaker is as in the origial HF Signals case design, at the top and to the left of the RaspberryPi. If you have a speaker to use, you should plan on how you will mount it at this point.

### Step 3: Insert the sBITX motherboard
It is a tight fit!  Angle the motherboard so that the antenna connector goes in first and then you can bow the side with the audio connectors back to place the motherboard into the case. (Obviously, make sure you took off all the nuts on the antenna audio connectors!)

![step2-inserting_sBitx_into_case](https://github.com/AJ6CU/3d-printer-models/assets/70183884/b0cd26a2-13df-41a7-b671-91b1a919e66a)

### Step 4: Fasten the sBTIX motherboard
Since the threads on the audio connector are very short, I designed the case to push up against the wall where the audio connectors are. The 5 holes below the motherboard should more or less aign with the offsets. Do not be surprised if they are off a little, home 3d printers sometime have some variations. Tighten them down evenly. I used 7mm long screws here, but 5mm should work too.

At this point you can put the nuts on the audio connectors on and afterwards tighten down the antenna nut. In getting the audio connectors to attach and not pop off, I had to start on one end that was slightly farther out, tighten it down, and then move on to the next ones. 

Now plugin your RaspberryPi and fasten it down. These are 2.5mm screws not 3mm.  Note that because the holes for the RaspberryPi USB and RJ45 are slightly high, the RaspberryPi might not sit completely flat. This will be corrected in a future release.

![step3-sBitx_board_secured](https://github.com/AJ6CU/3d-printer-models/assets/70183884/c0db8eff-4802-470e-8179-6dad25d29d58)

#### Step 5: Mount an Internal Speaker
In the V1 design, there are no holes to attach a speaker. I am still looking for an option that is readily available. A future revision will include the url for the speaker and the body will have the attachment holes pre-drilled. Meanwhile, if you want to attach your speaker, you should do so now.

#### Step 6: Mount the Pi LCD Touchscreen and Encoder Board
See photo below for the proper orientation of the screen. The internal microphone channel is in the upper right. This is the top of the screen. The thicker support on the LCD frame is on the bottom. Note that the ribbon cable of the screen faces the bottom. The encoder board will need to be bent slighty to ensure the mounting nuts of the encoder can be attached to the front of the lcd frame. Make sure you plug in the encoder cable before attaching it to the frame.

![step4-mounting_touchscreen](https://github.com/AJ6CU/3d-printer-models/assets/70183884/81e31009-2d32-44e5-aed0-26ea0dd7dd23)

#### Step 7: Hook up the Touchscreen
Note that the blue tab on the lcd ribbon cable faces down and the connector of the ribbon cable face up. Make sure you hook up the power cable with correct polarity to the sBitx motherboard.

![step5-touchscreen_connection_note_blue_facing_down](https://github.com/AJ6CU/3d-printer-models/assets/70183884/386f77ad-6243-4021-9352-a4285570306f)

#### Step 8: Done!
Assuming that you got the ribbon cable seated properly, when you turn on the sBITX you should get the RaspberryPi desktop. Then by double clicking the sBitx icon on the desktop it should start! (Search the bitx20 group for hints on how to auto start the sBitx softwre.

![step6-working](https://github.com/AJ6CU/3d-printer-models/assets/70183884/8dbc2519-6e0e-4cc4-a66d-54d853a559c2)

## Other Photos
These are some of the other photos I have taken. Perhaps you will find them useful.

![extra-back_of_case_showing_heat_sink](https://github.com/AJ6CU/3d-printer-models/assets/70183884/87fdd7ca-0bc6-4e11-bb5c-6a09dbfa0cab)

## Future Revisions
1. Body with mounting holes for an internal speaker.
2. Optional brace (such as Elecraft designed for their KX2/3) so that the sBitx can be tilted back slightly.

## Known Problems
1. Holes for RaspberryPi connectors (USB and RJ45) are high by about 1-2 mm. 
2. No holes provided to attach speaker.

![extra-cover_for_pi_hdmi](https://github.com/AJ6CU/3d-printer-models/assets/70183884/ac4a55d3-e08d-4f37-b58f-6fe6c431fe2c)

![extra-holes_for_raspberrypi_USB_too_high](https://github.com/AJ6CU/3d-printer-models/assets/70183884/66b72fa7-ffef-4250-9f4c-d5567024cd4e)

![extra-longer_15cm_video_cable_used](https://github.com/AJ6CU/3d-printer-models/assets/70183884/2dd9e33d-16d7-4fb0-b298-019776fcc795)

![extra-power_audio_connections](https://github.com/AJ6CU/3d-printer-models/assets/70183884/b84e9697-7e6a-4ff3-800b-c0cc639cf8cb)


73
Mark
AJ6CU
