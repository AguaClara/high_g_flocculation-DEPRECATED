# High G Flocculation, Spring 2018
#### Mehrin Selimgir, Roswell Lo, Kanha Matai
#### May 18, 2018

## Abstract
The High G flocculation team (High G Team) seeks to understand and mitigate the increase of pressure (also known as headloss) throughout experimental flocculators. First, The High G team found that a buildup of coagulant- and not clay, is causing the pressure buildup in the flocculator for particle removal teams. This pressure buildup may be affecting the removal efficiency of the flocculator as particle removal experiments progress. The High G team determined that using hydrophobic tubing is not an effective mean of reducing pressure buildup. Through various experiments the team found that pressure increase can be mitigated through creating a high shear force in the flocculator  through sudden, short increases in water flow. We have determined a value which is the lowest amount of shear force necessary to mitigate pressure.

## Introduction
Flocculation is a critical component of  the water treatment process in which particles, which have had their charges neutralized through coagulation, are prompted to collide and aggregate with other particles to form flocs. Flocs above a critical size will settle out due to gravity during sedimentation. Viscous shear in the flocculator drives collisions and the formation of these flocs. For the High G Team's specific experimental setup, flocs are solely composed of clay particles and coagulant. Polyaluminum Chloride (PACl) is used as our coagulant due to price and availability.  A fraction of the surface of the clay particles is covered in coagulant and when these particles are prompted to collide, a successful collision occurs due to electrostatic attraction: the positively charged coagulant particle neutralizes the negatively charged clay particle. The purpose of the flocculator is to subject particles to enough viscous shear to form particles large enough to settle.

Last semester, High G Flocculation worked on experimentally determining the ideal shear (G) value for flocculator performance by varying G through the flocculator . During these experiments,  the team found that pressure difference through the flocculator increased throughout every trial, while removal efficiency slightly decreased (effluent turbidity slightly increased). The High G team hypothesized that both the pressure increase and the decline in removal efficiency are due to PACl sticking on the walls of the flocculator, allowing less PACl to stick to clay particles. This semester the High G team seeks to understand and mitigate the effect of PACl sticking to the walls.

 In a full scale water treatment plant, the flocculator is large enough that coagulant on the flocculator walls would not affect particle removal, however, alleviating the pressure build up observed in the experimental apparatus will allow for better experimental design and research for all particle removal teams.

Our team sought to alleviate the pressure buildup through various methods such as using hydrophobic tubing, using a syringe to increase water flow, and adjusting pump settings to increase water flow.

## Literature Review and Previous Work

Last semester, while testing effluent turbidities at different shear values, the High G team measured the pressure increase through the flocculator as well. The following graph shows the pressure difference across the flocculator of one trial at G= 300 Hz and 1.4 mg/L coagulant.

