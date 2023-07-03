# Chapter-18

This repository is to introduce the important topics in a Data Science Project: Model Deployment.

Few things to consider before putting a model into a production.
Firstly, we need to consider the business stakeholders. We need to be very confident in model's performance and its output results. We don't want to deploy a model into production that is not good enough from the business point of view/ objectives. 

Second, cost may be a factor to consider. Putting a model into production requires investment infrastructure: a server (local or in the cloud) is needed to host the model. So, there will be a recurring cost involved. 

Third, to define the process to manage the life cycle of the model. How will you check that your model is not deviating from the ground truth after time? Will you retain and update your model every week, or month? How will we keep track of the different versions of our model and the data used for training and testing? 

These are the kinds of questions we need to consider, think through, and plan.

Once we get all the green lights, then we can move our machine learning model into production.

This repository is intended on how we can serve our model as an on-demand service via a web API.
