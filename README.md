# Repository for "Machine Learning Engineer" Specialization (Yandex Practicum)

This is a repository containing links to projects that have been completed during 6-month "ML Engineer" training program at Yandex Practicum:

1. [**Yandex Real Estate: price prediction service**](#price-prediction-service-of-yandex-real-estate)
2. [**Yandex Music RecSys**](#recommendation-service-of-musical-tracks-from-yandexmusic)
3. [**E-Commerce RecSys**](#recommendation-service-of-items-in-e-commerce-diploma-project)

## Completed projects

### ***<ins>Price prediction service of Yandex Real Estate</ins>***

*Taking the role of an employee of Yandex Real Estate service, a marketplace for renting and buying residential and commercial real estate, the task is to develop a model for evaluating real estate prices that would produce adequate business metrics and deploy it to production in cloud infrastructure.*

| Project name | Description | Technology stack | Python libraries |
| :---   | :--- | :--- | :--- | 
| [***Building pipelines for data preparation and model training***](https://github.com/spolivin/mle-project-sprint-1-v001) | Creating an MVP of the algorithm for evaluating the value of real estate objects provided their characteristics | *Yandex Cloud*, *Ubuntu*, *Apache Airflow*, *DVC*, *S3-storage*, *PostgreSQL*, *Docker*, *Jupyter* | `apache-airflow` `catboost` `dvc` `scikit-learn` `boto3` `sqlalchemy` |
| [***Improving baseline model***](https://github.com/spolivin/mle-project-sprint-2-v001) | Running *MLflow* experiments for improving the baseline model of prices prediction | *Yandex Cloud*, *Ubuntu*, *MLflow*, *Jupyter*, *S3-storage*, *PostgreSQL*| `mlflow` `psycopg2` `optuna` `autofeat` `mlxtend` `catboost` `scikit-learn` |
| [***Deploying ML application to production***](https://github.com/spolivin/mle-project-sprint-3-v001) | Building a FastAPI service for computing price predictions online with metrics monitoring system | *Yandex Cloud*, *Ubuntu*, *FAST API*, *Docker*, *Grafana*, *Prometheus* |  `fastapi` `uvicorn` `prometheus-fastapi-instrumentator` `autofeat` `requests` |
---

### ***<ins>Recommendation service of musical tracks from Yandex.Music</ins>***

*Imagining ourselves as an employee of Yandex Music, a popular streaming service with a large catalog of over 70 million tracks, the objective is to make it easier for users to navigate such a vast music stream by creating an effective system of personalized recommendations.*

*Interaction with a music service should be convenient, simple and enjoyable. To do this, the user needs to be offered tracks or selections based on his tastes and preferences. Almost all popular services do this - few users will want to spend time searching for potentially interesting music, having tried a well-honed system of personal recommendations once.*

| Project name | Description | Technology stack | Python libraries |
| :---   | :--- | :--- | :--- |
| [***RecSys of musical tracks***](https://github.com/spolivin/mle-project-sprint-4-v001) | Building and deploying a system of personal recommendations of musical tracks | *Yandex Cloud*, *Ubuntu*, *S3-storage*, *Jupyter*, *FAST API* |`fastapi` `uvicorn` `boto3` `implicit` `catboost` `unittest` `requests` `scikit-learn`|
---

### ***<ins>Recommendation service of items in e-commerce (DIPLOMA PROJECT)</ins>***

*It was online commerce that gave impetus to the problem of recommendations. One of the first and most famous examples of a commercial recommendation system is Amazon.*

*The objective is to build a similar system of personalized recommendations of a wide variety of items from e-commerce industry that would target users' actions of adding items to cart and deploy it in cloud infrastructure.*

| Project name | Description | Technology stack | Python libraries |
| :---   | :--- | :--- | :--- |
| [***RecSys in e-commerce***](https://github.com/spolivin/mle-pr-final) | Building and deploying a system of personal recommendations of various goods with online metrics monitoring system | *Yandex Cloud*, *Ubuntu*, *Apache Airflow*, *MLflow*, *S3-storage*, *PostgreSQL*, *Docker*, *Jupyter*, *Grafana*, *Prometheus*, *FAST API* |`fastapi` `uvicorn` `boto3` `psycopg2` `implicit` `catboost` `prometheus-fastapi-instrumentator` `apache-airflow` `mlflow` `unittest` `requests` `scikit-learn` `sqlalchemy` |
---
