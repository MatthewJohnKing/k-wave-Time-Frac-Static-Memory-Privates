# k-wave-Time-Frac-Static-Memory-Privates
If adjusting the MATLAB k-wave package these files need to replace ones within the Private repository.

These files have been updated to allow for the input medium.alpha_L such that this may be fed as an input for the computation of the Birk-Song Points and weights
Additionally they allow for medium.alpha_power and medium.alpha_coeff to be given as arrays that are the size of the space in this way both the time frational code kspaceFirstOrder[]DTF and the adjusted k-wave kspaceFirstOder[]Dalpha where []=1,2,3 can be run for an absorption that changes across the space.
