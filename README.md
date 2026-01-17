A high-fidelity numerical simulation developed to model the temperature distribution of a Formula SAE brake rotor during a high-speed deceleration event. 
This project utilizes a 3D Transient Heat Conduction model in Cylindrical Coordinates (r, theta, z) to predict thermal soaking and surface temperature gradients.
The distinguishing and notable feature of this code is the fact that it is able to take the rotational symmetry of the rotor into account which helps eliminate 
the overly conservative approach of enabling build up of heat/ excessive heat concentration in a specific spot similar ot a steady state solution with a linear static
solver in an FEA. Consequently,the heat distribution is much more uniform throughout the rotor.
