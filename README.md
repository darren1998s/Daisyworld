# Daisyworld
Daisyworld simulation project in python for NUS module SP3175

Daisyworld simulation is based on the 1983 paper by Lovelock et. al. More information can be found here https://en.wikipedia.org/wiki/Daisyworld

The code for both are mostly the same, except for exhibiting hysteresis. The "correct" hysteresis as seen in the 1983 paper is achieved by allowing for the planet to reach equilibrium first before changing luminosity. The "wrong" hysteresis was coded so that the luminosity shining on the planet changes at constant rate, regardless if the system has reached equilibrium.

Additional functionality i added was to simulate a predator which preys on all daisies with no preferance. Future work could be to simulate a more realistic predator (as the current one is immortal), and more importantly to account for spatial reproduction instead of spontaneous spatial spreading.
