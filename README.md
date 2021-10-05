# Convetional-PID-vs-Fuzzy-PID

The development of Proportional-Integral-Derivative (PID) and Self-Tuning Fuzzy PID
Controllers is to be applied to control a direct current (DC) motor. The nonlinearities and uncertainties
of the system are overcome by the simulation study of both controllers for the armature voltage-
controlled DC motor. To obtain fundamentally robust systems, the Fuzzy Logic Controller (FLC) is
designed according to 49 fuzzy rules for self-tuning every parameter of the Fuzzy PID controller. The
parameters of the proportional, integral and derivative (KP, KI , KD) gains of the PID controller are
tuned using fuzzy logic. The two inputs of the FLC are the motor speed error between the reference
and the actual speed, and the rate of speed change error. The output of the FLC is used as the parameter
of the PID controller to control the speed of the DC motor. The best performance of the Fuzzy PID is
compared with the conventional PID. To find the best Fuzzy PID performance, triangular, trapezoidal
and Gaussian membership functions defined in the FIS editor in MATLAB are assessed. The step
response, load disturbances and noise disturbances are the three simulated scenarios. To tune the
Fuzzy PID, trial and error is used by taking into consideration the Rise time, Settling time, Present
Overshoot and Integral Absolute error as performance parameters.
