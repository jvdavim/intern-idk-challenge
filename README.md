# intern-idk-challenge

## Summary

The goal of this challenge is to evaluate the internship candidate technically. The evaluation criteria is described in
the last section. The rules and instructions are in the sections bellow.

## Rules

1. The project must be in a private github repository.
2. The documentation must be written in a `README.md` file in the project's root folder.
3. All the stages must work on linux (any distribution).

## Instructions

The challenge is composed of two major stages.

1. Train an supervised image classification machine learning model.
    - Download the `archive.zip` file from [https://drive.google.com/drive/folders/1rXZHeOh6Xv_uaKZIRVCQfrrAiY5_iqQX?usp=sharing] and unzip it in a folder of your choice.
    - Develop a python script to train and evaluate a machine learning algorithm to classify the flowers. It's up to you the choice of the machine learning library or framework to run the experiments. It must be clear how to run the experiments on the documentation.
    - You need to generate artifact(s) from the experiment so the model can be recovered from disk later.

2. Deploy the model so it can be used by other users and systems.
    - With the artifact(s) generated on the previous stage, you have to create a service that can be consumed by other users and systems in real time. The framework is up to the user.
    - The documentation should have clear instructions about how to deploy the service. It doesn't need to be deployed, but must any user must be able to deploy it following the documnetation.

## Hints

- You are free to choose the python dependencies, but it's important to show your skills with python, so I would recommend the usage of large community libraries like numpy, scikit-learn, pytorch, tensorflow, and so on.
- The model accuracy metrics are not important. It's important to show your skills with machine learning, like how do you evaluate your model, how do you choose the models hyperparameters, etc.
- Feel free to choose any kind of deployment solution you want to. Some options are Docker, Linux daemon, web server, or even a CLI (Command Line Interface). If you don't know what is a deployment or how to do this kind of stuff, this is a good oportunity to learn it!
- We strongly recommend you to search for solutions on google or any other search engine. Your hability to adapt and get advantage of someone else's solution will be evaluated too. Pay attention to the licenses, and don't forget to document the credits. Again, if you don't know what is a license and how it works, this is a great chance to learn.

## Evaluation Criteria

- Python skills - How well does the candidate knows python?
- Git skills - How the candidate knows git?
- Machine learning skills - What does the candidate knows about machine learning?
- Documentation quality - How easy is to understand the project following the documentation?
- Code quality - Does the candidate follows best pratices and patterns?
- Organization - How does the candidate organized the project? Is it easy to understand the project's folder structure? How the training, evaluation and deployment codes are organized in the project?
- Transparency - Is the solution presenting the respective credits and referencing what was done by another author?
