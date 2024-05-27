The project aims to creat models for estimating rotor performance a two different flight regimes: hovering and forward flight.
The created models are based on Blade Element momentum theory and they have been adapted so they can be used for small scale rotors as well as large scale rotors.
The models have been developed for linearized BEMT and full BEMT and an adaptation of linearized BEMT who also considers the dependency of lift and drag with reynolds number and it's non linear behaviour.
The hovering BEMT models are multiple. There are models for estimating rotor performance of a fixed geometry and other models for estimating the required pilot input (Collective pitch or rotational speed).
Those models are used for finding the optimal twist and chord distributions using MATLAB optimization toolbox.
For forward flight, it has been created a model for estimating rotor performance of rigid rotors (no pitch, no lead-lag or flapping hinges). An optimization function has been also created.
Additionally, the .zip files contain required .txt files for running the codes. Those .txt files have the aerodynamic properties of the airfoils used for the model and estimated with XFOIL.
