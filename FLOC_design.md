#Flocculator Design Calculations


```python
from aide_design.play import*

#Inputs
Q_reactor=4/3 *(u.mL/u.s) # flow rate of the system
Gtheta_goal=20000 #target G*theta to design flocculator to
Diam_floctube=(1/8)*(u.inch)
R_c=5*u.cm #radius of curvature (the radius of the tube the flocculator is wrapped around)
Re_pipetransition=2100
v=(1*10^-6)*(u.m**2/u.s)
e_pvc=0.12*u.mm #roughness of PVC Re_pipetransition

#Calculations
Re_f= 4*Q_reactor/(np.pi*Diam_floctube*v)


#def fric_function(Q_reactor,Diam_floctube,v,e_pvc)
if Re_f > Re_pipetransition:
  print('Re_f is greater than Re_pipetransition')
  fric=0.25/((log((e_pvc/3.7*Diam_floctube)+(5.74/(Re_f**0.9))))**2)
else:
  fric=64/(Re_f)
  print('Re_f is not greater than Re_pipetransition')
  print(fric)
L=1
h_f=fric*(8/(pc.gravity*np.pi**2))*((L*Q_reactor**2)/(Diam_floctube**5))
R=0.556*u.kelvin
De=((Diam_floctube/R)*Re_f).to*(u)
print(De)

#friction_ratio=1+(0.33*np.log(De)**4)















```
