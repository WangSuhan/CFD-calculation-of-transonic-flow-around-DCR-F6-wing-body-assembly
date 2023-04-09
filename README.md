# CFD-calculation-of-transonic-flow-around-DLR-F6-wing-body-assembly
The DDLR-F6 wing-body assembly is a classical example of a transonic transport aircraft. It is a simulation of aerodynamic force and surface pressure distribution under the specified Mach and Reynolds numbers of the DDLR-F6 model.

Install
----
`Fluent` & `ICEM`, where `ICEM` is used in mesh generation, `Fluent` is used to calculate physical quantity in flow field.

Download https://www.ansys.com/

Turbulence model
-----
The `Spalart-Allmaras` model is specially proposed to solve the problem involving the flow around the curved surface boundary, especially for the flow around the wing, and has a good simulation effect for solving the turbulent boundary layer problem with the influence of curved wall and adverse pressure gradient.

To understand this model, refer to these two links:

https://zhuanlan.zhihu.com/p/466415033

https://turbmodels.larc.nasa.gov/Papers/RechAerosp_1994_SpalartAllmaras.pdf

DLR-F6
----
https://aiaa-dpw.larc.nasa.gov/Workshop2/DLR-F6-geom.html
