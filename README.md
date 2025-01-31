# Numerical-Integrator
A Xojo Software Project that performs Numerical Integration

This is a Xojo programming project.
https://www.xojo.com

In order to build the project, you must download Xojo from:
https://www.xojo.com/download/
You will also need the fpPlugin extended precision math plug-in from Einhugar Software:
https://einhugur.com/Downloads/Plugs/fpPlugin.zip

This application uses the Double Exponential numerical integration method to evaluate integrals numerically. It also performs additional related calculations and can iterate through sets of input values to save the user from manually entering individual input values. 

The Double Exponential Transform, also known as the Sinh-Tanh Transform, is very efficient at evaluating integrals where the integrand value is not cyclical. It may not be appropriate for cyclical functions such as (sin x)/x.

The mathematical operations are performed to an arbitrary precision which may be set by the user. The default precision is about 24 decimal digits, but can be increased or decreased by the user as necessary.

The extended precision math library that is used in this application was developed by Robert Delaney. In addition to the usual scientific functions, the library includes a number of specialized scientific functions.

For further details, refer to the main documentation
