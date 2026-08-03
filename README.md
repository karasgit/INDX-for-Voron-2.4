
<b style="color:red;"> After some feedback and own experience, I designed second version of rear mount for Bondtech INDX on Voron 2.4. I recommend to use 42 mm tool distance.   </b>

This repository contains 3d printable models of parts needed to use Bondtech INDX on Voron 2.4 with rear mount 
<img width="4080" height="1836" alt="IMG_20260803_234258" src="https://github.com/user-attachments/assets/8a91b6d4-b313-4d16-a9b8-3df1b1641492" />

<img width="4080" height="1836" alt="IMG_20260803_234519" src="https://github.com/user-attachments/assets/980e74be-42be-4a09-9d05-c4ffa9617a31" />

<img width="1140" height="552" alt="INDX" src="https://github.com/user-attachments/assets/77d17472-9550-45e3-83c1-d9d564713fba" />

This implementation replaces XY joints to be able to mount print head on the rear side of the extrusion.
<img width="819" height="698" alt="XY joint - Right" src="https://github.com/user-attachments/assets/0b298a4a-ef27-419c-a0d1-2acfd9e5d38f" />

Y end stop switch is moved to front right Z bearing block. The wires are guided to the endstop in the groove of the right gantry extrusion, secured with strips of PET bottle with a width of 11 mm.

<img width="414" height="415" alt="Z bearing block" src="https://github.com/user-attachments/assets/6d8b8426-9864-4a1b-a27d-ca305697ddf6" />
<img width="4080" height="1836" alt="IMG_20260803_231318" src="https://github.com/user-attachments/assets/87f6d5b6-b8b7-45d8-acbe-233401d2b6fb" />


X end stop is on Eddy Probe Mount on the X-carriage

<img width="793" height="817" alt="X-carriage" src="https://github.com/user-attachments/assets/4e46090e-1af2-4230-b36e-0facc528ade6" />


Another alternative is here https://www.printables.com/model/1644881-indx-9mm10mm-belt-mount-for-vorons-standard-belt-p


Tool holder is mounted on original back extrusion (2020). It is adjustable in Z axis +-1.5 mm. The adjust mechanism is designed to eliminate the need for springs(comapre to the version 1). Instead, it uses the pressure of the wrench and gravity to adjust. When adjusting the tools downwards, lightly press the adjustment screw.
It is possible to mount max. 8 tools with 36 mm distance (without Bondtech part cooling) or 7 tools with 41 mm distance (with Bondtech part cooling). Bondtech recommend distance 41 mm but surrounding tools are touching part cooling ducts during tool change. For 7 tools it is necessary to have 41 mm distance to fit brtween A/B drives. I recommend to use 4 or 6 tools with 42 mm distance.
<img width="1254" height="788" alt="řez" src="https://github.com/user-attachments/assets/18397f6e-555a-4ad1-80b9-b33b0a358dfe" />

<img width="726" height="346" alt="6x42 mm" src="https://github.com/user-attachments/assets/2cdc21ae-147f-476a-b75c-c9ddb2aa0722" />



It is necessary to replace front idlers, because X extrusion have to fit between it. I use https://github.com/selliott79/Other-V2-Idlers .
In my repo are front idlers modified to be able to use original screws.

Wires are managed with original X axis cable chain between bottoms rack and back gantry extrusion (form bottom side). Use Z_Chain_mount to mount chain to buttom extrusion. On back gantry extrusion is chain crewed dirctly to extrusion from buttom side. 

Printable area is reduced by 18 mm on Y (332 mm on 350 mm printer). X is reduced approx 2-3 mm (347 mm), Z without tophead is 300 mm.


