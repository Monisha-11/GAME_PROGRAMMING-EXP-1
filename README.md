# EXP 01 - IMPLEMENTATION OF EFFECT IN MATERIALS
## AIM :
To Implement various effects in a material such as emissive, roughness, and metallic properties in Unreal Engine
## ALGORITHM :
1) Right-click in the content browser and choose material
2) Rename the material and double-click to open it
3) Right-click in the working space and search for constants.In constant choose constant vector 4
4) After this double click on the constant vector 4 and edit the color using the color picker
5) After adjusting the color click okay and save it.They join the output of the constant vector 4 to the base color
6) Create a single constant using step 3 and adjust its value of it using detail pannel by adjusting the value And you can apply this constant value to metallic, roughness, emissive color etc
7) For emissive you need to multiply the constant vector 4 and constant and apply it to emissive color For creating walls and gate you need to create a material and import a png image .
8) And use the png image as texture sample and connect the (rgb) of texture sample to the emmisive color & connect the alpha value of texture sample to the opacity

## OUTPUT :-
### BASIC-COLOR :-
![image](https://user-images.githubusercontent.com/93427240/229363186-efb3524f-4409-4005-a6a6-0af57cdc76c1.png)
### EMMISIVE :-
![image](https://user-images.githubusercontent.com/93427240/229363206-dd69288a-6169-4b16-a437-5c3ed935ad6e.png)
### METALLIC :-
![image](https://user-images.githubusercontent.com/93427240/229363467-ea291be8-c04d-4e4f-8d7b-5fb4daacebfd.png)
### ROUGHNESS :-
![image](https://user-images.githubusercontent.com/93427240/229363489-f9ab6a58-2ecb-4f5d-a665-ea117fe55e4c.png)


### RESULT:-
Thus, To Implementing various effects in material properties in Unreal Engine is implemented successfully.
