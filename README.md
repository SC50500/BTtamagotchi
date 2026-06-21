# ARIRANG
<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/873e574f-cb1e-4d55-a048-1f06cdc37708" />

# Description
A 4-button tamagotchi remix based on global pop band BTS's new album "ARIRANG" featuring a speaker in place of a buzzer and unique tamagotchi dancing emoticons. Instead of indicating changes in the pet's state using buzzes, the ARIRANG tamagotchi uses a sequence of notes from the speaker to play a familiar tune. What makes this tamagotchi design unique is that it uses easily accessible parts and produces sound from the speaker without storage of music on a micro-SD card or similar component. Music is played through using the tone() function in the Arduino IDE. 

# Purpose
The basic eat, sleep, and play functions of your average tamagotchi are still present in this design, allowing users to interact with their tamagotchi pet at any time of day. An additional music feature has been added to the tamagotchi, as coded for by the fourth button on the PCB. This button plays one of three tunes, extrapolated from popular BTS songs and inspired by piano or music box covers arranged by other composers and artists (View credits for more information). 

For more information about what a tamagotchi is and how to use it, check out [this guide](https://tamagotchi.fandom.com/wiki/Main_Page) on what a tamagotchi is. 

# Features
* **0.96" OLED Display (128 x 64):** Black and white, yes, but perfect for Van, a character that is monochromatic ;3
* **INGHAi Speaker:** A small, but powerful speaker with a simple adapter that allows for music from Arduino IDE or bluetooth to be played. 
* **Four tactile switches:** The first three are for the basic eat, sleep, and play functions of the tamagotchi, but the fourth is a "music" button that activates one of three tunes that any BTS fan would recognize, paired with a pet dancing animation.
* **Unique themed pet and animations:** Your tamagotchi pet goes by the name Van! Van is a character from the LINE x BTS collaboration, which produced a line of BTS mascots called BT21. In this collaboration, Van represents the ARMY, BTS's fandom, instead of a specific member. I felt that because of this, Van was the most suitable mascot for this project. 

# How does this work? 
Each of the four different buttons are mapped to one of four screens: eat, play, sleep, and dance/music.

* Left-up button: For when Van is feeling a bit peckish
* Left-down button: For when Van is bored
* Right-up button: For when Van needs some rest
* Right-down button: For when Van is ready to party :3

When these buttons are pressed, a quick transition music is played to indicate a change in Van's status. If any of Van's status bars (Hunger, Happiness, and Energy) fall below 50, Van's expression will change into a sad expression. 

After each animation runs its course, the screen returns back to the main screen while the pet awaits further instruction.

# Design
Below are all of the screenshots of my design (plus screenshots by layer and an exploded view :3)
<img width="1461" height="767" alt="image" src="https://github.com/user-attachments/assets/15af5c36-9075-4b8b-995d-3622fcfe4275" />
<img width="527" height="771" alt="image" src="https://github.com/user-attachments/assets/c6378291-3641-455e-a845-05a9b81985c0" />
<img width="527" height="746" alt="image" src="https://github.com/user-attachments/assets/b21459cd-dea7-4ad7-8c74-41ad06ddf0b7" />
<img width="510" height="737" alt="image" src="https://github.com/user-attachments/assets/d9a6d5a7-3215-4be9-9e8d-6b625b18cbeb" />
<img width="672" height="548" alt="image" src="https://github.com/user-attachments/assets/e2616e68-d332-40b7-a000-57e28c6275a2" />
<img width="557" height="712" alt="image" src="https://github.com/user-attachments/assets/868c6fbe-dd5a-4285-adce-981610bb9316" />
<img width="658" height="596" alt="image" src="https://github.com/user-attachments/assets/078e827a-0102-4d75-bfc4-a34b57cf2c00" />
<img width="677" height="452" alt="image" src="https://github.com/user-attachments/assets/ef4b50dd-2e93-423e-a367-4ab49d9c8e67" />
<img width="885" height="621" alt="image" src="https://github.com/user-attachments/assets/b7c1bb36-1311-443d-bd70-36c0b3df2845" />

# Inspiration
As someone who has been a fan of BTS since they were 7 years old, I've dreamed of completing a project that allowed me to take creative liberty in designing a product that reflected both my interest in KPOP and engineering.
The theme of the tamagotchi was centered around "ARIRANG", BTS's newest album that was recently released this year. After being inactive as a band for over 3 years, this was the long-awaited "comeback" album that myself and other long-time fans were excited to listen to.
More importantly, this album holds a different meaning to the fandom, ARMY, and the group; It is meant to represent a return to the roots from which BTS first came.
So, in honor of their return from their hiatus, I decided to dedicate my first hardware project to them -- A band whose songs motivated me throughout all of the obstacles I overcame to ship this project. 

# Credits & Acknowledgements

Credits to BTS's new "ARIRANG" album cover and the BTS ARMY Logo for the hardware design inspiration. 

# Libraries & Extensions Used

* ESPRESSIF Arduino IDE Extension
* Adafruit SSD1306
* Adafruit GFX Library

# Music Attribution & Copyright Disclaimer
The audio files included in this repository are piano covers intended for non-commercial entertainment purposes only.

*    *Original Composition:* "Crystal Snow", "Spring Day", and "Butterfly", intitially performed by BTS, copyrighted by Big Hit Music / HYBE. 
*    *Arrangements:* Based on the piano arrangements by [SMYANG PIANO](https://www.youtube.com/c/smyangpiano) (used with pending permission.
*    *Performances:* Recorded and arranged by Sophia Chan.

*Disclaimer: Although the music used in the tamagotchi are inspired by the music box and piano arrangements created by SMYANG PIANO as a cover for BTS's music, the actual arrangements slightly differ in composition.*
