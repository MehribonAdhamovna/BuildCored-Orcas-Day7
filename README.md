# BuildCored-Orcas-Day7
KeyboardOscilloscope — BUILDCORED ORCAS Day 07

What it does. This project turns my computer keyboard into a musical instrument where each key plays a specific sine wave frequency. It also shows a live "oscilloscope" that visualizes how the different sound waves combine into one single signal.

Hardware concept. The core concept is superposition, which is how speakers and analog synths work by adding multiple sound waves together. When I press several keys, the software adds their math together to create a single complex wave that my computer's DAC (Digital-to-Analog Converter) turns into sound.

What I would do differently. I’d like to add "ADSR envelopes" so the notes fade out smoothly instead of cutting off instantly when I release a key. I also think it would be cool to add different types of waves, like square or triangle waves, to see how their shapes change the texture of the sound.

Screenshot. https://drive.google.com/file/d/12hj_04QWu9979AYOfEjx4-XD16IaXteY/view?usp=sharing

Run it. python day07_starter.py
