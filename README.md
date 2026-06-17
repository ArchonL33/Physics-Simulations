## ** Author's Note **
##----------------------------------------------------------------------------------------------------------------------------------------##
I come from a background in physics and mathematics. The focus of this project is on the accuracy of the physics and the clarity of the numerical methods rather than on writing highly optimized or production‑grade code.
Because of that, parts of the code may be: more verbose than necessary, not fully optimized, written with clarity in mind rather than efficiency.
This project represents my learning process as I explore numerical simulation and Python programming. I'm actively improving my software engineering/programming skills. 
Suggestions for improvement are always welcome. Thank you.
##----------------------------------------------------------------------------------------------------------------------------------------##

Projectile Motion with Quadratic Drag Simulation

This project simulates projectile motion with and without quadratic air resistance using Python and Jupyter Notebook.

## Features
- Adjustable initial velocity, angle, mass, drag constant, and initial height
- Realistic quadratic drag model
- Side-by-side comparison of trajectories (drag vs no drag)
- Interactive sliders using ipywidgets
- Clean matplotlib visualizations

## Files
- `ProjectileMotion.ipynb` — main notebook with simulation and plots.

## Physics Model

I derived the equations for projectile motion (kinematics) and other useful formulas to aid in this project.
Such examples used are:

The drag force is modeled as:

F_drag = -c * v^2 * v_hat

where  
- c = ½ ρ C_d A  
- v is speed  
- v_hat is the unit velocity vector

## Requirements
- Python 3
- NumPy
- Matplotlib
- ipywidgets

## Author
Zachary Lee
