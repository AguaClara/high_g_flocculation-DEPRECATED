# High G Flocculation, Spring 2018
#### Mehrin Selimgir, Roswell Lo, Kanha Matai
#### March 9, 2018

## Abstract
Previously, the High G team designed an experimental setup to test the effects of velocity gradient (G) on flocculator performance. Specifically the team sought to determine an optimal G value through effluent turbidity results.

For this semester, the team aspires to continue to conduct experiments to conclude on an optimal G value. Additionally, the team seeks to evaluate the use of hydrophobic tubing to minimize headloss, assess whether headloss can be mitigate through a sudden, short increase in pump speed, and overall to determine a relationship between coagulant dose and optimal G. As of now, our team has concluded that hydrophobic tubing does not significantly mitigate headloss.   



## Introduction
Flocculation is the water treatment process in which particles, which have had their charges neutralized through coagulation, are prompted to collide and aggregate with other particles to form flocs. The intention is that once these flocs conglomerate, they will settle out due to gravity during sedimentation. A driving factor in the formation of these flocs is from particle shear in the flocculator. For our specific experimental setup, flocs are solely composed of clay particles and coagulant (PACl). A fraction of the surface of the clay particles is covered in coagulant and when these particles are prompted to collide, a successful collision occurs due to electrostatic attraction: the positively charged coagulant particle neutralizes the negatively charged clay particle. The likelihood of such collisions to occur increases when particles scatter around at different velocities, hence a flocculator subjects flow to a specific velocity gradient.



## Literature Review and Previous Work

ROSWELL 123

