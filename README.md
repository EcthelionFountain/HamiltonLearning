# HamiltonLearning
A repository to test how Hamiltonian and Lagrangian functions might be used to imrove performance of learning algorithms in certain areas.

Looking at for instance an instance of contrastive learning where the update function behaves as follows:

\[Lsup_contrast​=i∈B∑​∣P(i)∣−1​p∈P(i)∑​log∑a∈B∖{i}​exp(zi​⋅za​/τ)exp(zi​⋅zp​/τ)​\]
