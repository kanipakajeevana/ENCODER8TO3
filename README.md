# ENCODER8TO3
# AIM
To simulate and synthesis Encoder using vivado.
# APPARATUS REQUIRE
vivado 2023.2 software.
#PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs
# CIRCUIT DIAGRAM AND TRUTH TABLE

![image](https://github.com/kanipakajeevana/ENCODER8TO3/assets/170450203/79d7556e-a347-4a0f-8452-acd3f42c6beb)
![image](https://github.com/kanipakajeevana/ENCODER8TO3/assets/170450203/f18cbeb6-beb9-4e7c-afb1-acf95cca6466)
![image](https://github.com/kanipakajeevana/ENCODER8TO3/assets/170450203/d69a7b08-d6b3-4306-97b6-5802152ada98)
![image](https://github.com/kanipakajeevana/ENCODER8TO3/assets/170450203/3fad4892-c475-48d5-a593-5777afe5b22e)
# VERILOG CODE
module encoder(d,a,b,c);

input [7:0]d;

output a,b,c;

or (a,d[4],d[5],d[6],d[7]);

or (b,d[2],d[3],d[6],d[7]);

or (c,d[1],d[3],d[5],d[7]);

endmodule
# OUTPUT
![image](https://github.com/kanipakajeevana/ENCODER8TO3/assets/170450203/6ae54a9f-0492-46c0-ae4b-ee68e664241f)
# RESULT
Thus, the verilog program for Encoder has been simulated and verified successfully.








