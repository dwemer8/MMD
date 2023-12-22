# The project made for the "Principles of applied statistics" course at Skoltech
Repo with reporducing experiments from the paper: [A Test Of Relative Similarity for Model Selection in Generative Models](https://arxiv.org/pdf/1511.04581.pdf)

An example is provided under Example_Vae.py which trains two varational auto-encoders and then compares their samples to a holdout set using MMD.

The Relative MMD computations need to be exact to assure their validity. Thus matrix operations can be costly. Please make sure you have a properly configured numpy installation (linked to optimized blas libraries like openblas).

### Team members:
- Nikolay Kotoyants
- Dmitriy Kornilov
- Danil Gusak
# Results

We have obtained following results for the corresponding data:
1) Experimental validation of the Relative MMD Test [synthetic_dataset_experiments.ipynb](synthetic_dataset_experiments.ipynb)
2) VARIATIONAL AUTO-ENCODER: changing the dataset size experiments [VAE_data_experiments.ipynb](VAE_data_experiments.ipynb)
3) VARIATIONAL AUTO-ENCODER: changing the architecture experiments [VAE_architecture_experiments.ipynb](VAE_architecture_experiments.ipynb)
