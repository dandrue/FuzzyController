# FuzzyController

In this repository you can find a raw Fuzzy controller applied to a steam turbine, the input variables are temperature and pressure and the output variable is a displacement corresponding to a fuel injector actuator.

The input and output membership functions were established previously at the problem declaration so the controller can define the functions and use three types of inference functions to the fuzzification and defuzzification of the variables.

For the inputs Temperature and pressure, there are 5 membership functions defined as trapezoidal functions for the left and right limits of the universe of discurse and for the middle membership functions a triangular profile is used.

The Fuzzy controller is estructured into two files, FuncionesPertenencia.py contains all the functions needed for the implementation, on ControlFuzzyTurbina.py an especific implementation for a turbine control is defined.


