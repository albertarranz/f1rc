# F1RC Project [doc in progress ...]

F1RC, in a nutshell, is a multidisciplinary light control, telemetry and lap timing project for RC cars and likely applicable to other types of vehicles. However, my initial focus has been on RC cars, both electric and combustion-powered.

<img src="https://github.com/user-attachments/assets/94a7a34e-0699-467b-8cd6-50ee7fda5ec9" height="400"> <img src="https://github.com/user-attachments/assets/fec9602d-9cf7-4180-b186-39e30df4fe0a" height="300"/> <img src="https://github.com/user-attachments/assets/a938900c-1de0-493d-9562-eb74103a5412" height="400"/>



# History

A few years ago, in mid-2023, I purchased a [XIAO ESP32 C3](https://wiki.seeedstudio.com/XIAO_ESP32C3_Getting_Started/) microcontroller and I was amazed by its size and power. I started some basic projects but nothing particularly remarkable. Around that time, I was testing an F1 RC car on my local track—the 3Racing FGX and FGX 2018, a terrible car by the way—and I had the idea of implementing brake lights that mimicked the behavior of a real F1, since this was something not very common in the RC car market. I finished it in a weekend. It monitored the throttle and brake channels and would flash the lights at varying frequencies accordingly. 

The project consisted of three LED brake lights mounted on the rear wing of a Formula 1 RC car. One large LED at the bottom center of the wing and two smaller LEDs at the upper corners — mimicking a real Formula 1 car and its behavior: flashing at high frequency when braking and at low frequency when accelerating. Not perfectly accurate to real life, but good enough for an RC model.
The microcontroller continuously read the throttle servo value and, based on a threshold, flashed the lights at one frequency or the other. Simple but effective — one pin to read the throttle servo's PWM signal and another pin for the brake light output.

<img height="400" alt="2026-05-17 12_32_05-NVIDIA GeForce Overlay DT" src="https://github.com/user-attachments/assets/dccd8e00-81ff-4e56-a7ed-8e41f29ef52c" />


Everything worked perfectly and quickly. But soon I thought: "what a waste of resources, using a microcontroller just to control some brake lights…" And I started to imagine… and ended up building what I have today: a lighting, telemetry, and lap timing system for RC cars, all controlled through an Android app that has evolved and will keep evolving over time — and completely free.

Here I offer everything you need to build it yourself: buying the components and ordering the PCB to be manufactured, installing the firwmare and the app. But in the very near future, I will also offer semi-assembled and fully assembled options for those who don't want to build anything from scratch.

https://youtube.com/shorts/2Qd2mVsXTfQ

More info https://github.com/albertarranz/f1rc/wiki
