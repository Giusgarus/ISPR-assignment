# ISPR 24/25 - Assignments

This repository contains the assignments for the ISPR course (Intelligent Systems for Pattern Recognition) for the academic year 2024/2025. Each folder corresponds to one of the four assignments given during the course.

## Repository Structure

- `First/`: (track 4) Edge detection with convolution filters.  
- `Second/`: (track 4) Bayesian Network modeling and sampling.  
- `Third/`: (track 2) Horse semantic segmentation with convolutional neural networks.  
- `Fourth/`: Paper review and presentation.

## Assignment Details

### Assignment 1: Edge Detection with Convolution Filters

**Description:**  
Implement the convolution of a set of edge detection filters with an image and apply it to at least three images of your choice from the [dataset](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction#). Implement Roberts, Prewitt, and Sobel filters (see here, Section 5.2, for a reference) and compare the results (it is sufficient to do it visually). You should not use library functions for performing the convolution or generating the Sobel filter. Implement your own and show the code!

**Instructions:**  
1. Select at least three images from the provided [dataset](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction#).  
2. Implement the Roberts, Prewitt, and Sobel edge detection filters from scratch. Avoid using library functions for convolution or filter generation.  
3. Apply each filter to the selected images and visually compare the results.  
4. Document your implementation process, including the code and visual outputs, in a report or notebook.  
5. Submit your code and report by the specified deadline.  

**Deadline:**  
[Friday, 21 March 2025, 6:00 PM]

### Assignment 2: Bayesian Network Modeling and Sampling

**Description:**  
Implement a Bayesian Network (BN) comprising at least 10 nodes, all with binomial or multinomial distribution. Represent the BN with the data structures that you deem appropriate and in the programming language that you prefer. The BN should model some problem/process of your choice, so you are also free to define the topology according to your prior knowledge (just be ready to justify your choices). For instance, you can define a BN to represent a COVID diagnosis through a certain number of events/exams/symptoms: e.g. Cough, Cold, Fever, Breathing problems, Swab Exam, etc. Or you can model your daily routine: Wakeup, Coffee, Toilet, Study, Lunch, etc.

Once you have modelled the BN, also plug in the necessary local conditional probability tables. You can set the values of the probabilities following your own intuition on the problem (i.e., no need to learn them from data). Then run some episodes of Ancestral Sampling on the BN and discuss the results.

The assignment needs to be fully implemented by you, without using BN libraries.

**Instructions:**  
- Design and implement the Bayesian Network with at least 10 nodes.  
- Define the topology and justify your choices.  
- Populate the local conditional probability tables with intuitive values.  
- Perform Ancestral Sampling and analyze the results.  
- Provide a detailed explanation of your implementation and findings.

**Deadline:**  
[Tuesday, 22 April 2025, 2:00 PM]

### Assignment 3: Horse Semantic Segmentation with Convolutional Neural Networks

**Description:**  
Implement a convolutional neural network (CNN) for semantic segmentation of horses in images. You are required to use a publicly available dataset, such as the [Weizmann Horse Dataset](https://www.msri.org/people/members/eranb/horse.html), and train a model to segment horse regions from the background. You may use popular deep learning frameworks (e.g., PyTorch, TensorFlow) and leverage pre-trained models if desired, but you must clearly document any transfer learning or data augmentation strategies used.

**Instructions:**  
1. Download and preprocess the horse segmentation dataset.  
2. Design and implement a CNN architecture suitable for semantic segmentation (e.g., U-Net, FCN).  
3. Train your model on the training set and evaluate its performance on the validation/test set using appropriate metrics (e.g., IoU, pixel accuracy).  
4. Visualize and discuss the segmentation results, highlighting both successes and failure cases.  
5. Document your code, methodology, and findings in a report or notebook.  
6. Submit your code, trained model, and report by the deadline.

**Deadline:**  
[Tuesday, 20 May 2025, 2:00 PM]

### Assignment 4: Paper Review and Presentation

**Description:**  
The fourth midterm covers the program until lecture 36. Unlike previous assignments, this midterm requires you to read and summarize the main findings of a single paper chosen from the list provided below.

Students are expected to deliver a short presentation (no more than 8 slides) covering the following content:

- Introduction to the problem
- Model description
- Key insight of the model, represented by a commented equation
- Key (empirical) result
- Comments on novelties, strengths, and weaknesses

Paper chosen: [Ho and Ermon, Generative Adversarial Imitation Learning, NIPS 2016](https://arxiv.org/abs/1606.03476)

**Instructions:**  
1. Select one paper from the provided list.
2. Carefully read and analyze the paper.
3. Prepare a presentation (maximum 8 slides) addressing all required points.
4. Highlight and comment on a key equation from the paper.
5. Summarize the main empirical result(s).
6. Discuss the novelties, strengths, and weaknesses of the work.
7. Submit your slides and be ready to present them on the assigned date.

**Deadline:**  
[Friday, 27 June 2025, 6:00 PM]  
(For the first appello: Wednesday, 4 June 2025, 6:00 PM)

## Contribution Guidelines

If you want to contribute or have any questions about the assignments, feel free to open an issue or submit a pull request. Make sure to follow the course rules for assignment submissions.
