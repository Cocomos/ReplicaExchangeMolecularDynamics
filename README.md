# ReplicaExchangeMolecularDynamics
This program will take user input and perform Nose-Hoover REMD in shell.


Author: Trevor (Cocomos) Reutershan

Institution: California State University - Long Beach

Group: Tapavicza Quantum Chemistry Group


Some Info:
    This program will perform a Markov Chain Monte Carlo (MCMC) simulation based upon the user input.
    A Metropolis decision criteria is put in place to determine the switching of states.
    A Nose-Hoover thermostat is used to ensure a Boltzmann distribution of thermal states.
    Simulations are performed with free boundary conditions; that means in the gas-phase (i.e. no box).
    For further reading, see Wikipedia page for Parallel Tempering - https://en.wikipedia.org/wiki/Parallel_tempering.
    
   
Inputs:
    Temperatures in Kelvin |
    Number of REMD cylces |
    Number of MD steps per REMD cycles |
    Timestep for frog calculation (MD timestep) |
    Default settings - Temps = (300 K, 600 K, 900 K, & 1200 K); Cycles = 100; Steps = 200; Timestep = 40.
    Defaults are chosen based on what is known to work best for MC and MD simulations and what is most used.
    

Required packages:
    Turbomole Quantum Chemistry Package (any version) | 
    Turbomole MD Package
    
    
Notes:
    You must upload your intitial coordinate file to template/. and perform command define with Turbomole.
 
