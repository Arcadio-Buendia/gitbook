Q. A bullet with initial speed $v_o$ is fired at a log of wood. The resistive force by wood on the bullet is given by $\eta v^\alpha$, where $\alpha<1$. What is the time taken to stop the bullet inside the wood log?
#### Understanding the question
 
``` python
from vpython import *
#Screen size to display graph and animation
scene1=canvas(height=400,width=980)
graph1=graph(height=300,width=980,xtitle='time',ytitle='velocity')

#defining the log object, bullet object and graph style
wood=cylinder(pos=vec(15,0,0),length=19,color=color.red,opacity=0.5);
bullet=sphere(radius=0.2,vel=vec(15,0,0),make_trail=True,interval=10,trail_type='points')
graph=gdots(color=color.green);

dt=0.01
time=0
scene1.camera.follow(wood)
while bullet.vel.x>0:#Stop animating once our bullet is no longer in motion
    bullet.acc=vec(0,0,0)
    if bullet.pos.x>=wood.pos.x-wood.length/2 and bullet.pos.x<=wood.pos.x+wood.length/2: #apply acceleration only when bullet is inside wood
        bullet.acc=vec(-bullet.vel.x**0.9,0,0)
    bullet.vel+=bullet.acc*dt
    bullet.pos+=bullet.vel*dt
    graph.plot(time,bullet.vel.x)
    time+=dt
    rate(1/dt)
print('time:',time)
```

![](bullet%20in%20a%20log.excalidraw.md)

#### Designing an Answer
 - We are given the force, we only need to apply newton's laws of motion to find out everythin.
 $$F=\eta v^\alpha=am=\frac{dv}{dt}m$$
 $$\implies dt=\frac m\eta\frac{dv}{v^\alpha}$$
 
#### Solution
Integrating hte above, $$\int_0^t dt=\frac{m}{n}\int_{v_o}^0\frac{dv}{v^\alpha}$$
$$\implies t=\frac{m}{n}\frac{v_o^{1-\alpha}}{1-\alpha}$$