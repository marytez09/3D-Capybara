# 3D Capybara Process
#### This is a full documentation of the steps taken starting from the initial planning all the way to the final 3D capybara model. This model took a lot of trial and error, this documentation will go through all the hiccups encountered, what was learned during the process, and how it was tweaked towards the final result.

## The First Version 
#### When creating the design for this project, I wanted to go for a low poly plush aesthetic. Being my first time designing a model that will eventually house components, my initial thoughts were to keep the model as simple and low poly as possible. 
#### The hardware and model were both measured in millimeters, this was to ensure that the components are to fit inside of the model the hardware components perfectly encapsulated inside
#### The two blocks inside the model are based off of measurements from the actual hardware components that will be housed inside. I kept these blocks as reference throughout the modeling stage to make sure the components were still able to fit when thickening the walls. 

## Housing Hardware Components
#### For the first trial of this project, I thought it would be most effective to cut the model in half, and have shelf-like structures inside of the model that will then house both the RFID reader and raspberry pi. The shelves are to be printed attached to the model itself and connected together like lego pieces.

## Result of Ver. 1
#### This was my first trial of printing the model and internal shelves together. This was my first time using UltiMaker Cura and had learned that utilizing supports in the configuration stage is essential for keeping the filament from sagging. This model was printed without the use of supports which resulted in the lego pieces and model itself to lag down and not connect properly.
#### Due to the model not having any supports during the printing stage, it resulted in filament sag and a very noticeable hole down the middle of the model where they are to connect. I concluded that there needed to be a design change, as well as a change in the configuration of how the model is printed in UltiMaker Cura. 

## Version Two (Final)
####  With the second edition of this model, I decided to cut the model horizontally rather than vertically. This way, the design looks more seamless rather than a very noticeable line down the middle of the model's face. 
#### I learned that holes and divots tend to get smaller during the printing stage due to the filament. So in order to account for that, I made the holes a tad wider than the tabs connected to the head 
#### The head and body both have internal cavities within them to house the hardware components inside.

## Fixes Made in Cura
#### When configuring the model to be sliced in Ultimaker Cura, this time I made sure to add supports to the build plate and add a brim on the head for example just to add extra protection for the small tabs protruding at the bottom where it connects to the body.
#### The infill levels were kept at 0-5% to ensure that the internal cavities were not filled in

## The Final Capybara Print
#### This time the model was perfectly intact, no sag, the head and body fit together seamlessly. A small divot had to be carved out at the back of the head for the power cable to come out. 