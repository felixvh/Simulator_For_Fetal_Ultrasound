# Simulator for Fetal Ultrasound

## Key Investigators

- Felix von Haxthausen (University of Lübeck, Lübeck, Germany)
- David García Mato (Ebatinca S.L., Las Palmas de Gran Canaria, Spain)
- Tolga-Can Çallar (University of Lübeck, Lübeck, Germany)

## Medical Background
Forceps or a ventouse suction cup are used during an assisted birth, also referred to as an instrumental delivery. Forceps are slick metal objects that resemble big spoons or tongs. They are contoured to fit the baby's head and are placed around the infant's head. An obstetrician gently pulls at the handles to assist in delivering the baby during a contraction.

Before inserting the forcep tools, it is important to know the infant's position within the uterus. Ultrasound imaging is commonly used to obtain this information. This step will be the focus of the project.


## Project Description
In a previous project by Universidad Carlos III de Madrid, a [simulator](https://youtu.be/EEasWbH1jZI) was developed to train this procedures. In this project, we want to proceed and develop a simulation tool for the ultrasound imaging of the fetus. PLUS already offers a [tool](http://perk-software.cs.queensu.ca/plus/doc/nightly/user/DeviceUsSimulator.html) to generate fake ultrasound images based on 3D models. However, a general problem is that one needs to provide acoustic properties of each model for the ultrasound image generation. Therefore, we want to develop a tool that automatically provides the acoustic properties for each model.


## Objective
The objective is to create a tool that automatically assigns accoustic properties to each 3D model and generates the according config file for the PLUS ultrasound image generation server.


## Approach and Plan
1. Use the Total Segmentator to create the 3D models with assigned organ definition based on CT data.
2. Create and define a lookup table (LUT) that assigns the accoustic propeerties to each organ label. 
3. Develop a tool or module that generates the config file based on the models and the LUT.




