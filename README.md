# MoleculeSim-VRChat

This is a VR application that simulates the behavior of atoms given a XYZ data set on *VRChat* ! 
(Some non-standard practices are used given the limitations of U#)

 Animation of XYZ file on VRChat
 
 ![XYXp0](https://user-images.githubusercontent.com/8094167/234337101-c6c4f972-af58-4fb5-8656-60316293c7f6.gif)



## Features

* Each atom/molecule type has its own prefab allowing plenty of costomization
![7gfgm3](https://user-images.githubusercontent.com/8094167/228888337-70e9f02d-6512-468a-9d6c-fa20d1f3cab1.gif)

* The atoms exist inside a father GameObject so its possible to move the entire animation

 



# How to use 

1. When exporting, select the positions only, and make sure you are not exporting a single frame.
![image](https://user-images.githubusercontent.com/8094167/234338878-461c43fd-184c-4cca-895b-b6ca089bc8f4.png)

2. Create a prefab for each one of your elements. This gives the power to use any shape or material as long VRChat can handle it. 
![image](https://user-images.githubusercontent.com/8094167/234347240-7c70eae1-9fc2-4cd0-b964-f9e7617f22e2.png)
(eg transparet mat for Al) 

3. Create an empty object for each of the elements and the U# Script "UMoleculeType" to each one where you define the ammount and what prefab to use 
![image](https://user-images.githubusercontent.com/8094167/234368925-6d517ef3-17ec-4b9e-8e1f-6b3fe72094b0.png)

4. Create another Empty object wit the U# script XYZPloter and add the values
![image](https://user-images.githubusercontent.com/8094167/234369359-92439637-df98-4db2-abd1-6c907723bbcb.png)


