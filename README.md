# Ising Model Simulation
 Ising model simulation using Glauber and Kawasaki dynamics

## Animations
The notebook produces animations of the emergent behaviors of the modeled system at the three given temperatures. An example animation for Glauber dynamics is displayed below.
![glauber_animation](https://github.com/juliammikk/Ising-Model-Simulation/assets/71704999/bae5c576-7fcc-4d24-acc5-cb7cf339a384)


## Visualisations
To visualize the system observable around the critical temperature (phase transition), 1000 measurements of energy and magnetisation (where applicable) over 10000 sweeps are collected for 20 temperatures. This data is stored in the glauber/kawasaki.csv files. Susceptibility and scaled specific heat (and errors) are then calculated for each temperature. All observables are then plotted against temperature. More precise values for plotted data can be found in the glauber/kawasaki_plot_data.csv files.

The observables that can be measured vary based on the dynamics used. Example plots for both dynamics are displayed below.


![glauber_plots](https://github.com/juliammikk/Ising-Model-Simulation/assets/71704999/e908802e-1150-4eeb-bc25-beb92ff6cf2b)

![kawasaki_plots](https://github.com/juliammikk/Ising-Model-Simulation/assets/71704999/e1524c98-6097-43b4-91b1-c1c2a7a5511c)
