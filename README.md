# OSCAR code for (QP^5)_d with d = 33 and 71

This repository contains the OSCAR implementation of the algorithm used in the paper

 D.V. Phuc, *A-generators of H^*(V^{\oplus 5}) = Z/2[u_1,\dots,u_5] and the cohomological transfer*, 2025.

The file `Code_OSCAR_33_and_71` implements the ultra-sparse bitpacked algorithm described in Section 3 and Appendix 4 of the paper.  
It computes:

- a basis of admissible monomials for \((QP_5)_d\) with \(d = 33\) and \(d = 71\), and  
- the corresponding \(GL_5\)-invariants,

and was used to verify all numerical results in Section 3.

## Requirements

- OSCAR (see <https://oscar.computeralgebra.de>)  
- A working Julia installation compatible with OSCAR

## Usage

1. Start an OSCAR / Julia session.
2. Load the script:
   ```julia
   include("Code_OSCAR_33_and_71")
