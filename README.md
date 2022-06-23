# Deepknob

User identification from data retrieved by sensors using neural networks. 

User can be identified by 88% accuracy the way the user opens a door by using sensors in a handler.

## 1. Open init in colab

By tapping the button below

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlfredoFernandezGuaza/deepknob/blob/master/DeepKnob.ipynb)

## 2.  Create a zip called 'deepknob-data.zip'

This zip needs to contain:
*   Directory called 'data' with the dataset inside named as 'final_dataset.csv'

## 3. Upload deepknob-data.zip

<img src="https://user-images.githubusercontent.com/107152988/175368101-afeefcc3-cb54-4962-be8a-6e900e95eafe.png" width="50%"/>

## 4. Execute all cells

a) With <kbd>&#8984;</kbd> + <kbd>F9</kbd> or <kbd>CTRL</kbd> + <kbd>F9</kbd>

b) By tapping the first option in execution enviroment submenu: 'Execute all'.

<img src="https://user-images.githubusercontent.com/107152988/173200201-94000e5d-bbaf-4312-8d7c-98fb53734f8c.png" width="50%" />

## 5. Be Patience and Wait for Results, I've got 88% mean and median accuracy

¿Can you improve it by changing the model, the optimizer, the learning rate or the batch size?, you could also try modifing the callbacks.

Measures done by K-fold iterative with shuffle done before each iteration with k=8 and 2 iterations.


