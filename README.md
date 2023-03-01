# rabbitsGame 

This project shows **how to implement a P5js sketch on the Gosai operating system** with the exemple of the dvic's [**interactive pool**](https://dvic.devinci.fr/projects/educationnal-billard). 
The sketch will become a new **project application** using the different **drivers and devices** it needs to be **interactive** with the Augmented Reality (AR) interactive pool platform.
The principle of the project is to make some **rabbits** that are going though the pool table and create an **interaction** so that the rabbit can be **killed** with a **billiard ball**.

![diagramExpetech](https://user-images.githubusercontent.com/116834424/222148372-ba872ca2-a72b-4a02-88cc-ea04149ae10b.JPG)

## Application Template

For each application there are 3 different files :
- **Processing.py** python code that **itnitialize wich driver** the app is going to need to display on the pool table. 
- **The display** file is the main sketch of your project. These are **the animations displayed** on the pool table. It is using the javascript language.
- **The components** folder are all the **class files** that the display file need, also in javascript. 

In the Rabbits game there is the processing file and 4 different classes : rabbit , particles, firework, and bubble.

- The **Rabbits class** will **manage** the **display** and the **movement** of the rabbits.
- The **Particles class** will generate **colored dots** with a **velocity** and **display** that gradually **decrease and disappear** around the dead rabbits.
- The **Fireworks class** uses the particles class and **generates** a list of **100 particles** around the dead rabbit to **create an eplosion**.
- The **Ball class** allows to generate the **list of balls** present on the table.
