# mpgmres

When solving linear systems of equations using standard Krylov subspace methods, the user is only allowed to choose a single preconditioner, although in many situations there may be a number of possibilities. Here we provide an extension of GMRES, multi-preconditioned GMRES (MPGMRES), which allows the use of more than one preconditioner. 

This code is based on the algorithm described in the manuscript: 
Greif, C., Rees, T., Szyld, D. B., [GMRES with multiple preconditioners](https://link.springer.com/article/10.1007/s40324-016-0088-7)
Also available as UBC technical report: UBC CS TR-2011-12, or Temple Math. report 11-12-23. 
