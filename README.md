# Solution to MATLAB and Simulink Challenge project 162 Build a wireless communications link with software defined radio
A wireless communication link with Software Defined Radio (SDR) to transmit and receive signals without relying on traditional, fixed hardware components 

[Program link](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub)

[Project description link](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Build%20a%20wireless%20communications%20link%20with%20software%20defined%20radio)

# Project details

# Methodology
    1) A single scalar data (eg: sensor measurement) is taken as the source data and it is converted into bundles of binary bits.

    2) Design over-the-air transmission scheme, including modulation type and optionally, forward error correction.

    3) Model a channel in software, with all the impairments expected in the actual link.

    4) Build corresponding receiver. Receiver will have to accomplish carrier frequency synchronization, timing synchronization, and frame synchronization.

    5) Decode the source bits.

    6) When the link works as expected in software, remove the channel model and transmit and receive using SDR hardware.

    7) Continue from there to optimize your design for selected criteria such as throughput, or reliability, or security, or your own design criterion.


# How to run section
Please explain step by step how to run the code/model and include information about what toolboxes and other resources needed to run it.

# Demo
Add a video or animated gif/picture to showcase the code in operation.
  
# Reference
[1] Timothy M. Schmidl and Donald C. Cox, "Robust Frequency and Timing Synchronization for OFDM", IEEE Transactions on Communications, Vol. 45, No. 12, December 1997.
