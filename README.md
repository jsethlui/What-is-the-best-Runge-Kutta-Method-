# What-is-the-best-Runge-Kutta-Method-

The Runge Kutta (RK) Method is an iterative time-step method used to approximate ordinary differential equations (ODE's) around some fixed point. There also exists different weighted variations of the RK Method, which may be more suitable in some cases in order to obtain a greater approximation than that of the standard RK Method. Within my research, I explore two things: (1) the standard and 3/8 weighted RK Methods, and (2) two different ODE's (each with their own respective fixed point).

The goal is to approximate both of these ODE's with both the standard and 3/8 weighted RK Methods. The idea is to identify which of the following is true:

 a) the standard RK Method obtains a better approximation for both ODE's
 
 b) the 3/8 weighted RK Method obtains a better approximation for both ODE's
 
 c) the standard RK Method obtains a better approximation for one ODE than that of
    the 3/8 weighted RK Method
    
 d) the 3/8 weighted RK Method obtains a better approximation for one ODE than that of
    the standard RK Method

After having implemented both the standard and 3/8 weighted RK Methods (ultimately approximating all ODE's up to 0.5% accuracy), I concluded that (c) is true. I arrived at the fact that although the RK Method was relatively more accurate than that of the 3/8 weighted RK Method, the approximation difference is less than 1%. Unless accuracy up to some number of significant digits is necessary, both RK methods are sufficient enough in approximating any ODE around some timestep
