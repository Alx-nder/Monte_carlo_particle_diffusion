Start with 10,000 particles all located at x=0 at time t=0. Implement the Monte Carlo 
“random walk” in one-dimensions to mimic the diffusion of these particles. Thus, after every “unit 
time step”, simply move each particle 0.1 units to the right (with probability 0.5) or 0.1 units to the 
left (with probability 0.5). 
Plot a histogram of the particle distribution after: (a) 50 time steps, and (b) 500 time steps


The failure probability is given by an exponential distribution. Thus, if "t" is the time to failure, the associated cumulative distribution function FT(t) is given as: FT(t) = 1 - exp(-2t).
You want to generate a string of 500 times to failure (e.g., t1, t2, …t500) for this random process based on a Monte Carlo scheme involving generation of random numbers ri. Obtain a formula linking the ith failure time ti to the ith random number ri.
