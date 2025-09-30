# H&M_recommendation_system

**H&M Real-Time Personalized Recommender**, in using with Hopsworks

## Project Scope

1. Architect a scalable and modular ML system using the Feature/Training/Inference (FTI) architecture.
3. Feature engineering on top of our H&M data for collaborative and content-based filtering techniques for recommenders.
2. Use the two-tower network to Create user and item embeddings in the same vector space.
3. Implement an H&M real-time personalized recommender using the 4-stage recommender design and a vector database.
4. Use MLOps best practices, such as a feature store and a model registry.
5. Deploy the online inference pipeline to Kubernetes using KServe.
6. Deploy the offline ML pipelines to GitHub Actions.
7. Implement a web interface using Streamlit.
8. Improve the H&M real-time personalized recommender using LLMs.

## 👔 Dataset

We will use the [H&M Personalized Fashion Recommendations](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations) dataset, available on Kaggle, open-source for academic research and education.

It is an e-commerce dataset that contains fashion articles from the H&M clothes brand.

It contains:
- 105k articles
- 137k customers
- 31 million transactions 

More on the dataset in the feature engineering pipeline [Notebook](notebooks/1_fp_computing_features.ipynb) and [article](https://decodingml.substack.com/p/feature-pipeline-for-tiktok-like).