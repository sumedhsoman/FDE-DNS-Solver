A FDE solver for DNS of turbulent flows, based on Moin and Rai's paper. The interpolation is still linear, the authors had used cubic interpolation. Some part of the code is based on Seibold's MATLAB solver as well. Current Boundary conditions are for lid driven cavity flow. Execution speed isn't exactly a strength, and no post processing is currently present.

References-
[1] Rai, Man Mohan, and Parviz Moin. "Direct simulations of turbulent flow using finite-difference schemes." Journal of computational physics 96, no. 1 (1991): 15-53.\
[2] Kim, John, and Parviz Moin. "Application of a fractional-step method to incompressible Navier-Stokes equations." Journal of computational physics 59, no. 2 (1985): 308-323.\
[3] Seibold, Benjamin. "A compact and fast Matlab code solving the incompressible Navier-Stokes equations on rectangular domains mit18086 navierstokes. m." Massachusetts Institute of Technology (2008).
