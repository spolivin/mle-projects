# Repository for "Machine Learning Engineer" Specialization (Yandex Practicum)

This is a repository containing links to projects that have been completed during 6-month "ML Engineer" training program at Yandex Practicum. 

## Projects

### ***<ins>Price prediction service of Yandex Real Estate</ins>***

Taking the rol of an employee of Yandex Real Estate, a marketplace for renting and buying residential and commercial real estate, the task is to develop a model for assessing real estate prices that would produce adequate business metrics and deploy it to production.

| Project name | Description | Technology stack used |
| :---   | :--- | :---: |
| [**Building pipelines for data preparation and model training**](https://github.com/spolivin/mle-project-sprint-1-v001) | Creating an MVP of the algorithm based on machine learning for evaluating the value of real estate objects provided their characteristics | `airflow` `docker` `docker-compose`  `dvc` `scikit-learn` `boto3`|
| [**Improving baseline model**](https://github.com/spolivin/mle-project-sprint-2-v001) | Conducting a range of experiments in Mlflow aimed at improving the baseline model of prices prediction | `mlflow` `optuna` `autofeat` `mlxtend` `catboost` `scikit-learn` |
| [**Deploying ML application to production**](https://github.com/spolivin/mle-project-sprint-3-v001) | Building a FastAPI application for computing price predictions online with metrics monitoring system | `fastapi` `docker` `docker-compose`  `prometheus` `grafana` |
---

### ***<ins>Recommendation service of musical tracks from Yandex.Music</ins>***

Imagining ourselves as an employee of *Yandex Music*, a popular streaming service with a large catalog of over 70 million tracks, the objective is to make it easier for users to navigate such a vast music stream by creating an effective system of personalized recommendations.

Interaction with a music service should be convenient, simple and enjoyable. To do this, the user needs to be offered tracks or selections based on his tastes and preferences. Almost all popular services do this - few users will want to spend time searching for potentially interesting music, having tried a well-honed system of personal recommendations once.

| Project name | Description | Technology stack used |
| :---   | :--- | :---: |
| [**Recsys of musical tracks**](https://github.com/spolivin/mle-project-sprint-4-v001) | Building and deploying a system of personal recommendations of musical tracks | `fastapi` `boto3` `implicit` `catboost` `unittest`|
---

### ***<ins>Recommendation service of items in e-commerce (DIPLOMA PROJECT)</ins>***

It was online commerce that gave impetus to the task of recommendations. One of the first and most famous examples of a commercial recommendation system is Amazon.

The objective is to build a similar system of personalized recommendations of a wide variety of items in *e-commerce* industry that would target users' actions of adding items to cart.

| Project name | Description | Technology stack used |
| :---   | :--- | :---: |
| [**Recsys in e-commerce**](https://github.com/spolivin/mle-pr-final) | Building and deploying a system of personal recommendations of various goods with online metrics monitoring system | `fastapi` `boto3` `implicit` `catboost` `grafana` `prometheus` `airflow` `mlflow` `unittest`|
---
