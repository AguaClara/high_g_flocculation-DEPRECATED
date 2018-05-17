#Velocity gradient and shear needed to remove coagulant nanoparticles from tube walls
The purpose of this code is to convert the head loss value (observed through experimentation) that is enough to shear the coagulant nanoparticles from the tube walls to a velocity gradient and shear value. 



```python

from aide_design.play import*
import math as m

#Inputs
Q_reactor=((1120) *(u.mL/u.min)).to(u.ml/u.second) # flow rate of the system

Q_Reactor=(Q_reactor).to(u.ft**3/u.second)

#print(Q_Reactor)

Diam_floctube=((3/16)*(u.inch)).to(u.ft)

radius_floctube=Diam_floctube/2

#print(Diam_floctube)

tube_length=43*(u.ft)

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

<3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3 <3
