#RED VIMANA: A Project to Fly

When  I was young (younger than now), I watched airplanes pass over my head like every day and i used to ask that same exact question,”how could that big and heavy thing fly as if it was a feather” on loop i.e. 

for(age = 5; !I_understand_how_it_works; age++) 

{

    ask_question("How could that big and heavy thing fly as if it were a feather?");
    
}
//c++ reference lol. 

Red Vimana (in which it means mystical flying vehicle in Sanskrit) is my attempt to finally answer that question for myself by building my own drone.
I’m moving from "wondering how things fly" to "making things fly." This project for me is about more than just a drone but it’s about mastering the physics, the electronics, and the grit required to build a complex machine that defies gravity.


The Build:

The Brain   : SpeedyBee F405 v4
Motor       : EMAX RS2205
Propeller   : Gemfan Flash 5149 Propeller
Battery     : Tattu funfly 1550mAh 100C 14.8V 4S-LiPo Battery
Firmware    : Betaflight
Mission     : To achieve a stable, high-speed flight while maintaining a "clean" build.

Detailed Parts List with pricing and etc: [Link Text](BOM.md)

How would I fly this?
I will be using Jumper T14 Radio Controller, I chose the Jumper T14 because its 1W internal ELRS module and Hall Effect gimbals which will be really responsive for my custom built airframe. I'll upgrade this same drone in fpv monster later on thus t14 will be awesome choice. Similarly I will use ELRS Nano as my Receiver which is affordable and compatible with my t14.
and I will configure the flight controller using Betaflight 4.5, to tune the PID values to my my drone stable.


**Schematics circuit diagram**
I created my schematics diagram with the help of EasyEDA,which looks like this:
<img width="730" height="515" alt="image" src="https://github.com/user-attachments/assets/fae1e27f-8f86-43b9-a7be-4627f83d132f" />

for more info you can check out this link:
[SCHEMATICS/SCHEMATICS.md](https://github.com/notsonerdysid/DRONE-BLUEPRINT/blob/main/SCHEMATICS/SCHEMATICS.md)

**3D FOR MY DRONE'S FRAME**
I'll be using PETG as my material for the drone. It is light, durable, strong.
my 3d design for the frame looks like this:

//thanku for reading my story :)

