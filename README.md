# Function Genrator
LabVIEW Function Generator
Overview
This project involves the creation of a function generator using LabVIEW. The system generates various waveforms, adds customizable noise, and implements noise removal techniques. It serves as a platform for simulating real-world signal conditions and testing noise reduction methods.

Features
Waveform Generation: Produces sine, square, and triangle waveforms with adjustable frequency and amplitude.
Noise Addition: Introduces noise to the waveform with customizable type and amplitude. Supported noise types include:
Uniform White noise
Periodic Random noise
Gaussian noise
Gamma noise
Poisson noise
Binomial noise
Bernoulli noise

Noise Removal: Implements filtering techniques to clean noisy signals and restore the original waveform.
Graphical Displays: Visualizes clean, noisy, and filtered signals for analysis.
System Design
The system is designed using LabVIEW's graphical programming environment and consists of the following modules:
Waveform Generator: Creates clean signals based on user inputs.
Noise Generator: Produces noise waveforms with adjustable parameters.
Signal Adder: Combines the clean signal and noise to generate a noisy signal.
Noise Removal Block: Applies filtering to remove noise and restore the original signal.
Graphical Displays: Provides visual representations of the signals at each stage.

Block Diagram
Block Diagram

Methodology
Waveform Selection: Choose the waveform type (e.g., triangle) and set its frequency and amplitude.
Noise Addition: Select the noise type and amplitude to add to the clean waveform.
Noise Removal: Apply filtering to the noisy signal to retrieve the original waveform.

Results
The waveform generator successfully produces clean signals of various shapes with adjustable parameters.
Noise addition accurately reflects the specified noise characteristics.
