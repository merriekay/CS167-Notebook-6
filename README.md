# Notebook \#6
Using CNNs to predict whether a chest x-ray has pneumonia. 

## The Data: 📊

For this notebook, you will train a convolutional neural network for an image recognition task (like the cat vs. dog example). In this case, your algorithm will utilize a dataset of chest x-ray images to help learn how to diagnose pneumonia. The assignment is inspired by the Kaggle data competition  https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

I have sampled the images in the dataset to 200x200 pixels to allow you to download the dataset in a reasonable format (52 MB compared to 1GB for the full-resolution images).

## The Exercises: 💪
The assignment is to run an experiment where you try a basic CNN network and then try a variation on it to see what happens. I will be looking for the following:

1. In a mark-down cell near the top of your notebook, give a brief explanation of your problem.  
2. Build a **baseline CNN** that has this structure:
  - Conv layer 1
  - Pool layer 1
  - Conv layer 2
  - Pool layer 2
  - Flatten
  - Fully Connected (Dense)

3. Build a **tuned CNN**--simply a CNN that has some changes from the first one. You may change whichever parameters you like (consider the kernel size, the number of layers, the types of layer, the number of feature maps in each layer, adding dropout layers, etc). Just make some sort of change that you think might be significant, train you new model, and compare its performance to the original. In a text-cell, describe what you changed.   
    - You should train each model for enough epochs that your performance on the test set stops improving (i.e., show where you reach overfitting)  OR for at least 30 minutes of training time. If you would like to further experiment with additional changes, that is fine, but because these things sometimes take a long time to train, I'm setting a low bar for just showing me two variations.

4. **Include graphs** of how well your testing data performed vs. the training data.

5. **Conclusions**: Answer the following questions in a markup cell at the bottom of your notebook.
    - What configuration of your CNN proved to be more accurate? Why do you think this is the case?
    - How accurate can you make your CNN predictor? I will award a bonus point to the student who can achieve the most accurate model.

Use a Markup cell to put your name at the top of the file. Rename your file LastnameNotebook6.ipynb and submit the link to your repository to Blackboard.

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded (out of 1)  | Notes |
| --------- | ------------------- | --------- |
| 1: Problem       |        |     |
| 2: Baseline CNN  |        |    | 
| 3: Tuned CNN     |        |    |
| 4: Graphs        |        |    | 
| 5: Conclusions   |        |    |
| <b>Total         |     /5 | </b>   |
