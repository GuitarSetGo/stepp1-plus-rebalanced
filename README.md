# StepP1 Plus 2.0
Fork of [StepP1 Plus](https://github.com/rayden-61/stepp1-plus) by **rayden-61**. It updates the grade system to match the one currently used in **Pump It Up Phoenix 2**.

StepP1 Plus is a modified version of StepP1 1.0.3 (5-panel focused StepMania fork), originally developed by xMax (v. 1.0.0), with further binary modifications and theme decryption by SheepyChris and Team CrackItUp (1.0.1 to 1.0.3). Like StepP1 Plus, this repository only covers Lua modifications to the theme.

## What's changed in this fork
- **Phoenix 2 grade thresholds.** The P.Grade thresholds match Pump It Up Phoenix 2 (see the table below). SSS+ through AAA were already the same. AA+ through F changed:

  | Grade | StepP1 Plus 2.0.0 | Phoenix 2 (this fork) |
  |---|---|---|
  | AA+ | 925,000 | 940,000 |
  | AA | 900,000 | 920,000 |
  | A+ | 825,000 | 900,000 |
  | A | 750,000 | 800,000 |
  | B | 650,000 | 700,000 |
  | C | 550,000 | 600,000 |
  | D | 450,000 | 500,000 |
  | F | below 450,000 | below 500,000 |

- **Accurate evaluation grade.** The large grade on the evaluation screen is calculated directly from your judgments, so it always matches your P.Score with any judge.
- **Evaluation total score.** TOTAL SCORE on the evaluation screen shows your P.Score (0 to 1,000,000), calculated from your judgments.
- **Low pass color.** Passed scores below the A grade (800,000) are shown in green, following the new A threshold.

The P.Score formula, the judge timing windows (EJ, NJ, HJ, VJ, XJ, UJ) and the save format are unchanged. Save data from StepP1 Plus 2.0.0 still works, and existing records are shown with the new grades.

## Grades
Grades match the system currently used in Pump It Up Phoenix 2. Every grade has two versions:
- **Stage Pass**: you reached the score and your lifebar never dropped to 0.
- **Stage Break**: you reached the score, but your lifebar dropped to 0 at some point during the song.

| Grade | P.Score | Stage Pass | Stage Break |
|---|---|---|---|
| **SSS+** | 995,000 or more | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_SSS%2B%20%28doubleres%29.png" height="32" alt="SSS+"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_SSS%2B%20%28doubleres%29.png" height="32" alt="SSS+"> |
| **SSS** | 990,000 ~ 994,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_SSS%20%28doubleres%29.png" height="32" alt="SSS"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_SSS%20%28doubleres%29.png" height="32" alt="SSS"> |
| **SS+** | 985,000 ~ 989,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_SS%2B%20%28doubleres%29.png" height="32" alt="SS+"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_SS%2B%20%28doubleres%29.png" height="32" alt="SS+"> |
| **SS** | 980,000 ~ 984,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_SS%20%28doubleres%29.png" height="32" alt="SS"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_SS%20%28doubleres%29.png" height="32" alt="SS"> |
| **S+** | 975,000 ~ 979,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_S%2B%20%28doubleres%29.png" height="32" alt="S+"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_S%2B%20%28doubleres%29.png" height="32" alt="S+"> |
| **S** | 970,000 ~ 974,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_S%20%28doubleres%29.png" height="32" alt="S"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_S%20%28doubleres%29.png" height="32" alt="S"> |
| **AAA+** | 960,000 ~ 969,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_AAA%2B%20%28doubleres%29.png" height="32" alt="AAA+"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_AAA%2B%20%28doubleres%29.png" height="32" alt="AAA+"> |
| **AAA** | 950,000 ~ 959,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_AAA%20%28doubleres%29.png" height="32" alt="AAA"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_AAA%20%28doubleres%29.png" height="32" alt="AAA"> |
| **AA+** | 940,000 ~ 949,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_AA%2B%20%28doubleres%29.png" height="32" alt="AA+"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_AA%2B%20%28doubleres%29.png" height="32" alt="AA+"> |
| **AA** | 920,000 ~ 939,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_AA%20%28doubleres%29.png" height="32" alt="AA"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_AA%20%28doubleres%29.png" height="32" alt="AA"> |
| **A+** | 900,000 ~ 919,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_A%2B%20%28doubleres%29.png" height="32" alt="A+"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_A%2B%20%28doubleres%29.png" height="32" alt="A+"> |
| **A** | 800,000 ~ 899,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_A%20%28doubleres%29.png" height="32" alt="A"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_A%20%28doubleres%29.png" height="32" alt="A"> |
| **B** | 700,000 ~ 799,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_B%20%28doubleres%29.png" height="32" alt="B"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_B%20%28doubleres%29.png" height="32" alt="B"> |
| **C** | 600,000 ~ 699,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_C%20%28doubleres%29.png" height="32" alt="C"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_C%20%28doubleres%29.png" height="32" alt="C"> |
| **D** | 500,000 ~ 599,999 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_D%20%28doubleres%29.png" height="32" alt="D"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_D%20%28doubleres%29.png" height="32" alt="D"> |
| **F** | Below 500,000 | <img src="Themes/Fiesta%202/Graphics/RecordGrades/R_F%20%28doubleres%29.png" height="32" alt="F"> | <img src="Themes/Fiesta%202/Graphics/RecordGrades/B_F%20%28doubleres%29.png" height="32" alt="F"> |

P.Score goes from 0 to 1,000,000:

`P.Score = 995,000 × (Perfect + 0.6 × Great + 0.2 × Good + 0.1 × Bad) ÷ total notes + 5,000 × max combo ÷ total notes`

## Installation Instructions
- Clone the repository (click the green "Code" button, then choose "Download ZIP"). We recommend downloading and setting up Github Desktop or similar to easily sync updates.
- The stepp1-plus-main folder can be stored on your location of choice. It is a portable installation and will not write files to anywhere else.
- Do not install over a previous StepP1 installation. If you want to, move or copy your SongMovies, RandomMovies and Songs folders from other installations to the main stepp1-plus folder.
- To install songs, simfiles and background animations, follow the usual Stepmania standards. Read the provided Manual on https://github.com/rayden-61/stepp1-plus/blob/main/Documentation/Manual_EN.pdf (english) or https://github.com/rayden-61/stepp1-plus/blob/main/Documentation/Manual_EN.pdf (spanish)
- Do not use save files from other builds.
- We do not recommend migrating and old Save/PreferenceP1.ini file. Use the provided default PreferenceP1 and change your settings in-game (press Scroll Lock to access the in-game settings menu).
- We recommend this songpack, which has features tailored to this build: https://drive.google.com/drive/folders/1S1kLTRQoj3WptFkbg24__KqHJ1m13yhc (further updates for .ssc files can be acquired here: https://github.com/rayden-61/PIU-Simfiles)
- To change your in-game avatar, first create a profile and drop any square aspect ratio image file named "avatar.png" on your profile folder (example: stepp1-plus/save/localprofiles/00000001/avatar.png)

## Changes, Features and Known issues
- Changes in this fork: see [What's changed in this fork](#whats-changed-in-this-fork).
- StepP1 Plus changes, features and known issues: https://github.com/rayden-61/stepp1-plus/blob/main/CHANGELOG.txt

## Credits
- StepP1 Plus, the base of this fork, was created by rayden-61 (https://github.com/rayden-61/stepp1-plus). All StepP1 Plus features and changes are rayden-61's work.
- Phoenix 2 grade system in this fork: GuitarSetGo.
- StepP1 was created by xMax/StepF2 team (https://stepf2.blogspot.com/). Check out the in-game credits screen for original Stepmania and StepP1 credits, or visit the original StepP1 website.
- StepP1 1.0.1 to 1.0.3 were made by SheepyChris (https://github.com/sheepyChris/) with help from Team CrackItUp (check out 'Intro' folder for additional credits message).
- SofiaXY and The Resistance Simfiles (https://web.facebook.com/TheResistance2019/) for some cosmetic changes and noteskins in StepP1 Plus.
- Team Overcross for the Phoenix Co-op noteskin (edited by rayden-61 for use on non-coop charts).
