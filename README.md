### RED VIMANA: A Project to Fly

When  I was young (younger than now), I watched airplanes pass over my head like every day and i used to ask that same exact question,”how could that big and heavy thing fly as if it was a feather” on loop i.e.  
for(age = 5; !I_understand_how_it_works; age++) 
{

    ask_question("How could that big and heavy thing fly as if it were a feather?");
}
**//c++ reference lol*

Red Vimana (in which Vimana means mystical flying vehicle in Sanskrit) is my attempt to finally answer that question for myself by building my own drone.
I’m moving from "wondering how things fly" to "making things fly." This project for me is about more than just a drone but it’s about mastering the physics, the electronics, and the grit required to build a complex machine that defies gravity.  


**The Build:**  
The Brain   : SpeedyBee F405 v4  
Motor       : R2207 2450KV Brushless Motor  
Propeller   : Gemfan Flash 5149 Propeller  
Battery     : Tattu funfly 1550mAh 100C 14.8V 4S-LiPo Battery  
Firmware    : Betaflight  
Detailed Parts List with pricing and etc: https://github.com/notsonerdysid/DRONE-BLUEPRINT/blob/main/BILLS%20OF%20MATERIAL/BOM.csv 

  
**Learning Objectives**
Through this project, I aim to develop practical engineering skills in:
- Flight dynamics and thrust generation
- Flight controller architecture and stabilization systems
- PID tuning and control systems using Betaflight
- Master using Onshape(starting from tinkercad)
- Electronics integration and circuit planning
- LiPo battery safety and power management
- Debugging and testing embedded systems  
My main goal is to gain hands-on understanding of how hardware, software, and the physics behind which will work together in autonomous systems.

How would I fly this?
I will be using Radiomaster Pocket Radio Controller because it offers hall-effect gimbals and also very afforable; ELRS version recommended for the HGLRC receiver which can give range upto more than 1.6km. I'll upgrade this same drone in fpv monster later on in future, with the upgrades like adding cool landing pad and more
and I will configure the flight controller using Betaflight 4.5, to tune the PID values to make my drone stable.
  
  
**Schematics circuit diagram**  
I created my schematics diagram with the help of EasyEDA,which looks like this:
<img width="730" height="515" alt="image" src="https://github.com/user-attachments/assets/fae1e27f-8f86-43b9-a7be-4627f83d132f" />  
for more info you can check out this link:
[SCHEMATICS/SCHEMATICS.md](https://github.com/notsonerdysid/DRONE-BLUEPRINT/blob/main/SCHEMATICS/SCHEMATICS.md)

    
**3D Design for my Drone**  
I get myself to learn 3d designing on Onshape before that i used to design only on tinkercad, It is really a JUMP which I am really proud of. My drone's weight will be around 670gm (290gm frame alone) which in my opinion is not very ideal for 5" drone but I prioritize safe and stable flight first. And after I will make my drone fly I will be upgrading its frame to have weight of around 100gm but later on. I'll be using PETG as my material for the drone, though it is not very stiff as compared to PLA,i have Arm thickness of 8mm and since my drone will be quite heavier PETG is better choice as it has better heat resistance.
For the real drone design here are the all the measurements:  
1. Wheelbase : 240mm
2. Each arm length: 120mm
3. Arm thickness : 8mm
4. Arm width : 15mm
5. base plate : 65mm x 65mm  

It looks like this:
Without Components
<img width="1128" height="885" alt="Screenshot 2026-02-24 145243" src="https://github.com/user-attachments/assets/126b3dd6-1f52-4253-a4eb-c9abe9412cda" />  
with components
<img width="1003" height="676" alt="Screenshot 2026-02-24 144842" src="https://github.com/user-attachments/assets/d288c8c2-b4e9-490e-922d-289f56c26032" />  
LINKS TO CHECK OUT MY DRONE DESIGN:-  
.stl FILE : (https://github.com/notsonerdysid/DRONE-BLUEPRINT/blob/main/FRAME%20DESIGN/DRONE%20DESIGN%20V3.0.step)  
.step FILE : (https://github.com/notsonerdysid/DRONE-BLUEPRINT/blob/main/FRAME%20DESIGN/DRONE%20DESIGN%20V3.0.stl)  
onshape link : https://cad.onshape.com/documents/e85d7f9eb9a1812312bbe570/w/3836bb74fdebc3d255a65e92/e/69b71edf874c67ab1f65e7c8?renderMode=0&uiState=699ddd75395985ace820c65e     

**Budget and Funding Use**  
I have estimated the cost of essential components is approximately $332.19.
A detailed parts list with pricing and links is provided in the Bills of Materials document.
LINKS FOR THE BOM:-
.csv file : [https://github.com/notsonerdysid/DRONE-BLUEPRINT/blob/main/BILLS%20OF%20MATERIAL/BOM.csv](url)    
docs File : [https://docs.google.com/document/d/1cGEEqKZGyfhhKSGbjoTj9GcO14NI_GNIEH85b2QIAr4/edit?usp=sharing](url)  
.md File : [https://github.com/notsonerdysid/DRONE-BLUEPRINT/blob/main/BILLS%20OF%20MATERIAL/BOM.md](url)  
I have tried to make t the budget below the funding limit. Any additional costs caused by shipping or unforeseen expenses will be covered personally. Minor assembly materials like soldering iron, screws, zip tie, double tape, etc will also be provided by me.
Funding will be used only for essential learning components.

**Summary for how I spend my time before submitting**  
I have invested 75+ hours over 16 days designing, engineering and learning new stuff for this drone from very basic.  
*I have worked researching, learning 3d designing from Tinkercad to Onshape, electronics and schematics planning, Learning how does a Drone even fly, and cost optimization, journalling, debugging Drone design over and over*  
I litterly design my drone frame again and again for more than 6 times through multiple frame designs to ensure to maintain structural strength, safe and stable flight performance.
I learned some basic engineering principles such as thrust-to-weight analysis in which I have resulted with ratio of 8.05:1 at max thrust, Basics for what is Pid control, and etc.
I created detailed schematics and a complete bill of materials while reducing the budget from $400 to $326.07. 
I learned basics for how imu sensor coordinate with FC and ESC.
I also journal everything I worked with for everyday for past 16 days.   
here is a pdf that where I have clicked photos of the notes ( I like to study making notes) which I had created during prototyping and learning( these photos arent mentioned before thats why i put i here for proof that i am not saying 75+ hour)  
LINK: [https://drive.google.com/file/d/1fnM4xNsK86z5Zi4jRAErgGUUMKQ07n5t/view?usp=sharing](url)  

**Action**  
I will add a soft-mount the Flight Controller. A heavy 3D-printed frame will vibrate crazy and Betaflight's gyro will hate it. I will use M3 heat-set brass inserts. My battery will be positioned underneath the base plate as shown in the design and will attatch it with the help of a strap

In this project I will demonstrate my self-driven learning and technical problem solving.
All of my progress, failures, and improvements are openly documented for transparency and reproducibility.
The design phase is complete and ready for physical prototyping and testing.
Funding will directly enable hardware implementation and validation of this engineered system.
This support will accelerate my growth as a builder and help transform theory into real flight.

THANK YOU!!

