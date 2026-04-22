# Rocket Engine for Physics Class

Objective: make a small working fluid bi-propellant rocket engine, using gaseous Oxygen and E85.

### Plan:
- Diagram
  <img width="589" height="801" alt="Screenshot 2026-04-21 235128" src="https://github.com/user-attachments/assets/6300984f-b58c-49a5-9c94-ef6de247a05e" />
- Electronics
  - Thermocouples: https://a.co/d/0b2APcB7
- What will be measured (Coldfire test):
  - Injector Pressure
- What will be measured (Hotfire test):
  - Chamber Pressure
  - Chamber Temperature
  - Thrust
  - Exhaust Velocity
  - Exhaust Temperature
 
### Math:
1. Maximum Allowable Pressure (Barlow’s Formula, P = (2*S*t)/D)
   - S (Yield Strength of Copper (9,000 psi)
   - T (Thickness of 0.0625 inch)
   - D (Diameter of 1 inch)
   - P = 1,125 psi
   - Safety factor (4x)
   - Max Pressure of 280 psi
2. Optimal Throat Diameter (Contraction Ratio of 2-4, CR = Ac/At)
   - Ac (Cross-sectional area of the chamber of 3.14 inches)
   - At (Cross-sectional area of nozzle throat)
   - Skip (copper nozzle is 0.5 inches, so not changing for now)

### Resources:
- https://youtu.be/VI8gdmjEwKc?si=jSt5G9J_5a8ICkqq
- https://youtu.be/x05B5nusaLw?si=24WsIwJmIG0IdciG
- https://youtu.be/XC1Tc5egH74?si=-gywtH47ZLRdF7Ur
- https://youtube.com/playlist?list=PLbX9WP2S_MYMwtzhWO-6o9Fq24Vk7T-Za&si=qLqg0jDMqB4pCFxk
- https://youtu.be/kAau2e5sILg?si=o4UfmNlpXlLmAiYO
- https://youtube.com/playlist?list=PLyJ-pcKWFQSdeUy0XFVZllpI9fBT3yCsE&si=32jorvktfL7fC7Oy
- https://youtu.be/JU6Ymku1cNw?si=RsupSIDDjV6EkAkS
- https://youtu.be/Zi2zTaPVzTM?si=mO94Rb_VUMe_6xsD
- https://youtu.be/Ud8fyPsoGlY?si=VvPf-5cIqqnMvJa6
- https://youtu.be/gP48Urfv2NQ?si=lDzyiD2Om94iib8m

- https://www.grc.nasa.gov/www/k-12/airplane/rktthsum.html

- https://randomnerdtutorials.com/arduino-k-type-thermocouple-max6675/
- https://esphome.io/components/sensor/max6675/
