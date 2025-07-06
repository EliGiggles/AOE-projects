Inductors: Like capacitors - except V = L*dI/dT
They supply more voltage to keep current constant, 
![image](https://github.com/user-attachments/assets/03275839-863f-4225-9a14-8af8c7771f4a)
Product of the right-hand rule - changing current creates a magnetic field (and so opposing voltage)

Energy = 1/2*L*i^2
Inductance = flux through inductor/current nessecary to produce that flux
Flux porportional (in a coil) to number of turns squared
Wheeler's Formula
<img width="154" alt="image" src="https://github.com/user-attachments/assets/2a4f9743-d1b8-405a-8333-88a286f682e1" />
K= 1.0 or 0.395 for dimensions in inches or centimeters, respectively

Works when l > 0.4d
Boost and buck converters

<img width="293" alt="image" src="https://github.com/user-attachments/assets/c1600f27-12de-4e1f-a3ca-be491b166ea9" />
The averange voltage across both these inductors must be zero - otherwise the current keeps increasing. Therefore, the current must on averange be the same in each cycle.

Buck Converters:

When current is pushed through the inductor while the switch is open, the inductor will produce a significant but decreasing opposing voltage (so a net lower voltage). With the switch closed, the inductor continues to provide decreasing current, outputting a positive but decreasing voltage in the same direction as the source.
change in On_current
<img width="332" alt="image" src="https://github.com/user-attachments/assets/22c952aa-ebbc-4b42-b0c0-9ef4f485f407" />

change in Off_current
<img width="251" alt="image" src="https://github.com/user-attachments/assets/1f5e7c89-777c-4515-a6fa-23e965c0298a" />

Since change in current. = 0 on-current + off_c = 0

This simplifies to vout/vs = D(percent of duty cycle on)

Boost Convertor:
When the switch is closed, the inductor charges off the voltage source, having an equal and opposite voltage across it relative to the source. When the inductor instead is connected to ground through the load, it will try to supply a voltage in the opposite direction relative to the source to keep current flowing (which will drop off)

change in i_on + change in i_off  = 0

<img width="245" alt="image" src="https://github.com/user-attachments/assets/136c635c-7749-4e35-b012-85408e9aa1eb" />
On
![image](https://github.com/user-attachments/assets/fdbaef48-b749-4754-887d-0a077352892a)
Off
![image](https://github.com/user-attachments/assets/ddd61e24-b408-410a-a8fa-67821dc832d6)
Simplified
<img width="160" alt="image" src="https://github.com/user-attachments/assets/832dabe3-f7cf-47e0-92e4-0213ed08d88b" />




Play.armor-alley.net
