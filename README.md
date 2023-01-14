![](https://github.com/TirendazAcademy/Comet-Tutorials/blob/main/Images/Comet_Logo.jpg)

[![](https://img.shields.io/badge/Python-blue?&style=plastic&logo=python&logoColor=white)]()
[![](https://img.shields.io/badge/Comet-150050?style=plastic&logo=comet_ml&logoColor=white)]()
[![](https://img.shields.io/badge/TensorFlow-FF6E31?&style=plastic&logo=tensorflow&logoColor=white)]()
[![](https://img.shields.io/badge/Pytorch-darkblue?&style=plastic&logo=pytorch&logoColor=white)]()
[![](https://img.shields.io/badge/HuggingFace-CB1C8D?&style=plastic&logo=huggingface&logoColor=white)]()
[![](https://img.shields.io/badge/DataScience-FFC300?&style=plastic&logo=datascience&logoColor=white)]()
[![](https://img.shields.io/badge/MachineLearning-367E18?&style=plastic&logo=machinelearning&logoColor=white)]()
[![](https://img.shields.io/badge/DeepLearning-820000?&style=plastic&logo=deeplearning&logoColor=white)]()


Comet ML is an experiment tracking platform that allows data scientists and machine learning engineers to track, compare, and collaborate on their machine learning experiments. This GitHub repository contains a sample project that demonstrates how to use Comet ML to track the progress of a machine learning model, including metrics, code, and artifacts, all in one place. With Comet ML, you can easily reproduce, understand, and optimize your experiments, and share your results with your team. 
This repository will help you get started with Comet ML by showing you how to integrate it into your machine learning project.

## Comet Features

![](https://github.com/TirendazAcademy/Comet-Tutorials/blob/main/Images/ML_dev_cycle.png)

Comet ML offers a comprehensive set of features to support every stage of the machine learning lifecycle. These features include:

- Experiment tracking and management: Keep track of training runs and models, with the ability to easily reproduce experiments.
- Dataset versioning: Store and track different versions of your datasets with Comet Artifacts.
- Model registry: Maintain a library of trained models in the Comet Model Registry.
- Model production monitoring: Monitor the performance of models in production and detect any drift.
- Code panels: Create custom visualizations to speed up the iteration process.
- Reports: Share results, collaborate with team members, and measure team performance.

Overall, Comet ML allows you to easily track, compare, and collaborate on machine learning experiments, from the initial training runs to monitoring models in production.

## Install Comet

`pip install comet_ml`

## Create an Experiment and log to Comet

To add a Comet Experiment to your Project, simply copy and paste the following snippet into the top of your file:

```
## import comet_ml at the top of your file
from comet_ml import Experiment

## Create an experiment with your api key
experiment = Experiment(
    api_key="Your API Key",
    project_name="Your Project Name",
    workspace="Your Workspace Name",
)
```

📌 If you enjoy this repo, don't forget to give me a ✨. Thanks for reading 😀

🔗 Let's connect [YouTube](http://youtube.com/tirendazacademy) | [Medium](http://tirendazacademy.medium.com) | [Twitter](http://twitter.com/tirendazacademy) | [Instagram](https://www.instagram.com/tirendazacademy) 😎
