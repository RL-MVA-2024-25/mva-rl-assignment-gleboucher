[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/1_SYVk3e)

#  RL-Class-Assignment Documentation

To solve this HIV problem, I used a quite deep and heavy DQN, compared to what was made in class. The idea is to perform different episodes, updating the weights of the DQN with the loss based on the reward and keep only the model that reached the best results on the evaluate_HIV function. 



## Training the model 

As I am currently working on mps environments, you need to modify the train.py file, swithching to cuda if you want to use a GPU. If youw to retrain the model, you need to run the following command: 
```python src/train.py```
after having installed the differents dependencies of the repository. 

## Testing the Model

To test the model, you only need to run the following command: 
```python src/main.py```
This test will only work if there is no score.txt file. 
The results should give a grade of 6/9, passing the 1e9 test (4 thresholds out of 6) for the default patient and the 2e9 (2 thresholds out of 3) for the population test

## Grading 

To obtain the grading, you can run : 
```pytest src/grading.py```

