# Lab 9 Yang

*I pledge my honor I have abided by the Stevens Honor System - Nicholas Scirocco*

## Install Yang & PlantUML

![image](https://github.com/user-attachments/assets/e890b9e6-eff8-40e5-b9a3-a1c3146b8a64)

## Copy the necessary YANG file to lab9 directory

![image](https://github.com/user-attachments/assets/acfe3256-025e-49d3-8810-5cf851fddcb2)

## Convert the YANG file into a YIN file using `pyang -f yin -o intrusiondetection.yin intrusiondetection.yang`

![image](https://github.com/user-attachments/assets/f6903e10-2c0e-4d93-9d2c-78e16444b8df)

## Convert the YANG file into a UML format using `pyang -f uml -o intrusiondetections.uml --uml-no=stereotypes,annotation,typedef intrusiondetection.yang`

![image](https://github.com/user-attachments/assets/accd7a91-98b7-4f7f-9813-dfce624c7a1d)

## Used PlantUML to create a diagram from this new .uml file using  `plantuml intrusiondetection.uml`

![image](https://github.com/user-attachments/assets/2108d6c9-91be-40a3-a8b7-b3b72407c163)

![image](https://github.com/user-attachments/assets/0ab9d6b7-2699-42f3-b52e-1059377d4c79)
