# Ex2p / Ex2pO
Extra lens mount for 2-photon microscope
 - extend imaging capability
 - excitation of neurons by optogenetic stimulation with narrow-band laser


|Imaging flexibility|Optogenetical stimulation (under-filled setting)|
|---|---|
|<img width="960" alt="image" src="https://github.com/rysk-t/ex2p/blob/main/imgs/summary.png"> | <img width="320" alt="image" src="https://github.com/rysk-t/ex2p/blob/main/imgs/stimulation.png">|


# Hardwares
 - Construction parts list is listed in this [link](https://docs.google.com/spreadsheets/d/1m83LMHQkvfFSLj0JxW27Dom7R-7Ju0coneMxOGsIGas/edit?usp=sharing)
 - Analog discovery 2 (Digilent) is used to generate TTL signal for stimulation.

## Construction

## Ex2p
<img width="1101" alt="image" src="https://github.com/rysk-t/ex2p/blob/main/imgs/construction_ex2p.png">


## Ex2pO
<img width="1101" alt="image" src="https://github.com/rysk-t/ex2p/blob/main/imgs/construction.png">

 - Red-colored parts are the original parts of the Ex2p Nikon version.
 - Most of the parts were commercial parts from Thorlab.
 - FC/APC laser input ports were attached to the dichroic mount.
   - Various narrow-band and fast switchable LD laser sources are recommended (e.g., Omicron Luxx+, Coherent OBIS LX).
  
[3d-data files (.stl)  are available](https://github.com/rysk-t/ex2p/tree/main/Ex2pO_parts).

## Circuits configuration
Using Analog Discovery 2 with a custom-made breakout board, TTL for laser modulation was quickly configurable.
<img width="640" alt="image" src="https://github.com/rysk-t/ex2p/blob/main/imgs/AD2_interface_card.png">


[PCB files (.grb)  are available](https://github.com/rysk-t/ex2p/tree/main/Ex2pO_parts/breakoutboard).

breakout board designed by Kota OKADA and Ryosuke TAKEUCHI (Nagoya University)
