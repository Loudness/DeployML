# Deployment pipeline of Machine Learning Models

---


A deployment pipeline for machine learning models using model versioning, CI/CD and serving it through a Flask JSON API.

First version include a simple regression based ML model based on housing price data that is retrieved from Kaggle. 

The created models are deployed on Gemfury (with versions and requirements) to be able to track incremental (or decremental) changes in the trained model.

## Stack used:

* **AWS ECR** (Perhaps replace with Kubernetes, time will tell) 
* **Docker** Packaging for deployment
* **Github** Code Repository
* **Pyhon Notebooks** For experimentation before conversion to pipeline
* **GemFury** Cloud Package repository
* **CircleCI** For Continuous Integration
* **Flask**  JSON API
* **Kaggle** Training data

**+ Various ML tools.**



## Steps for the project are:

1. Data Analysis
2. Feature Engineering
3. Feature Selection
4. Building The Machine learning models
5. Configuration for Docker
6. Setup and Configuration of Circle CI (CD)
7. Convert iPython notebooks to a deployable and updatable pipeline
8. Connect JSON API to model for production use. 

Rinse and repeat only steps 2,3 and 4 for future versions of ML models.

### Future steps
* **Dashboard** using Dash and Plotly 
* **Deep learning model** On a more powerful AWS machine and lots of time
* **Reformat this page** so it is cleaner,BTW thanks for reading so far.. 
* **A architectural view** So you get the point of the project faster.


Buggy and lots of bugs, but getting there.


  
