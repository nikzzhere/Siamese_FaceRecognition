# Overview
This repository contains the implementation of One-Shot & Few-Shot Face Recognition using a Siamese Neural Network model. The Siamese architecture learns embeddings for faces and enables recognition even with limited samples.

# Table of Contents
1.Introduction

2.Features

3.How to Run

4.Project Report

5.Contributors

# Introduction
Face recognition in scenarios where limited training data is available is a challenging task. This project explores the use of Siamese Neural Networks to perform One-Shot & Few-Shot Face Recognition. The Siamese architecture enables learning embeddings for faces and facilitates recognition, even when there are minimal samples available for a particular individual.

# Features
Implementation of Siamese Neural Network for face recognition.
Ability to perform One-Shot & Few-Shot learning for face recognition tasks.
Project Report detailing methodologies, results, and analysis.

# How to Run
Download the ipynb file and run in your respective python environment.

# Project Report

• Our model is mainly based of self developed siamese
network and in our project we maintained same base model
but tried to check various loss functions and metrices.

• In first case we used triplets to form loss and the loss was
the difference in positive and negative distance of images.It
gave around 92 to 93 percent training accuracy and 86 to 87
percent validation accuracy.

• In second case we used quadraplets where we took mean of
distance between positive images as one input for loss function
and took loss as difference between positive and negative
distance. It gave around 85 to 86 percent training accuracy
and 80 percent for validation accuracy.

• In third case we took loss function as diference of squares
and that was pretty low and was around 65 percent for training
and 60 percent for validation.

• Computation is about equal for second and third case and
less for first case because in first case we only use three images
and for second, third case we use four images.

• In the research paper ”One-Shot Face Recognition” he got
an accuracy around 91 percent for the pubfig dataset.

• Scope for development is mentioned in the conclution

For a detailed overview of methodologies, experimental setup, results, and analysis, please refer to the Project Report.

# Contributors
Vedhamsh Bode 

Elavartha Nikhil Reddy

Prasanth
