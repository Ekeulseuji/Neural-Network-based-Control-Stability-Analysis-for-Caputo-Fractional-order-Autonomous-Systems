# Neural-Network-based-Control-Stability-Analysis-for-Caputo-Fractional-order-Autonomous-Systems
A novel approach for the design of appropriate control policies and valid neural Lyapunov functions for Caputo-type nonlinear fractional-order systems.

**Codes will soon be uploaded (depending on the tImE of MaNUsCripT aCcEpTAnCe)**

A three-layer neural network model with initial neural control feedback gain matrix set as the lqr gain matrix is built to stabilize a Caputo-type fractional-order system. A neural Lyapunov function will also be computed out for validating that the neural controller gain matrix could indeed control the nonlinear system until being asymptotically stable. The model parameters are updated through gradient descent based on the gradient of the loss function, and a Satisfiability Modulo Theory solver was used to generate counterexamples until the falsification conditions are satisfied for all x within a pre-specified B(η).

<div align=center>
<img src="https://github.com/user-attachments/assets/3fc5dc8e-2938-4cc9-bd24-f9567412525e" width="650" height="782" />
</div>


Results are as follows:


<div align=center>
<img src="https://github.com/user-attachments/assets/5709129e-b12d-445a-9234-153f1e1a5475" width="650" height="682" />
</div>
