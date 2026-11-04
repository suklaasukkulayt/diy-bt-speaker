# DIY Portable Bluetooth speaker  
## About  
This is a GitHub repository for the DIY Portable Bluetooth speaker project made for the Stardance event. [Link to the project](https://stardance.hackclub.com/projects/39114)  

This speaker uses a main board from an old Streetz bluetooth speaker ([CMB-110](https://amzn.eu/d/0365UWwi)), with Bluetooth, AUX and USB playback support. It even supports TWS. It also has a ~3000mah battery and LED lighting. The amplifier has a peak power of 2*15W.  
## Building instructions  
### Required materials:  
Check out [materials_speaker.csv](./materials_speaker.csv)  
You will also need wood (I used particleboard), staining varnish and acrylic sealant and screws of your choice. I used mostly Torx screws, but also some Philips screws for buttons.  
The particleboard I used is 9mm thick.  
### Dimensions:
#### Front and back:
Width: ~125mm  
Height: ~125mm  
#### Sides:
Width: ~165mm  
Height: ~125mm  
#### Top and bottom: 
Width: ~165mm  
Height: ~140mm  

Both speaker elements are about 4"  
Passive bass radiator is about 3,5"  

### Pinout
RGB LED to CN2 (VCC, GND, DATA (data not used here, but it can be) with ~33 Ω resistor  
Speakers to SPKL3 and SPKL4  
Battery to 5pin connector without proper marking (no pin name)  
See [pinout.jpg](./pinout.jpg)

### Other info  
Screw holes are **not** included in the CNC files. You need to make them by yourself. Also the top panel with the buttons does not have a file with the holes for the rubber button thing.  
More info about other stuff and (maybe) building about this project is here:  [Stardance](https://stardance.hackclub.com/projects/39114)  
Because I used a closed source amplifier board, i'm unable to provide firmware or other stuff for it.  

**Showcase video:** [YouTube](https://www.youtube.com/shorts/X91US23UtD8)  

### Photos from inside:
<img width="3072" height="4096" alt="IMG20261031161302" src="https://github.com/user-attachments/assets/3b9f89a7-062c-4a26-8b46-ef3a2e1293e9" />
<img width="2448" height="3264" alt="IMG20261031161342" src="https://github.com/user-attachments/assets/56201c3e-4543-4c84-aac3-cb84073f01ba" />
<img width="3072" height="4096" alt="IMG20261031161313" src="https://github.com/user-attachments/assets/e65f0470-d648-48a4-aa4b-57ce6b0b36bb" />
<img width="3072" height="4096" alt="IMG20261031164540" src="https://github.com/user-attachments/assets/8e4bdcd4-6a10-408d-8069-dbf06cd0afb9" />
<img width="2448" height="3264" alt="IMG20261031161405" src="https://github.com/user-attachments/assets/8e5a7cb2-e0ba-4c13-ad5d-8b876cd96f2c" />
<img width="3072" height="4096" alt="IMG20261031165404" src="https://github.com/user-attachments/assets/b6907783-158d-41e5-946a-1d207b18e5b7" />

### Photos from outside:  
<img width="2393" height="2312" alt="IMG20261031202654~2" src="https://github.com/user-attachments/assets/8f788b0f-dcbe-4777-93df-0371bac9c827" />
<img width="2357" height="2312" alt="IMG20261031202659~2" src="https://github.com/user-attachments/assets/9976686c-1e2b-4694-9b87-0b5754c13fdd" />
<img width="3000" height="2837" alt="IMG20261031202710~2" src="https://github.com/user-attachments/assets/9e654716-1f28-4407-95e8-7d75f8e63d70" />
