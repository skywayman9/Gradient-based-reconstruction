# Grad Based 🤣

Gradient-based reconstruction approach for simulations of compressible flows. The novel feature of the proposed algorithm is the efficient reconstruction via derivative sharing between the inviscid and viscous schemes: highly accurate explicit and implicit gradients are used for the solution reconstruction expressed in terms of derivatives. The higher- order accurate gradients of the flow variables (density, pressure and velocity components) are reused to compute the viscous fluxes for efficiency and significantly improve the solution and gradient quality, as demonstrated by several viscous-flow test cases. The viscous schemes are fourth-order accurate and care- fully designed with a high-frequency damping property, which has been identified as a critically important property for stable compressible-flow simulations with shock waves [Chamarthi et al., JCP, 2022]. Shocks and material discontinuities are captured using a monotonicity-preserving (MP) scheme, which is also im- proved by reusing the gradients. Several numerical results obtained for simulations of complex viscous flows are presented to demonstrate the accuracy and robustness of the proposed methodology.


https://arxiv.org/abs/2205.01034

Note: If doesn't work for your problem/test case don't blame me.


Note 2:  don't use it without understanding and curse me. If you don't like my work please use WENO or something else.  
Sainath
