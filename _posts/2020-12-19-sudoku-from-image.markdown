---
title: "Sudoku Solutions from Image"
layout: post
# date: 2016-01-23 22:10
tag: jekyll
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "A program that detects sudoku puzzle from an image and solves it using recursion."
category: project
author: kalpitborkar
externalLink: false
---

# Sudoku Solutions from Image: Computer Vision
A program that detects sudoku puzzle from an image and solves it using recursion.\
Check the github repository here: [Sudoku Solutions from Image](https://github.com/kalpitborkar/Sudoku-Solutions-from-Image)

The project is divided into three parts:
  - Part One: Digit Classification Model
  - Part Two: Detecting And Reading The Sudoku From An Image
  - Part Three: Solving The Puzzle

## Part One: Digit Classification Model
In this section:
  - Loading Data
  - Splitting The Test Train And Validation Sets
  - Preprocessing The Data
  - Model Building And Training

## Part Two: Detecting and Reading the Sudoku from an Image
In this section:
- READING THE SUDOKU PUZZLE
  - Read an image from the dataset
  - Preprocess the image
- DETECTING CONTOUR
  - Detect the biggest contour of the image.
  - Reshaping the outline to get the cropped and well-aligned Sudoku
- SPLITTING THE CELLS AND CLASSIFYING DIGITS
  - Splitting the sudoku box into 81 cells with empty spaces or digits
  - Cropping the cells to avoid misdetection of boundary lines as digits
  - Using the model to classify the digits in the cells such that the empty cells are classified as zero
  - Getting the detected output in the form of an array of 81 digits

## Part Three: Solving the Puzzle
In this section:
  - Reshaping the array into a 9 x 9 matrix
  - Solving the matrix using recursion

## Built With
- [TensorFlow 2](https://www.tensorflow.org/)
- [Keras](https://www.tensorflow.org/api_docs/python/tf/keras)
- [OpenCV](https://opencv.org/)