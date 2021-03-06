# Embedded-project-302497

# Activity 1

## If the person sit in the car seat then the ButtonSensor activate and if the person turns ON the heater then LED Glows

|ON|OFF|
|:--:|:--:|
|![ON](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/ON.PNG)|![OFF](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/OFF.PNG)|

# Activity 2
## If both the above conditions are true, then input analog temperature readings are converted into digital values.
 ![ADC](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/ADC.PNG)
 
 # Activity 3
 ## Using PWM the digital values are shown in Oscilloscope.

|PWM_20%|PWM_40%|
|:--:|:--:|
|![PWM_20%_Dutycycle](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/PWM_20%25_Dutycycle.PNG)|![PWM_40%_Dutycycle](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/PWM_40%25_Dutycycle.PNG)
|PWM_70%|PWM_95%|
|   |   |
![PWM_70%_Dutycycle](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/PWM_70%25_Dutycycle.PNG)|![PWM_95%_Dutycycle](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/PWM_95%25_Dutycycle.PNG)

# Activity 4

## The digital temperature values can be visualized in serial monitor using USART protocol
![activity4ON](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/act%204.1.PNG)

## Functioning of Application

![activity4OFF](https://github.com/KollaNarasimha/Embedded-project-302497/blob/main/Simulation/act%204.gif)

#### CI and Code Quality

|Build|Cppcheck|Codacy|Code Inspector|
|:--:|:--:|:--:|:--:|
|[![Compile-Linux](https://github.com/KollaNarasimha/Embedded-project-302497/actions/workflows/compile.yml/badge.svg)](https://github.com/KollaNarasimha/Embedded-project-302497/actions/workflows/compile.yml)|[![Cppcheck](https://github.com/KollaNarasimha/Embedded-project-302497/actions/workflows/CodeQuality.yml/badge.svg)](https://github.com/KollaNarasimha/Embedded-project-302497/actions/workflows/CodeQuality.yml)|[![Codacy Badge](https://app.codacy.com/project/badge/Grade/409ce2c6d9a84b0a8e7f6c798a29150b)](https://www.codacy.com/gh/KollaNarasimha/Embedded-project-302497/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=KollaNarasimha/Embedded-project-302497&amp;utm_campaign=Badge_Grade)|  ![Code Grade](https://www.code-inspector.com/project/25934/status/svg) ![Code Score](https://www.code-inspector.com/project/25934/score/svg)
