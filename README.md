# Data + AI Summit 2020 on 19 November
## MLOps using MLFlow

MLflow is an MLOps tool that enables data scientist to quickly productionize their Machine Learning projects. To achieve this, MLFlow has four major components which are Tracking, Projects, Models, and Registry. MLflow lets you train, reuse, and deploy models with any library and package them into reproducible steps. MLflow is designed to work with any machine learning library and require minimal changes to integrate into an existing codebase. In this session, we will cover the common pain points of machine learning developers such as tracking experiments, reproducibility, deployment tool and model versioning. Ready to get your hands dirty by doing quick ML project using mlflow and release to production to understand the ML-Ops lifecycle.


## ML-Ops
![MLOps](/Images/mlops.jpg)

* Communication between data scientist, operations or production team.
* Collaborative in nature.
* Designed to eliminate waste, automate as much as possible, produce richer, consistent insights.
* MLOps follows a similar pattern to DevOps.
* MLOps drives insights you can trust and put into play more quickly.

## MLFlow
![MLFlow Workflow](/Images/mlflow_workflow.jpg)

MLflow introduction – an open source platform for machine learning life cycle and productionizing ml model. MLflow is based on an open interface philosophy that describes a set of core abstractions that make it easier to incorporate existing infrastructure and machine learning algorithms. This means that if you're a developer who needs to leaverage MLflow and you're using a particular framework that's actually unsupported, the open interface architecture makes it incredibly simple to implement the framework and start working with the platform. Effectively, this means that MLflow is designed in principle to work with any machine learning library or any language.

It has the following primary components:

![MLFlow](/Images/mlflow.jpg)

* Tracking: Allows you to track experiments to record and compare parameters and results.
* Models: Allow you to manage and deploy models from a variety of ML libraries to a variety of model serving and inference platforms.
* Projects: Allow you to package ML code in a reusable, reproducible form to share with other data scientists or transfer to production.
* Model Registry: Allows you to centralize a model store for managing models’ full lifecycle stage transitions: from staging to production, with capabilities for versioning and annotating.
* Model Serving: Allows you to host MLflow Models as REST endpoints.
