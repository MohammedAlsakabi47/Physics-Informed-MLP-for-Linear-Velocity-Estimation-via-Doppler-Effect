# Physics Informed MLP for Linear Velocity Estimation via Doppler Effect

<p align="center">
  <img src="results_GIF.gif" alt="Description of GIF">
</p>

This repository presents a simulation of a Doppler effect caused by a two-blade propeller with a linear speed of 100m/s. The circular movement of the propeller causes the frequency change on an emitted waveform, with a carrier frequency of 3GHz, from a transmitter placed in the direction of the 'Receiver' in the GIF above. The instantaneous linear velocity of the propeller is then predicted with a three-layer MLP whose input is the noisy signal depicted on 'Wave at Receiver'.

## Dataset
Under `Dataset`, the input signal is found in `input_waves.mat`, the instantaneous spectrum is found in `forier_response.mat`, and the ground truth frequency is found in `frequency_progression.mat`.

## How to Run
To preprocess the dataset and train a physics-informed MLP, use `PINN_training.py` and `PINNs.m` for result visualization.
