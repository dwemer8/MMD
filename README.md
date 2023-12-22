# Relative MMD
Repo with reporducing experiments from the paper: [A Test Of Relative Similarity for Model Selection in Generative Models](https://arxiv.org/pdf/1511.04581.pdf)
An example is provided under Example_Vae.py which trains two varational auto-encoders and then compares their samples to a holdout set using MMD.

The Relative MMD computations need to be exact to assure their validity. Thus matrix operations can be costly. Please make sure you have a properly configured numpy installation (linked to optimized blas libraries like openblas).
