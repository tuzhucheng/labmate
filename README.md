# labmate
A tool to keep track of your personal machine learning experiments

This tool is currently in development..

## Vision

Whether you are a ML engineer working in industry or a researcher using ML to tackle some problem, you will likely run a lot of experiments, whether it's hyperparameter tuning, trying out a variation of a model architecture, or running the same model on some new dataset. There are many variables to keep track of. Furthermore, as you progress, your model will likely change, which means the performance you obtained on an earlier model in your hyperparameter search or on some dataset is no longer up-to-date. Although you can use spreadsheets or log files to keep track of your experiments, it can quickly become overwhelming. Labmate is designed to be your assistant for helping you run and track your personal experiments.

Here is my current vision of what features labmate should have:

* Ability to store and organize logs of historical runs, including the particular arguments you used and the version of the code and data (maybe some environment info too)
* Make it easy to extract and search information from historical logs
* Ability to define, schedule, and run your experiments to keep the machine utilized (esp. GPU)
* Send push notification to you to let you know your experiments are done
* (stretch) integrate some auto hyperparameter tuning functionalities into the tool

This is meant to be a relatively lightweight, **personal** tool to be used in an individual setting.

## Comparison with Similar Tools

I have used [Future Gadget Laboratory](https://github.com/Kaixhin/FGLab) and [Codalab](http://codalab.org/) before. They are great tools for the use-cases described but both have some things missing for my own need. Hence I have decided to create my own tool.

TODO: elaborate on comparison with FGLab and Codalab.
