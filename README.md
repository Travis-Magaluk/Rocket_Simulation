# High School Rocket Simulation Program 

## About
The goal of this project was to make a workable rocket simulation to utilize in
my Physics of Rocketry class at Wasatch Academy. This simulation would allow 
the user to input various parameters about the rocket such as mass, mass of fuel,
thrust of rocket, consumption rate of fuel as well as some other parameters. 

The first part of the notebook deals with defining the mathematical and physics formulas 
needed to model the flight of a rocket. Care went into generating a function for
the air density as a function of altitude.

The second part of this notebook deals with the actual running of the simulation.
The program runs the formulas for a timestep defined by the user and for each 
parameter the value is stored in a list so that all the data can be graphed at
the end of the simulation. 

Simple plots are then generated to show the altitude as a function of time, 
velocity as a function of time, air resistance as a function of time as well as 
some others.

## Running this Notebook

To run, clone this repo and ensure that you have matplotlib, seaborn, and pandas installed.
It should run well with that. Please feel free to clone and use as wanted. 
Reach out to Travis Magaluk with any questions you have. 

## Future Work

This project is a pretty simple model of a rocket as a projectile going straight
up and down. I would love to add some features to make it a more robust simulation. 
Features include: 
1. Wind speed and its effect on the rocket.
3. Web based dashboard to allow users to toggle buttons and sliders to more interactively play with the parameters and see the results.

