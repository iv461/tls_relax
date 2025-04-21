# Solving the Truncated Least Squares problem (TLS) using linear  time convex relaxations paper

Based on https://github.com/cvpr-org/author-kit/


# TODO 
- Proof opf global convergence: Highlight that the proof of the convex relaxation' correctness suffices to prove global optimality 
of the overall solver 

# TODO experiments: 

- Scalability rotation-only solver 
- Overall runtime of the solver 
- Breakdown: How much does the computation of the convex relaxation, i.e. the weigthts requires compared to the minimiziation of the relaxation 
- Future work: How to combine both rotation and translation ? 

- Compare with STRIDE regarding rotation-only solving: Our solver is much faster ! 

- Conclusion: 