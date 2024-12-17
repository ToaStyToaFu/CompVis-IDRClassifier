# Rupiah Currency Recognition System

[![My Skills](https://skillicons.dev/icons?i=py)](https://skillicons.dev)
[![My Skills](https://skillicons.dev/icons?i=tensorflow)](https://skillicons.dev)

## Project Overview
This research project aims to develop an innovative image recognition system to help visually impaired individuals identify Rupiah banknotes independently through advanced computer vision techniques.

## Problem Statement
Individuals with visual impairments face significant challenges in recognizing and handling currency notes during daily financial transactions. This system provides a technological solution to enhance their financial independence.

## Key Features

- Image classification of Rupiah banknotes
- Audio feedback for currency denomination
- Utilizes advanced computer vision techniques

## Methodology
The research compared two image classification approaches:
### System A

Methods: MLP with manual feature extraction (SIFT and ORB)
Training Accuracy:

- ORB: 97.78%
- SIFT: 94.33%


Validation Accuracy:

- ORB: 53.84%
- SIFT: 67.77%


Limitation: Significant overfitting

### System B

Methods: SVM and FCNN with FLANN matching and RANSAC filtering
Validation Accuracy:

- FCNN: 74%
- SVM: 68%


Bias towards Rp10.000, Rp50.000, and Rp100.000 denominations

Technology Stack

Computer Vision
Machine Learning Algorithms

Multilayer Perceptron (MLP)
Support Vector Machine (SVM)
Fully Connected Neural Network (FCNN)


## Feature Extraction Techniques

SIFT (Scale-Invariant Feature Transform)
ORB (Oriented FAST and Rotated BRIEF)


## Matching Methods

FLANN (Fast Library for Approximate Nearest Neighbors)
RANSAC (Random Sample Consensus)



## Future Development

Expand dataset with diverse lighting and angle conditions
Increase data variety to improve system performance
Develop mobile application with voice feedback
Explore additional machine learning models
Enhance generalization capabilities

## Research Contribution
Developing an inclusive technology to support individuals with visual impairments in independently recognizing Rupiah currency denominations.
Ethical Impact
Aims to create assistive technology that promotes independence and accessibility for disabled individuals.

### Contributors:
<table>
  <tbody>
        <td align="center" valign="top" width="14.28%"><a href="https://github.com/yinsxie"><img src="https://avatars.githubusercontent.com/u/118384182?v=4" width="100px;" alt="Amelia"/></td>
        <td align="center" valign="top" width="14.28%"><a href="https://github.com/ToaStyToaFu"><img src="https://avatars.githubusercontent.com/u/115855066?v=4" width="100px;" alt="Stanley"/></td>
        <td align="center" valign="top" width="14.28%"><a href="https://github.com/DLiech"><img src="https://avatars.githubusercontent.com/u/122514634?v=4" width="100px;" alt="Deanzen Lie"/></td>
        <td align="center" valign="top" width="14.28%"><a href="https://github.com/davetjong2"><img src="https://avatars.githubusercontent.com/u/163985225?v=4" width="100px;" alt="Dave Tjong"/></td>
        <td align="center" valign="top" width="14.28%"><a href="https://github.com/itzKv"><img src="https://avatars.githubusercontent.com/u/116947826?v=4" width="100px;" alt="Kevin Brivio"/>
        </td>
</tbody>
</table>
