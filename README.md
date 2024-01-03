 Fuse

In general, the fuse should be rated at least 125% of the motor's full-load current (FLA)
xceeding 225% of the FLA is generally not recommended

Fast-acting fuses: These blow quickly in response to high currents, offering excellent protection against short circuits.
However, they *might also trip during temporary inrush currents during motor startup, leading to *nuisance tripping.

"*Time-delay fuses: These tolerate short-term overloads better than fast-acting fuses, making them suitable for motors and other applications with expected current surges. They offer a better balance between protection and operational continuity.

Dual-element fuses: These combine a fast-acting and a time-delay element, providing rapid short-circuit protection while allowing for temporary overloads. They're ideal for circuits with sensitive components and high inrush currents.

13 Amp is max current given by motor driver
Minimum recommended fuse size: 1.25 * 13 Amps ≈ 16.25Amps
Maximum recommended fuse size: 2.25 * 13 Amps ≈ 29.25Amps

![Screenshot 2024-01-02 214046](https://github.com/Ravikrishnan05/MARS-lessons/assets/134152503/fd6927b9-2cc8-48e6-99f6-900ec2af3c59)
![Screenshot 2024-01-02 213828](https://github.com/Ravikrishnan05/MARS-lessons/assets/134152503/fefc6b70-caef-4fa9-911f-3e1794f88413)
![Screenshot 2024-01-02 214017](https://github.com/Ravikrishnan05/MARS-lessons/assets/134152503/b2e7c4e2-fbb1-4da3-bc2f-b42b4df96d73)

based on the current we are giving to orin we need to choose fuse in such a way that is should be between 1.25 -2.25 times the max current

Circuit boards with delicate components like microcontrollers, processors, and memory chips: Fast-acting fuses quickly interrupt excessive current before it can damage these sensitive parts

We must connect fuses near the battery connection of main battery for over rover.
