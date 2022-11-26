# Li-ion Battery Management System

 - Designed and simulated using of Li-ion Battery Management System (BMS) for Electric Vehicles using MATLAB Simulink under different parameters i.e., Cell voltage, current, temperature. 
 - Performed Passive cell balancing using resistors considering SoH and SoC of the Battery Pack.
 - Simulated and analysed running data in graphical form to improve the performance of BMS.
 - Made a report to enhance the performance of battery pack using BMS.
## Deployment

To deploy this project

```bash
1. Install MATLAB software.
2. Your college/company may already provide access to MATLAB, Simulink, and add-on products through a campus-wide license.
3. Otherwise, go to the link, https://in.mathworks.com/store/link/products/student/SV?s_tid=ac_buy_sv_but1  to buy license and install the software.
4. Clone this project.
5. Or go to Simulink > New project from source code > git > retrieve.  
6. Go to the MATLAB > Home > Simulink > Open file location > Run and run these simulations.
```

## Screenshots


PASSIVE CELL BALANCING
<br /> The "fcn" Block at right has code written inside to regulate the heat dissipation of cells having different emfs.

<img width="791" alt="Screenshot 2022-11-17 181553" src="https://user-images.githubusercontent.com/116304936/203603974-b4e01f27-005a-49d4-afb2-26e891105c50.png">

SCOPE
<br /> Three cells with different emfs are connected. The cell with highest emf (80v) dissipates heat more rapidly through resistor than other two i.e. 75v and 70v.
<br /> After some time Each cell has same emf around 69.99998v (70v approx.)

<img width="960" alt="Screenshot 2022-11-17 181839" src="https://user-images.githubusercontent.com/116304936/203604355-51016a62-5327-46c1-9205-55812f4cf6d2.png">

BMS

<img width="896" alt="Screenshot 2022-11-17 182107" src="https://user-images.githubusercontent.com/116304936/203604442-7a3d1283-b9fe-4524-8da4-ef0c6279ad82.png">

SCOPE

<img width="960" alt="Screenshot 2022-11-17 182230" src="https://user-images.githubusercontent.com/116304936/203604529-3243a9d5-f32a-4322-8540-138a12a39341.png">