![PressureDiffFall](https://lh3.googleusercontent.com/jwL4Ie4dEJRwinZ8Ra5fH19Oh3LU96HfDxKeQaJgdw6c-oo9tug3KTeaW5yRvmYDGQZsnpZjN4awtnSPXxvIpqq5s_RD5G-sDRfjLXeYNgtCMXaVerP1MPDI75HBEdND_dXLIadgC7qJoaj9OzIamMFSMMctlAGHcAPJFPnrVaxDOlxYVXlGc8yUOAtvKkiVY-qeBSx5UiDguqQ8TUL_lHi2fEKtRVzUDrEp4qFvQ5kC_Xy3hKx5MsZhwNYmifK-I_ADIQ8lvo5sW_p4AOmnGtPjTavqBSSP6dCHWLZfsivNUsDc9vp3twb1Y5AYqFeXVYtL74PD5ZC218BuwHh-EQBshJj6MGTwY65z6fvF9Tuq91aj7_JdKQq4epose-4ug27mc_RZcMln2wCITVOWmhSnRoQGYYqaXDWuQ4nixmPqkqlJRjOildJ_PFajAcu7RxD7PmBBGMlHvjc030PNiPNEz5FncBsiRT6uZc8N_OaUA-63ZvjH7sTyVCumKh3jR-ityA95S2EDgV2LKX_BoHh3g0Ziy26vHroV0cM2moM_BqPHnZIuywogA72EhTVNbNpFaGPO4uDK1VGr1RUi1uygc17Zb51uoxUm06c=w917-h580-no)
**Figure 1: Graph of Pressure Difference vs. Time from Fall 2017**

The pressure throughout the flocculator increased about 12 cm in 10 hours. The Fall 2017 team hypothesized that the pressure increase may have been contributing to the rise in effluent turbidity in all experiments looking to maximize particle removal efficiency.

![EffluentTurbiditiesVShear](https://raw.githubusercontent.com/AguaClara/high_g_flocculation/master/Effluent%20Graph%20Zoomed%20in.PNG)
**Figure 2: Graph of Effluent Turbidity at Different Shear Forces**

At all G values tested, after reaching a steady state floc blanket, the effluent turbidities increased slightly but steadily in each of our experiments.

The High G team hypothesized that coagulant buildup in the flocculator is the main contributor towards the observed increase in pressure different throughout the flocculator and is currently researching methods to mitigate that pressure increase. The mechanism through which coagulant buildup increases both pressure and effluent turbidity is unknown, but we think it may be from an increase of PACl getting stuck to the flocculator walls instead of sticking to and destabilizing clay particles, leading to a rise in effluent turbidity.

<div class="alert alert-block alert-danger">
Revise for spelling/grammar

This section is now really light without any outside references.

// will put old research from HRS back in.
</div>

<!--- Took out graphs from HRS and put in old High G graphs that are similar.
-->

# Methods

### Experimental Apparatus
This section will briefly describe key components of the team's experimental apparatus and explain their purpose. A more detailed description of the governing design calculations, ProCoDA variables and set points, and experimental setup can be found in the Manual available at the end of this report.
###The High G Setup
![ExperimentalApparatus](https://github.com/AguaClara/high_g_flocculation/blob/master/ExperimentalApparatus.PNG?raw=true)
**Figure 3: High G Experimental Apparatus**

As shown in Figure 3 above, the overall experimental setup consists of a flocculator, clay and coagulant reservoirs, tube settler, and five distinct pumps. For this semester, two different flocculator tubing were used: hydrophobic and regular tubing. Regular tubing is depicted in Figure 3 above. Tabulated below is a summary of the experimental materials and their respective functions.

![ApparatusMaterials](https://github.com/MehrinSelimgir/Personal_MS/blob/master/EquipmentFunctions.PNG?raw=true)

###Key Components
Flocculator design parameters were determined through Python calculations (detailed in the Manual section) and sedimentation design parameters were based on values derived from the High Rate Sedimentation Summer 2017 team. Furthermore, influent turbidity, coagulant dose, and residence time within the sedimentation tank were pre-established by all the Particle Removal subteams. A summary of these values are tabulated below.

![Flocparameter](https://github.com/MehrinSelimgir/Personal_MS/blob/master/FlocculatorParameters.PNG?raw=true)

Additionally a syringe is incorporated into the High G experimental setup in order to inject a burst of water into the flocculator. The intention of the syringe is to test whether a high speed injection of water is capable of knocking off coagulant from the flocculator. Technical specifications for the syringe are detailed in the Manual section.  The results of this are detailed in the Results and Analysis section below.

A pressure sensor, circled in red in Figure 4 below, is incorporated into our experimental setup (located at the inlet and outlet of the flocculator) to assess whether the water and flocculator pumps are maintaining constant pressure during each trail by measuring the pressure difference between water entering and leaving the flocculator.

![pressuresensor](https://github.com/MehrinSelimgir/Personal_MS/blob/master/pressuresensor.PNG?raw=true)
**Figure 4: Close-up of the Pressure Sensor**

Additionally, a pressure attenuator (denoted in Figure 3) is incorporated into the High G setup (located between the water pump and influent turbidimeter). It was noted by the High Rate Sedimentation subteam that within a single peristaltic water pump rotation, immense pressure was built and released within the flocculator.  As this effect was more pronounced at lower flow rates, this introduced another variable in floc formation when varying velocity gradient. Thus, a pressure attenuator was added to mitigate the large pressure release to the flocculator from each perstaltic water pump rotation.


It is important to note that a waste stream between the flocculator and tube settler is also incorporated i nto the experimental setup. The intention of this waste stream is to maintain a constant upflow velocity in the sedimentation tank while varying G in the flocculator. This is achieved through conservation of mass as the stream can only flow through the sedimentation tank and the effluent. The waste pump allows for a set amount of flow into the sedimentation tank while the rest flows out in the effluent.

The following is a general outline of the team's experimental setup. Refer to Figure 3 for images and locations of the stated equipment. Steps on how to use the High G experimental apparatus are detailed in the Manual below.

1. The water pump is used to vary the velocity of influent stream through the flocculator,and therefore varies G in a controlled manner.
2. The clay pump contaminates clean water with a well-mixed clay solution.  The pump and influent turbidimeter together used PID control to maintain a constant influent turbidity of 100 NTU.
3. The PaCl coagulant pump introduces PaCl coagulant to the well-mixed clay-water solution. The clay-water solution enters the flocculator where clay particles collide and aggregate to form large flocs.
4. To account for the difference in flow between the water pump and the  effluent pump, a wastestream between the flocculator and sedimentation tube is introduced to maintain a constant up
flow velocity through the sedimentation tube. The sedimentation tube is an apparatus that is intended to mimic the function of a sedimentation tank in a full-scale treatment plant.
5. The flocs enter the bottom of the tube settler. The larger and denser particles settle out and are carried out to the waste stream.
6. The treated water, passing through the tube settler, exits the top and enters the effluent turbidimeter and are subsequently  carried out through the waste stream.
7. The waste pump acts to ensure that settled flocs in the tube settler exit the system without clogging the tubes.
8. The effluent pump ensures that the upflow velocity within the tube settler is kept at 2 mm/s, as recommended by the High Rate Sedimentation subteam.

### Procedure
Steps on how to use the High G experimental apparatus are detailed below.

1. Use Python coagulant dosing calculation to determine the required coagulant pump speed for the desired coagulant dosage.
2. Check all valves and connections to make sure desired pathways are clear and undesired pathways are blocked.
3. Verify all influent, effluent and coagulant pumps are set to desired experimental flow rates.
4. Turn on influent pump to fill sedimentation tank with clean water.
5. Plug in clay stock stirrer if not already plugged in.
6. Turn on influent, effluent, and coagulant  pumps.
7. Set state to PID control in ProCoDA (this will turn on clay pump, water pump and also turn on data collection).

Throughout the experiments, the data we will be collecting and analyzing is the headloss through the flocculator with time.

Figure 5, below, is a general process flow diagram of High G Flocculation experimental procedure.

![ProcessFlowDiagram](https://github.com/MehrinSelimgir/Personal_MS/blob/master/ProcessFlowDiagram.PNG?raw=true)
**Figure 5: High G Flocculation Process Flow Diagram**

## Results and Analysis

When conducting the experiment comparing the headloss in identical experiments with solely changing the tubing from regular (non-hydrophobic) tubing to hydrophobic tubing, the trial yield achieved the following results (Figure 6 & 7).


![nonhydrophobic](https://github.com/AguaClara/high_g_flocculation/blob/master/Full%20test,%20Regular%20tubing.PNG?raw=true)
**Figure 6: Graph of Headloss vs. Time for Regular Tubing**

 ![hydrophobic](https://github.com/AguaClara/high_g_flocculation/blob/master/Full%20test,%20hydrophobic%20tubing-%20fixed.PNG?raw=true)
 **Figure 7: Graph of Headloss vs. Time for Hydrophobic Tubing**

The results showed an insignificant difference in headloss reduction since, in both experiments, the trial started at around 70cm and after 10 hours reached 120cm at a constant rate. This showed that the hydrophobic tubing was ineffective at minimizing headloss due to the coagulant.

In order to determine the cause of pressure build-up, trials were conducted testing individual components. First, the team tested just water to ensure that the pressure did not increase naturally throughout the length of the experiment. The results of the trial are illustrated in Figure 8 below.

![just water](https://github.com/AguaClara/high_g_flocculation/blob/master/water%20only.PNG?raw=true)
**Figure 8: Graph of Headloss vs. Time, Regular Tubing, Just Water Trial**

This experiment eliminated the possibility that the pressure build up was caused simply due to the actual set up of this experiment. This was consistent with the hypothesis, and the observation that whenever a new trial was ran, the pressure difference started at the same value every time. However, the team did see a small increase in pressure. This minor change in pressure could perhaps be attributed to changes in viscosity due to temperature changes throughout the day, but does not explain the majority of the increase in pressure. For the following experimental trials, the team wanted to observe how headloss behaved when adding coagulant into the system.

![water+coagulant,regtub](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Regular%20Tubing%20-fixed.PNG?raw=true)
**Figure 9: Graph of Headloss vs. Time, Regular Tubing, Water & Coagulant Trial**

Due to the computer restarting overnight, ProCoDA only recorded 3 hours of data for this trial. Nonetheless, the results were unexpected compared to what was hypothesized. The team's initial belief was that the combination of the coagulant with the clay was the primary cause of the headloss. Instead, this data (Figure 9) shows that the coagulant alone caused a significant pressure increase. In fact, the pressure increase was even more significant than experiments running with coagulant and clay.  In experiments running both coagulant and clay, headloss would increase from 70cm to 85cm in 3 hours whereas running solely coagulant had an increase from 70cm to 95cm in the same time. To ensure the hydrophobic tubing makes an insignificant difference in headloss, the same experiment was run again with hydrophobic tubing. Through this experiment, the difference between coagulant build up in the different tubings can be isolated.

![water+coagulant,hydtub](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Hydrophobic%20Tubing.PNG?raw=true)
**Figure 10: Graph of Headloss vs. Time, Hydrophobic Tubing, Water & Coagulant Trial**

Figure 10 depicts a continuous build-up of pressure. Comparing only the first 3 hours, there is a noticeable difference between the two (Figures 11 & 12). The headloss increase with hydrophobic tubing was almost half the change with regular tubing (15cm versus 25cm).

<div class="alert alert-block alert-danger">
Revise sentence two for content.

Also figures 11 and 12 show a significant change between the two piping choices. But earlier you said there was no difference. Explain these results more.
</div>

![water+coagulant,regtub3](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Regular%20Tubing%20-fixed.PNG?raw=true)
**Figure 11: Graph of Headloss vs. Time, Regular Tubing, Water & Coagulant, 3-Hr Trial**

 ![water+coagulant,hydtub3](https://github.com/AguaClara/high_g_flocculation/blob/master/Water%20+%20Coag,%20Hydrophobic%20Tubing(3).PNG?raw=true)
 **Figure 12: Graph of Headloss vs. Time, Hydrophobic Tubing, Water & Coagulant, 3-Hr Trial**

Another observation from this trial is the sudden drop in pressure around the hour 12 (Figure 10)- when the coagulant ran out. This potentially proves that running water for a short amount of time without coagulant can clear out the coagulant. A more focused graph at the 12th hour (Figure 13) shows a lost of almost all of the built up pressure within 2 minutes. This loss in pressure could be due to the pumping in of air bubbles as the coagulant pump continued to run. The team aims to analyze this further through future experimental trials.

![pressuredrop](https://github.com/AguaClara/high_g_flocculation/blob/master/pressuredrop.PNG?raw=true)
**Figure 13: Refined View of 12th-Hr Pressure Drop, Hydrophobic Tubing, Water & Coagulant Trial**

In all of our experiments observing the increase of headloss throughout the flocculator, we noticed that the pattern of pressure increase was consistently linear with time. To best compare experiments we measured the slope at which the pressure increased (∆cm/hr).


![BarChart](https://github.com/AguaClara/high_g_flocculation/blob/master/clay%20graphs.png?raw=true)
**Figure 14: Slope of Pressure Increase across 4 different experiments**

Comparing hydrophobic and regular tubing experiments, we observed that the hydrophobic tubing experiments had higher pressure increases. Since we did not observe a significant benefit in using hydrophobic tubing (contrarily, we saw higher pressure increases) we determined that hydrophobic tubing was ineffective in mitigating pressure increase and continued our following experiments with regular tubing.

The chart above shows that experiments ran with clay had lower pressure increases compared to experiments with only PACl. This suggests that coagulant is the main contributor to pressure increase and that the presence of clay counteracts pressure increase by "using up" PACl.

After seeing that the headloss in the flocculator dropped significantly once the coagulant ran out, the next step we tested whether this same result can be mimicked by pushing water through the flocculator at a more rapid speed to 'knock off' the coagulant build up. We first tried to see if we could use a 100ml syringe to push water through the system. The minimum time of emptying the syringe attained was 3.5 seconds, resulting in a very short but high shear push through the flocculator. Below is a screenshot of the ProCoDa readings of the filling and ejecting of water.

![syringe-pressure](https://github.com/AguaClara/high_g_flocculation/blob/master/syringe%20test.PNG?raw=true)
**Figure 15: ProCoDa reading of pressure sensor during a syringe press**

From this image, it can be seen that as the syringe is being filled, the pressure drops below zero as flow is now in the opposite direction (the syringe is being filled before the flocculator so water from the pump is being pushed into the syringe and water from the flocculator is being drawn backwards into the syringe). Once filled, the pressure readings began to normalize. When ejecting the water from the syringe to the original, a substantial pressure difference was caused, reaching 500 cm of pressure. After reaching the peak pressure, the headloss through the flocculator slowly begins to stabilize back to its original headloss of 100cm.


The set up enabled the High G team to test whether high flow water would be capable of knocking off all of the built up coagulant. To accomplish this, we ran an experiment with water and coagulant for 2 days to build up a substantial pressure difference in the flocculator. Then, the syringe was used in attempt to clear the tubing.

![syringe-test](https://github.com/AguaClara/high_g_flocculation/blob/master/initial%20syring%20test.png?raw=true)

**Figure 16:  Pressure Sensor Data of Syringe Experiment**

From figure 16, we see that pushing water through the flocculator at a high speed is indeed capable of clearing out the PACl responsible for increasing the pressure in the flocculator tubing. The pressure drop while filling the syringe and the pressure increase when ejecting the water has been neglected in the image in order to focus on the effect of the burst of water. The high sheer from the increased flow was successful in clearing the built up coagulant and dropping the pressure form 160cm to 80cm.

Although using the syringe was successful in removing the coagulant build up, it would be an inefficient method to remove coagulant throughout a long trial. It would require periodic manual labor and would be impractical for overnight trials. Our next experiments moved towards utilizing ProCoDa to automate the high flow of water through the flocculator.

While testing different pumps speeds, we found that the tubing separates from the pump at 60% of maximum rpm capacity of the pump (1300 ml/min flow) and should be considered an upper limit for flow due to physical setup constraints.

As our experiments ran at a normal flow rate of 190 ml/min, the first high speed pump experiment was set to increase flow of water to 3x the normal flow rate for 2 seconds at 28.8% of maximum capacity (600 ml/min) every hour.


![600ml-2sec](https://github.com/AguaClara/high_g_flocculation/blob/master/600-2sec-fixed.PNG?raw=true)
**Figure 17: Injecting flow at 600ml/min 2 sec every hour**

From ,figure 17 we see that this experiment was unsuccessful in mitigating pressure. However, from the data it can be seen that the bursts made an insignificant pressure increase - only an increase of about 30 cm- compared to around 400 cm for the syringe experiment. While visually observing the experiment, we saw that much the excess flow was accumulating in the flow accumulator and not actually passing into the flocculator. The next experiment was ran with a 10 second burst of increased flow (up from 2 seconds) and this flow rate produced roughly 300cm of pressure difference. Unsure if this was enough, the team decided to start from the highest value possible and move down. The next experiment was set to send bursts at at 50% maximum capacity (1120ml/min) for 10 second burst every hour.

![0.5-10sec](https://github.com/AguaClara/high_g_flocculation/blob/master/1120-10sec-fixed3.PNG?raw=true)

**Figure 18: Injecting 1120ml/min at 10 sec**

From figure 18, we saw that the bursts of flow was sufficient to prevent the build up of coagulant. Our goal is to find the lowest possible increase of flow needed to still successfully deter pressure increase. The next experiment was set up to send 10 second burst of water at 40% of the maximum capacity (880ml/min) every hour.


![0.4-10sec](https://github.com/AguaClara/high_g_flocculation/blob/master/880-10sec-fixed.PNG?raw=true)

**Figure 19: Injecting 880ml/min 10 sec**

From figure 19, we see that the burst of flow was unable to prevent the build up of coagulant in the tubing. Thus, the next experiment will be set to send bursts of 45% (1000ml/min) for 10 second every hour, as it is a value between the successful and unsuccessful trial.

![0.45-10sec](https://github.com/AguaClara/high_g_flocculation/blob/master/1000-10sec.PNG?raw=true)
**Figure 20: Injecting 1000 ml/min 10 sec**

From figure 20, we can deduce that this experiment was a success as the there was no buildup of pressure in the flocculator. To move forward, the next experiment will be set to send bursts at 42.5% (940 ml/min) for 10 seconds ever hour as it is the value between the highest unsuccessful trial of 0.4 and the lowest successful trial of 0.45.

![0.425-10sec](https://github.com/AguaClara/high_g_flocculation/blob/master/940-10sec.PNG?raw=true)
**Figure 21: Injecting 940 ml/min 10 sec**

From this experiment in figure 21, we can deduce that the experiment was unsuccessful as the head loss still increased. Hence, we have got the lowest value of 1000ml/min bursts every hour for 10 seconds. This values will now be converted into determining the shear value required to remove the coagulant.

## Conclusions
From comparing trials using Hydrophobic and Non-Hydrophobic tubing, we saw that hydrophobic tubing is not effective in preventing pressure increase, so research teams have been advised to continue using Non-Hydrophobic tubing.

By measuring the pressure increase in the flocculator in separate experiments with only water, experiments with water and coagulant, and experiments with water, clay and coagulant, the team was able to isolate coagulant as the main contributor of pressure increase in the flocculator.  We believe a portion of the coagulant being dosed into the solution is being lost in the buildup on the flocculator walls.

<div class="alert alert-block alert-danger">
Are you taking turbidity readings because I didn't see any in the results section. If you mention a decline in performance, there should be a mention of it in results/analysis
</div>

Through our experiments, we have found a method to automate the removal of coagulant build-up through bursts of high-speed water through the flocculator.

While our prior hypothesis stated that a decline in the performance of our treatment process was likely from coagulant being lost to the flocculator walls instead of interacting with clay, the current High Rate Sedimentation team has found that the PACl buildup is not a factor in declining removal efficiency. For our experiment that means that mitigating an increase in headloss will not necessarily lead to negating a decline in removal efficiency, but removals teams will have more consistent long term experiments by not having to take into account a pressure increase throughout the flocculator.


## Future Work

Possible future experiment for future teams include:

1. Testing different flocculator tubing sizes-  is an optimal G value for flocculation consistent with all flocculator sizes
2. Working with HRS to find the reason for floc blanket decay and declining removal efficiency as their experiments progress.
3. Measuring the amount of coagulant that sticks to flocculator walls, and determining the physical method by which causes pressure increase in the flocculator.

## Bibliography
AWWA/ASCE (2012).Water Treatment Plant Design.*Water Treatment Plant Design*. McGraw Hill,New York,fifth edition.

Carissimi, E., Miller, J., and Rubio, J.   (2007). Characterization of the high kinetic energy dissipation of the Flocs Generator Reactor (FGR) - ScienceDirect.

Galantino, C. and Kang, A. (2017).  High Rate Sedimentation, Summer 2017 - Overleaf.

Garland,  C.,  Weber-Shirk,  M.,  and  Lion,  L.  W.  (2017).   Revisiting  Hydraulic  Flocculator  Design  for Use  in  Water  Treatment  Systems  with  Fluidized  Floc  Beds. *Environmental  Engineering  Science*,34(2):122-129.

Kawamura, S. (1991).*Integrated Design and Operation of Water Treatment Facilities*.  Second edition.

O'Melia,  C.R.  (1972). Coagulation  and Flocculation: Physicochemical  Processes  for  Water  Quality Control,.

Pennock,  W.  H.,  Chan, F.  C.,  Weber-Shirk,  M.  L., and  Lion,  L.  W.  (2016). Theoretical Foundation and  Test  Apparatus  for an  Agent-Based  Flocculation Model. *Environmental  Engineering  Science*,33(9):688{698.

Swetland, K. A., Weber-Shirk, M. L., and Lion, L. W. (2014). Flocculation-Sedimentation Performance Model for Laminar-Flow Hydraulic Flocculation with Polyaluminum Chloride and Aluminum Sulfate Coagulants. *Journal of Environmental Engineering*, 140(3):04014002.

# Manual

## Fabrication Details
The majority of the High G Flocculation experimental apparatus consists of pre-manufactured equipment (pumps, stock tanks, turbidimeters, and pressure sensor). The sedimentation tube settler is fabricated by the High Rate Sedimentation subteam. The hydraulic flocculators are fabricated by the High G Flocculation team. The flocculators are assembled by wrapping the desired tubing (hydrophobic or regular) around a hollow, cylindrical piece of cardboard.  The flocculator is then mounted on to the experimental apparatus on adjustable metal hose clamps.

## Special Components
As a possible solution to pressure build up, this semester the team invested in fabricating a hydraulic flocculator using hydrophobic tubing. The initial experimental trials indicate that hydrophobic tubing produced an insignificant mitigation to headloss. Figure 22, below, summarizes the general technical specifications, pricing, and vendor information for both hydrophobic and regular tubing.

![FlocculatorTubing](https://github.com/MehrinSelimgir/Personal_MS/blob/master/FlocculatorTubing.png?raw=true)
**Figure 22: Hydrophobic and Regular Tubing Information**

In order to test whether injecting a short burst of fluid can effectively knock off coagulant built up in the flocculator, the High G team also incorporated a syringe in the experimental apparatus. The specifications for the syringe are detailed below in Figure 23.

![syringe](https://github.com/MehrinSelimgir/Personal_MS/blob/master/syringe.PNG?raw=true)
**Figure 23: Plastic Syringe Specifications**

## Experimental Checklist
**(Including Pre-Experiment Cleaning)**

The following is a general outline of tasks to be done prior, during, and after experimentation. ProCoDA is a software that is used extensively during experiments; the software allows the user to automate data collection and various components of the experimental apparatus. PID stands for proportional integral derivative and is calibrated to control the clay pump via ProCoDA.

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

### States

The initial High G state is called Run pump, ProCoDA runs the following rule:
    -if time in state >= run time, then Fast pump
    -in Run pump, the water pump is running at the set point called normal pump

The next state is called Fast pump, ProCoDA runs the following rule:
    -if time in state >= Floc removal time, then Run pump
    -in Fast pump, the water pump is running at the set point called Fast pump

This creates and hourly cycle of going from running the pumps at a normal speed to running them fast for a short period of time.



### Set Points

| Set Point             | Setting |
|:--------------------- |:------- |
| Turb Target           | 100     |
| P                     | 68      |
| i                     | 125     |
| D                     | 0       |
| Influent Turbidty ID  | 1       |
| Effluent Turbidity ID | 2       |
| Floc removal time     | 10      |
| Run time              | 3590    |
| Fast pump             | 0.5     |
| Normal pump           | 0.12    |


The table above shows the set points used in ProCoda to control the clay pump. The values of P, i, D were calibrated using this guide https://confluence.cornell.edu/display/AGUACLARA/Calibrating+PID+Control. The Turb Target is set at 100 NTU for all experiments as it is convention for this series of experiments.

The water pump is also controlled by ProCoDA. Whereas, the pump after the sedimentation tank is controlled manually and is set at 60 rpm to maintain a 2 mm/s upflow velocity through the sedimentation tank.

## Python Code
Calculations were done in Python to determine PaCl coagulant dosing parameters and flocculator design parameters in order to run experiments and construct experimental apparatus.

###PaCl Dosing Calculations

The calculation logic for determining the coagulant dosing are derived from Dr. Monroe Weber-Shirk's CEE 4540 Lecture notes.

```python
from aide_design.play import*

#inputs
C_sys = 1.4*(u.mg/u.L)
C_labstock = 70.9*(u.g/u.L)
Q_sys = 1.48*(u.mL/u.s)
K_dilution = .8*(u.mL/u.L)
V_reservoir = 5*(u.L)
Frac_reservoir = .76
Q_per_rpm = .001828 *(u.mL/u.s)

#Calculations
M_flow_coag = (Q_sys * C_sys).to(u.mg/u.s)
C_reservoir = (C_labstock * K_dilution).to(u.gram/u.L)
Q_reservoir = (M_flow_coag / C_reservoir).to(u.mL/u.s)
V_lab = ((V_reservoir * C_reservoir) / C_labstock).to(u.L)

#Outputs
RPM = Q_reservoir / Q_per_rpm
RunTime = ((V_reservoir * Frac_reservoir) / Q_reservoir).to(u.hour)

print('The RPM needed for this coagulent dosage is' ,RPM)

print('The run time is ', RunTime)
```


### Flocculator Design Calculations

Depending on what specifically future teams are intending to test, all input variables will need to be assessed and adjusted accordingly.

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
#Velocity gradient and shear needed to remove coagulant nanoparticles from tube walls

The purpose of this code is to convert the head loss value (observed through experimentation) that is enough to shear the coagulant nanoparticles from the tube walls to a velocity gradient and shear value.

```python
from aide_design.play import*
import math as m

#Inputs are Q_reactor, Diam_floctube,tube_length, v_k, v_d, h
Q_reactor=((1120) *(u.mL/u.min)).to(u.ml/u.second) # flow rate of the system

Q_Reactor=(Q_reactor).to(u.ft**3/u.second)

#print(Q_Reactor)

Diam_floctube=((3/16)*(u.inch)).to(u.ft)

radius_floctube=Diam_floctube/2

#print(Diam_floctube)

tube_length=43*(u.ft) #length of flocculator tubing

floc_vol=np.pi*(radius_floctube**2)*tube_length

theta=floc_vol/Q_Reactor #residence time

#print(theta)

h=(420*u.cm).to(u.m)#headloss needed to shear coagulant nanoparticles from the tube walls
v_k=(1*10**-6)*(u.m**2/u.s) #kinematic viscosity of water @ 25 deg C

G=((pc.gravity*h)/(theta*v_k))**(1/2) #velocity gradient

print((G).to(u.hertz))#velocity gradient

v_d=0.00089*(u.Pa*u.second) #dynamic viscosity of water @ 25 deg C
#print(v_d)

shear=v_d*G #shear needed to knock off coagulant from floc tubing

print(shear)

print('Thus',h, 'is enough to shear coagulant nanoparticles from the flocculator tubing. This head loss value correlates to a velocity gradient value of ' ,G,  'and a shear value of ' ,shear)





```


# To convert the document from markdown to pdf
pandoc Name_of_this_file.md -o TeamName_Research_Report.pdf
```
