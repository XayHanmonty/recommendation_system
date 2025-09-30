# h&m_recommendation_system
A scalable, modular, and production-ready recommendation engine that can deliver real-time personalized suggestions for e-commerce users, combining both collaborative and content-based methods, and integrating modern MLOps practices.

## Architecture & Design Highlights

+ Adopted a Feature / Training / Inference (FTI) architectural paradigm to cleanly separate stages and responsibilities.

+ Created two-tower embedding models to project users and items into the same latent space, enabling efficient nearest-neighbor matching.

+ Incorporated a vector database (for example, for similarity searches) to power fast inference.

+ Built offline pipelines (for feature engineering, training, evaluation) and online inference pipelines, with robust deployment.

## Deployed:

+ Online inference on Kubernetes via KServe

+ Offline ML pipelines via GitHub Actions or CI/CD

+ Used MLOps best practices: feature store, model registry, versioning, monitoring.

## 👔 Dataset

We will use the [H&M Personalized Fashion Recommendations](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations) dataset, available on Kaggle, open-source for academic research and education.

It is an e-commerce dataset that contains fashion articles from the H&M clothes brand.

It contains:
- 105k articles
- 137k customers
- 31 million transactions 

More on the dataset in the feature engineering pipeline [Notebook](notebooks/1_fp_computing_features.ipynb).
