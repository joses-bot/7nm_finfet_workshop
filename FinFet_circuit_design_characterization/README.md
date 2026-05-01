### 7nm FINFET workshop
FinFet evolution

Going from planar 1nm to 28nm/32nm to eraliest version of FinFet in 2011 which is more like a 3 dimensional structure the source protudes upwards from the substrate and the gate straddles around it (see picture below), that architecture helps the switching happens in a faster way, if the initial fin structure and stack them forms the gate all around transistor. We can also decouple the periphery of the fin (electrical width) from the device area and pssibly get more device current than planar transistor. 

<img width="1207" height="658" alt="image" src="https://github.com/user-attachments/assets/1b8037a4-1601-47cb-a2b0-65cd65987ecc" />

Normal FET structures present known issues as hannel leakage (band to band tunneling because of highly doping regions in drain and source), one way to minimize the issue is using an oxide layer in between drain and source (fully depleted device) , one enhancement of this approach is to use a double gate which enhances the capacitandes (large cox and lowe cd) enhancing the switching time (sub-threshold swing).

At lower Vt we can get a lower leakage current (low power applications), even tuning the Vt we could reducew the dynamic power dissipation (equal drive current at a lower Vdd)

<img width="1127" height="637" alt="image" src="https://github.com/user-attachments/assets/04d280e8-819f-4766-a9b5-d6f7f999e553" />

CMOS Process evolution from 1um to sub-micron

<img width="1128" height="638" alt="image" src="https://github.com/user-attachments/assets/40652000-a279-4147-9aeb-09d8e72b00d8" />

<img width="1095" height="616" alt="image" src="https://github.com/user-attachments/assets/2077455e-b486-48eb-ac89-c7a6b063e360" />

Cell area scaling by changing the cell size

vertical dimension (cell height), horizontal dimension (cell width)

vertical dimension decrease -Fin depopulation used to decrease cell height and decrease the load capacitance decreasing the power consumption on the device

<img width="1101" height="617" alt="image" src="https://github.com/user-attachments/assets/17fe9e9d-ead8-48a9-8ce0-e3f148106e5d" />

Horizontal dimension decrease using diffcuison e.g from DDb (doubke diffusion break) to SDB (single diffusion break - using just one poly)
COFG (contact over field gate) to  COAG (contact over active region) 
Power/Ground rails embedded into the substrate  reduce the cell height

<img width="1100" height="607" alt="image" src="https://github.com/user-attachments/assets/1d7d2588-ee3b-49c3-85dd-e2de4d5ae1c3" />

Parasitics

Parasitics resistence

In planar -> the width of the contact is equal to the width of the channel keeping the extrinsic resistance low
In FinFet (Gate ll around transistors), the widht of the contact is reduced and the extrinsic resistance increases, challenge is to find new material to keep that ressitance to a low value, for instance using titatnium instead of nickel reduces the contact resistance and barrier height

<img width="1103" height="607" alt="image" src="https://github.com/user-attachments/assets/e63f6a70-43c3-42aa-ac4e-0b7467431bb4" />
<img width="1092" height="612" alt="image" src="https://github.com/user-attachments/assets/9027969d-9423-4c1d-9bec-3b98878b767f" />

Parasitic capacitance

Scaling down the gates of the transitors also scales doown the instrisic capacitance cox but increases the parasitic capacitance, this effect can be conter by introducing a lower K material in the gap between the gate and source achieving an overall ceff reduction

<img width="1098" height="612" alt="image" src="https://github.com/user-attachments/assets/bd5f9604-690a-4d3a-b7ec-9c07b69ce6f1" />

Devince scaling using layered materials

Using layered materials to try to sclae down the transiors to get lenfgt closer to 0.5nm. Using certain materials like MOS it is possible to deposit atomically precised layers of around 0.65nm accors the wafer, this material also increassses teh effective mass and reducing the bandgap

<img width="1093" height="607" alt="image" src="https://github.com/user-attachments/assets/76bfbcf5-cf9f-43f3-a83c-1c10a9b19d23" />


















