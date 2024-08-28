## SPICE Simulation

1. Ensure there is **hspice** in the current environment.
2. Put the sub-circuit definition to `./Spice/Cirs/models/XXX.cir`.
3. Change the parameters (input transition time, load capacitance) in `gates/Circuits/generated/generate_hspice.py`.
4. run `python ./Spice/Cirs/main.py`.

*PS: The Dataset for Neural ODE model will be saved in ./Libs/Ours/Dataset*

## Neural ODE

This repo refers to https://github.com/EmilienDupont/augmented-neural-odes

* run `python ./NODE/main.py`