*Discuss what is already known about your research area based on both external work and that of past AguaClara Teams. Connect your objectives with what is already known and explain what additional contribution you intend to make. Make sure to add APA formatted in-text citations. If you mention the author(s) in your sentence, you can simply give the year of publication.[(Logan et. al. 1987)](http://www.jstor.org/stable/pdf/25043431.pdf?acceptTC=true)*

Last semester, the High G team measured the pressure increase through the flocculator of one trial at 300 Hz and 1.4 mg/L coagulant.

![PressureDiffFall](https://lh3.googleusercontent.com/jwL4Ie4dEJRwinZ8Ra5fH19Oh3LU96HfDxKeQaJgdw6c-oo9tug3KTeaW5yRvmYDGQZsnpZjN4awtnSPXxvIpqq5s_RD5G-sDRfjLXeYNgtCMXaVerP1MPDI75HBEdND_dXLIadgC7qJoaj9OzIamMFSMMctlAGHcAPJFPnrVaxDOlxYVXlGc8yUOAtvKkiVY-qeBSx5UiDguqQ8TUL_lHi2fEKtRVzUDrEp4qFvQ5kC_Xy3hKx5MsZhwNYmifK-I_ADIQ8lvo5sW_p4AOmnGtPjTavqBSSP6dCHWLZfsivNUsDc9vp3twb1Y5AYqFeXVYtL74PD5ZC218BuwHh-EQBshJj6MGTwY65z6fvF9Tuq91aj7_JdKQq4epose-4ug27mc_RZcMln2wCITVOWmhSnRoQGYYqaXDWuQ4nixmPqkqlJRjOildJ_PFajAcu7RxD7PmBBGMlHvjc030PNiPNEz5FncBsiRT6uZc8N_OaUA-63ZvjH7sTyVCumKh3jR-ityA95S2EDgV2LKX_BoHh3g0Ziy26vHroV0cM2moM_BqPHnZIuywogA72EhTVNbNpFaGPO4uDK1VGr1RUi1uygc17Zb51uoxUm06c=w917-h580-no)

The pressure throughout the flocculator increased about 12 cm in 10 hours. The change in effluent turbidity throughout did not change. Prior research from the High Rate Sedimentation research team has indicated that at higher upflow velocity in the sedimentation tank, the floc blanket will decay and the effluent turbidity increases throughout a similar experimental trial, likely from the increase in pressure in the flocculator.

![SedTankDecay](https://www.overleaf.com/docs/11173977ftrfnxyhrpyv/atts/67486838)

The above graph shows a decrease in removal efficiency with time in the High Rate Sedimentation team's experiment at 3 mm/s upflow velocity in the sedimentation tank.  The higher upflow velocity shows a more pronounced difference in removal efficiency compared to High G Flocculation's Fall 2017 experiment where removal efficiency did not decline with time using a sedimentation tank upflow velocity for 2 mm/s.

The High G Flocculation team hypothesizes that coagulant buildup in the flocculator is the main contributor towards the observed increase in pressure different throughout the flocculator.



# Methods

### Experimental Apparatus
This section will briefly describe key components of the team's experimental apparatus and explain their purpose. A more detailed description of the governing design calculations, ProCoDA variables and set points, and experimental setup can be found in the Manual available at the end of this report.
###The High G Setup
![ExperimentalApparatus](https://github.com/AguaClara/high_g_flocculation/blob/master/ExperimentalApparatus.PNG?raw=true)
**Figure 1: High G Experimental Apparatus**

As shown in Figure 1 above, the overall experimental setup consists of a flocculator, clay and coagulant reservoirs, tube settler, and five distinct pumps. For this semester, two different flocculator tubing were used: hydrophobic and regular tubing. Regular tubing is depicted in Figure 1 above. Tabulated below is a summary of the experimental materials and their respective functions.

![ApparatusMaterials](https://github.com/MehrinSelimgir/Personal_MS/blob/master/EquipmentFunctions.PNG?raw=true)

###Key Components
Flocculator design parameters were determined through Python calculations(detailed in the Manual below) and sedimentation design parameters were based on values derived from the High Rate Sedimentation Summer 2017 team. Furthermore, influent turbidity, coagulant dose, and residence time within the sedimentation tank were pre-established by all the Particle Removal subteams. A summary of these values are tabulated below.

![Flocparameter](https://github.com/MehrinSelimgir/Personal_MS/blob/master/FlocculatorParameters.PNG?raw=true)



A pressure sensor, circled in red in Figure 2 below, is incorporated into our experimental setup (located at the inlet and outlet of the flocculator) to assess whether the water and flocculator pumps are maintaining constant pressure during each trail.

![pressuresensor](https://github.com/MehrinSelimgir/Personal_MS/blob/master/pressuresensor.PNG?raw=true)
**Figure 2: Close-up of the Pressure Sensor**

Additionally, a pressure attenuator (denoted in Figure 1) is incorporated into our setup (located between the water pump and influent turbidimeter), to mitigate the large pressure release to the flocculator from each perstaltic water pump rotation.



It is important to note that a waste stream between the flocculator and tube settler is also incorporated into the experimental setup. The intention of this waste stream is to fluctuate flow rate between the flocculator and the sedimentation tank to allow varying G values in the flocculator while maintaining a constant upflow velocity in the sedimentation tank.

### Procedure
The following is a general outline of the team's experimental setup. Refer to Figure 1 for images and locations of the stated equipment.

1. The water pump is used to vary the velocity of influent stream through the flocculator,and therefore varies G in a controlled manner.
2. The clay pump contaminates clean water with a well-mixed clay solution.  The pump and influent turbidimeter together used PID control to maintain a constant influent turbidity of 100 NTU.
3. The PaCl coagulant pump introduces PaCl coagulant to the well-mixed clay-water solution. The clay-water solution enters the flocculator where clay particles collide and aggregate to form large flocs.
4. To account for the difference in  
flow between the water pump and the  effluent pump, a wastestream between the flocculator and sedimentation tube is introduced to maintain a constant up
flow velocity through the sedimentation tube. The sedimentation tube is an apparatus that is intended to mimic the function of a sedimentation tank in a full-scale treatment plant.
5. The flocs enter the bottom of the tube settler. The larger and denser particles settle out and are carried out to the waste stream.
6. The treated water, passing through the tube settler, exits the top and enters the effluent turbidimeter and are subsequently  carried out through the waste stream.
7. The waste pump acts to ensure that settled flocs in the tube settler exit the system without clogging the tubes.
8. The effluent pump ensures that the upflow velocity within the tube settler is kept at 2 mm/s, as recommended by the High Rate Sedimentation subteam.

Figure 4, below, is a general process flow diagram of High G Flocculation experimental procedure.

![ProcessFlowDiagram](https://github.com/MehrinSelimgir/Personal_MS/blob/master/ProcessFlowDiagram.PNG?raw=true)
**Figure 4: High G Flocculation Process Flow Diagram**


## Results and Analysis

When conducting the experiment comparing the headloss in identical experiments with solely changing the tubing from regular tubing to hydrophobic tubing we achieved the following results.

![nonhydrophobic](https://github.com/AguaClara/high_g_flocculation/blob/master/Full%20test,%20Regular%20tubing.PNG?raw=true) ![hydrophobic](https://github.com/AguaClara/high_g_flocculation/blob/master/Full%20test,%20hydrophobic%20tubing.PNG?raw=true)

From these results we were able to see and insignificant result. In both experiments, the trial started at around 70cm and after 10 hours reached 120cm at a constant rate. This showed that the hydrophobic tubing was inefftive at minimizing headloss due to the coagulant. Hence we begun to test what exactly was causing the pressure build-up, hence we began testing individual components. We first tested just water to ensure this effect is not a mere natural thing caused by water in our system. Hence we ran a trial by running just water through the pipe.

![just water](https://github.com/AguaClara/high_g_flocculation/blob/master/water%20only.PNG?raw=true)

This experiment eliminated the possibility that the pressure build up was caused simply due to the actual set up of this experiment. This was what we hypothesized as whenever we started a new trial, we were able to start at the same pressure everytime. However, we were unable to predict the minute drop in pressure, however, this could attributed to changes in viscosity due to temperature changes throughout the day. We then began testing water with coagulant.

![water+coagulant,regtub](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Regular%20Tubing.PNG?raw=true)

Due to some an overnight issue, we were solely able to obtain 3 hours of valuable data for this trial. This experiment surprised us as it was not what we hypothesized.We believed it was the combination of both the coagulant along with the clay that was causing the headloss. Instead, this data shows that the coagulant alone causes the pressure increase. In fact, the pressure increase was even more significant. Within 3 hours, the pressure was able to rise from 70cm to 95cm, which is half the change when run with clay in a third of the time. This experiment was conducted with regular tubing, and hence, to ensure the hydrophobic tubing makes an insignificant difference in headloss, we ran an experiment with hydrophobic tubing too.

![water+coagulant,hydtub](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Hydrophobic%20Tubing.PNG?raw=true)

Looking at the data, we can see a continuous build-up of pressure. To fairly compare the results from the hydrophobic test and the regular tubing, we looked at the graphs for the first three hours of both experiments due to only having 3-hour long trial for regular tubing. The axes have been matched the axes to visually compare notice the difference between the two. From the experiment, the headloss with the change with hydrophobic tubing was almost half the change with regular tubing (15cm versus 25cm).

![water+coagulant,regtub3](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Regular%20Tubing.PNG?raw=true) ![water+coagulant,hydtub3](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Hydrophobic%20Tubing(3).PNG?raw=true)

Additionally, another very interesting observation from this trial is the sudden drop in pressure around the 12th hour- this is when the coagulant ran out. This potentially proves that running water for a short amount of time without coagulant can actually clear out the coagulant. A more focused graph at the 12th hour shows we were able to lose almost all of the built up pressure within 2 minutes. Hence,  ramping up water flow to 4x that of the trial could mean removing all of the built-up pressure in 30 seconds.(note: the x-axis has been changed to minutes to get a more precise and understandable reading). This loss in pressure could be due to the pumping in of air bubbles as the coagulant pump continued to run, however this will be our future tests.

![pressuredrop](https://github.com/AguaClara/high_g_flocculation/blob/master/pressuredrop.PNG?raw=true)

## Conclusions
*Explain what you have learned and how that influences your next steps. Why does what you discovered matter to AguaClara?

Make sure that you defend your conclusions with facts and results.*

From comparing trials using Hydrophobic and Non-Hydrophobic tubing, there was no noticeable difference in pressure increase. Hydrophobic tubing is not effective in our experiments in prevent pressure increase, so research teams will be advised to continue using Non-Hydrophobic tubing.

By measuring the pressure increase in the flocculator in separate trials measuring only water, water and coagulant, and water, clay and coagulant, the team was able to isolate coagulant as the main contributor of pressure increase in the flocculator.  Future experiments will focused on reducing coagulant build up in the flocculator in order to lower the amount of pressure increase.


## Future Work
*Describe your plan of action for the next several weeks of research. Detail the next steps for this team. How can AguaClara use what you discovered for future projects? Your suggestions for challenges for future teams are most welcome. Should research in this area continue?*

## Bibliography
*Logan, B. E., Hermanowicz, S. W., & Parker,A. S. (1987). A Fundamental Model for Trickling Filter Process Design. Journal (Water Pollution Control Federation), 59(12), 1029–1042.*

# Manual
The goal of this section is to provide all of the guidance that would be necessary for a future team to pick up your work where you left off. Please try to be thorough and put yourselves in the shoes of a newcomer to the project. Below are some recommended sections, but the manual will likely take a slightly different form for each team.

## Fabrication Details
Include any information related to the fabrication of equipment, experimental apparatuses, or technologies. Include the purpose of each step and the fabrication methods used. Reference appropriate safety precautions.

## Special Components
If your subteam uses a particular part that is unique and you could foresee a future subteam needing to order it or learn more about it, please include basic information like the vendor where it was purchased, catalog/item number, and a link to any documentation.

## Experimental Methods
### Set-up
Step 1.
* Put tasks in a sequential order.
* It is okay to have sub-lists.
  - Like this.

### Experiment
Step 1.

### Cleaning Procedure
Step 1.

## Experimental Checklist
**(Including Pre-Experiment Cleaning)**

The following is a general outline of tasks to be done prior, during, and after experimentation.

1. Drain the sedimentation tank and flocculator from previous experimental trial, if necessary.
2. Refill clay and coagulant stock tanks.
3. Run tap water through the system to rinse the flocculator, sedimentation tank, and connecting piping.
4. Rinse and refill turbidimeters.
5. Use Python coagulant dosing calculation to determine the required coagulant pump speed for the desired coagulant dosage.
6. Check all valves and connections to make sure desired pathways are clear and undesired pathways are blocked.
7. Verify all influent, effluent and coagulant pumps are set to desired experimental flow rates.
8. Turn on influent pump to fill sedimentation tank with clean water.
9. Plug in clay stock stirrer if not already plugged in.
10. Turn on influent, effluent, and coagulant  pumps.
11. Set state to PID control in ProCoDA (this will turn on clay pump and also turn on data collection).


## ProCoDA Method File
Use this section to explain your method file. This could be broken up into several components as shown below:

### States
Here, you should describe the function of each state in your method file, both in terms of its overall purpose and also in terms of the details that make it distinct from other states. For example:
\begin{itemize}
\item \underline{OFF} - Resting state of ProCoDA. All sensors, relays, and pumps are turned off.
\end{itemize}

### Set Points
Here, you should list the set points used in your method file and explain their use as well as how each was calculated.

## Python Code
Calculations were done in Python to determine PaCl coagulant dosing parameters and flocculator design parameters in order to run experiments and construct experimental apparatus.

###PaCl Dosing Calculations


```python
from aide_design.play import*

#inputs
C_sys = 1.4*(u.mg/u.L)
C_labstock = 70.9*(u.g/u.L)
Q_sys = 1.48*(u.mL/u.s)
K_dilution = .8*(u.mL/u.L)
V_resivor = 5*(u.L)
Frac_resivor = .76
Q_per_rpm = .001828 *(u.mL/u.s)

#Calculations
M_flow_coag = (Q_sys * C_sys).to(u.mg/u.s)
C_resivor = (C_labstock * K_dilution).to(u.gram/u.L)
Q_resivor = (M_flow_coag / C_resivor).to(u.mL/u.s)
V_lab = ((V_resivor * C_resivor) / C_labstock).to(u.L)

#Outputs
RPM = Q_resivor / Q_per_rpm
RunTime = ((V_resivor * Frac_resivor) / Q_resivor).to(u.hour)

print('The RPM needed for this coagulent dosage is' ,RPM)

print('The run time is ', RunTime)
```
### Flocculator Design Calculations

```python

from aide_design.play import*
import math as m


#Inputs
Q_reactor=(4/3) *(u.mL/u.s) # flow rate of the system
Gtheta_goal=20000 #target G*theta to design flocculator to
Diam_floctube=(3/16)*(u.inch)
R_c=5*u.cm #radius of curvature (the radius of the tube the flocculator is wrapped around)
Re_pipetransition=2100
v=(1*10**-6)*(u.m**2/u.s)
e_pvc=0.12*u.mm #roughness of PVC Re_pipetransition

#Calculations
Re_f= ((4*Q_reactor)/(np.pi*Diam_floctube*v)).to(u.dimensionless)


print(Re_f)


#def fric_function(Q_reactor,Diam_floctube,v,e_pvc)
if Re_f > Re_pipetransition:
  print('Re_f is greater than Re_pipetransition')
  fric=0.25/((m.log((e_pvc/3.7*Diam_floctube)+(5.74/(Re_f**0.9))))**2)
else:
  fric=64/(Re_f)
  print('Re_f is not greater than Re_pipetransition')
  print(fric)
L=1
h_f=fric*(8/(pc.gravity*np.pi**2))*((L*Q_reactor**2)/(Diam_floctube**5))



R=R_c.to(u.inch)

De=(((Diam_floctube/R)**2)*Re_f)
print(De)

friction_ratio=1+(0.33*m.log(De)**4)
print(friction_ratio)

h_friction=h_f*friction_ratio
Area=(np.pi/4)*Diam_floctube**2
theta=(Area*L)/Q_reactor

ED_floc=(h_friction*pc.gravity)/theta

epsilon=ED_floc.to(u.mW/u.kg)
print('Energy dissipation rate is',epsilon)

G_floc=((epsilon/v)**(1/2)).to(u.second**-1)
print(G_floc)

theta_goal=(Gtheta_goal/G_floc).to(u.minute)
print(theta_goal)

L_goal=theta_goal*(Q_reactor/Area)

L_floc=L_goal
print('The length of flocculator tubing should be', L_floc.to(u.ft))
```


```python
# To convert the document from markdown to pdf
pandoc Name_of_this_file.md -o TeamName_Research_Report.pdf
```
