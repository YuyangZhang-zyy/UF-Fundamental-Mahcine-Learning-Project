[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Pe2yaTlT)
# Final Project

This is a **group assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

The final project is due Wednesday, December 6 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/479520/assignments/5825839) in the Canvas assignment.

## Training Data

The training data set is the same for every team in this course.

You can download the training data from the Canvas page:

* ["data_train.npy"](https://ufl.instructure.com/files/81900020/download?download_frd=1)
* ["labels_train.npy"](https://ufl.instructure.com/files/81900021/download?download_frd=1)

## Edit this READ-ME

Please edit this read-me file with information about your project. You can find a [READ-ME template here](https://github.com/catiaspsilva/README-template).

## README

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#authors">Authors</a></li>
  </ol>
</details>

## About The Project

In this project, we use the deep neural networks model we created to complete the task of classifying gesture pictures. We need to build a model to classify gesture images into 9 categories (corresponding to a-i) through the training set. Through multiple tests, we found the optimal hyperparameters and used them to train the model with the highest accuracy we could achieve. We use **TensorFlow 2.7.0** to complete this project. **We are not planning to complete extra credit task in this project.**

### File list:

## Files in github:

1. Final Project - Training Data.ipynb: Project 3 guideline.

2. training.ipynb: Training file that contains the models training and hyperparameter tuning steps.

3. training.pdf: pdf version of training.ipynb.

4. test.ipynb: Test file for evaluating the final trained model in the test set. This file loads all trained objects and simply evaluate the performance. All expected plot and graph are contained

5. test.pdf: pdf version of test.ipynb.

6. Final Project Report.pdf: 4-page IEEE-format paper addressing the details in model.

7. Model: Robotboy_model.h5 (save as large file)

8. Training data: data_train.npy, labels_train.npy


## Download links for large files:

Model: https://drive.google.com/file/d/1eTCq6N7FO6b3_ErQ0JpiWJBQHK9TgUxR/view?usp=sharing

Training data: Links provided above

## Getting Started

### Dependencies

This project uses HiperGator environment: TensorFlow 2.7.0

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/UF-FundMachineLearning-Fall23/final-project-code-report-robotboy.git
   ```

## Usage

After downloading all necessary files, you can open training.ipynb and test.ipynb using Jupyter Notebook or any IDE you like. Remember the running environment is on HiperGator TensorFlow 2.7.0. So better use TensorFlow 2.7.0 on your local. First run all the codes in training.ipynb in order from top to bottom. You can get the model. In test.ipynb, run all the code from top to bottom. You have to provide the test data to run the predict. You can directly run the test.ipynb to test the created model (robotboy_model.h5).

Since the maximum memory that can be applied for on hiperGator is 16GB, running the code will cause some kernel died problems caused by insufficient memory:

1. After running the model fit of 80% of the training set in training.ipynb, and continuing to run the code to create the final model, fitting the complete training set causes the kernel to die. Please run the 80% training set and the full training set separately as needed. The models we provide are models trained with the full training set.

2. If the model is re-run after running it once, kernel died caused by insufficient memory. Please run it again. Following the markdown cell we wrote and re-run part of the cells

3. When the input size is adjusted to be larger than $210*210*3$, kernel died will occur when running the code. Please avoid adjusting input size

## Authors

Xinrun Li - xinrunli@ufl.edu

Hang Shu - hangshu@ufl.edu

Yuyang Zhang - yuyoungzhang@gmail.com


Project Link: [https://github.com/UF-FundMachineLearning-Fall23/final-project-code-report-robotboy](https://github.com/UF-FundMachineLearning-Fall23/final-project-code-report-robotboy)

## Thank you