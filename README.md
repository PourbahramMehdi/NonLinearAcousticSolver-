# NonLinearAcousticSolver-
compile The WENO in src Folder .
compile the lacFoam and nlacFoam . 
you can change the fluid Acoustic properties in constant Folder for any other Fluid.
remember that the solver is very sensetive to corunt number. the best chois for courant number for 1d simulation is 0.3 < CFl < 0.8 and for 2d simulation is 0.2 < CFl < 0.5 . 
See the m4 File in polyMesh and Remember that, the scale of the Mesh Size in WavePropagation Simulation is atleast 0.025 of WaveLenght and smaller than that. 
