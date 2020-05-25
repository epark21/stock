# Final Project

# Building a containerized machine learning prediction model and deploy it in a scalable and elastic platform.

## Members
- Edward Park
- Zach Serapin
- Kabita Paul
- Jeremiah Canty


# Goals

-	Setup and Configure Docker locally
-	Create Flask scikit-learn app in Container
-	Run deployment in a scalable and elastic platform
-	Loadtest and verify auto-scale

## US Stocks Prediction Model Colab

https://github.com/epark21/stock/blob/master/stock_final_project.ipynb

# Steps

1.	Create project: ML stock prediction model
2.	Build and test
3.	Push to Dockerhub
4.	Pull it onto AWS Cloud 9
5.	Predict via pulled Container

# Docker Workflow

![Image](../master/images/docker.png?raw=true)



https://noahgift.github.io/cloud-data-analysis-at-scale/topics/docker-format-containers.html

# Architecture

![Image](../master/images/workflow1.png?raw=true)

https://aws.amazon.com/blogs/opensource/continuous-integration-using-jenkins-and-hashicorp-terraform-on-amazon-eks/

# Locust Load Test

This is the implementation of the Locust Load Test.  This is used to simulate simultaneous users.  The idea is that during a test, a swarm of locusts will attack your website.

![Image](../master/images/locustmain.png?raw=true)
![Image](../master/images/locuststats.png?raw=true)
![Image](../master/images/requests.png?raw=true)
![Image](../master/images/response.png?raw=true)
![Image](../master/images/users.png?raw=true)
