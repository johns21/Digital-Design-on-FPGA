# Digital-Design-on-FPGA
Documentation of Traffic light controller design using Virtual FPGA Lab for workshop organized by VSD

# Introduction
- Traffic control system is used to control and coordinate the traffic.
- Here we implement a simple verilog project to understand Traffic light control System using Virtual FPGA

# Tools used
Makerchip Virtual FPGA

# Theory
- Here we will implement a Simple Traffic control system using Virtual FPGA.
- There are three control signal which controls the Traffic system.
  - RED Light   - Indicates that the driver Should STOP.
  - Yello Light - Indicates that RED Signal is about to display.
  - Green Light - Indicates that the driver can GO.
- Here we design a simple 4 way Traffic controller such that Green signal hold for 8sec and yellow signal hold for 4sec.
- Here we use the concept of FSM.
- The below figure shows different states in FSM.


    ![image](https://user-images.githubusercontent.com/71406141/138126908-d4f4ac03-e3fe-4d42-9d63-147145b2fe50.png)
    
- In our experiment the output is displayed or understood by looking at 7 segment display.
![image](https://user-images.githubusercontent.com/71406141/138131919-f8f52a8b-6588-40b5-9d62-edab47aecf8c.png)
- if 'D' is ON it represents Green Signal.
- If 'G' is ON it represents Yellow Signal.
 
 
 # Results
 
 -At Zero cycle, The green light of North is ON.
 
 
![image](https://user-images.githubusercontent.com/71406141/138138319-38a40cf6-a039-41df-a7f9-f13cdf09a480.png)

 
 - At 8th cycle, Yellow Light of North is ON.
 
 
 ![image](https://user-images.githubusercontent.com/71406141/138138431-1293293a-8a57-4b0a-bb64-05c5228f07a8.png)
 
 
 - At 12th cycle, Green Light of EAST is ON.


 ![image](https://user-images.githubusercontent.com/71406141/138138497-31396e02-287e-4d4f-859e-e82772db4420.png)
 
 
 - At 19th cycle, Yellow Light of EAST is ON.
 
 
 ![image](https://user-images.githubusercontent.com/71406141/138138557-6abd7f4b-c331-4420-a133-f292f7c95923.png)
 
 
 - At 23rd cycle, Green Light of SOUTH is ON.
 
 
 ![image](https://user-images.githubusercontent.com/71406141/138138606-f8058f15-b616-4fa8-8136-81261cce89fa.png)
 
 
 - At 30th cycle, Yellow Light of SOUTH is ON.
 
 
 ![image](https://user-images.githubusercontent.com/71406141/138138678-a50bda45-232e-4b3d-8861-fc49ba570a3f.png)


 - At 34th cycle, Green Light of WEST is ON.
 
 
 ![image](https://user-images.githubusercontent.com/71406141/138138718-0435a6f3-9975-4c67-8692-c8211ee98808.png)


 - At 41st cycle, YELLOW Light of WEST is ON.
 
 
 ![image](https://user-images.githubusercontent.com/71406141/138138792-5808eeb5-e56a-449f-8a99-fa8fe49d354a.png)

 
 - At 45th cycle, again GREEN Light of NORTH is ON.
 
 
 ![image](https://user-images.githubusercontent.com/71406141/138138181-4b966475-2a1c-44fc-bc56-0a19635f3952.png)
 
# References
- https://github.com/BalaDhinesh/Digital-Design-on-FPGA--VSDOpen21.git

# Acknowledgements
- Kunal Ghosh,Co founder, VSD Corp.Pvt.Ltd
- Steve Hoover,Founder, Redwood EDA
- Bala Dhinesh, IIT Madras

 
 






    
