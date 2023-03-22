In this long research project, I did several tasks in order to reach the goal which is about effective hospital management during COVİD-19. Below, there are steps and explanation of the project.
1. Linear Programming for Hospital Resource Management:
Firstly, I developed a model using Linear Programming with several conditions which gives the appropriate numbers meaning the number of hospital resources in order to maximize the objective function.
2. Linear Programming for Nurse Scheduling:
Secondly, I used similar technique to develop a model which is about nurse scheduling based on their satisfaction. The constraints are mainly about the satisfactions such as how many times a nurse can work sequentially, how many times a nurse can work in a week and some more constraints like these ones.
3. Based on the results of two above tasks, the number of patients that an hospital can accept is identified. Next step is to classify accepted patients according to their criticality levels. For this purpose, I used and combined two different models explained below.
3.1 X-Ray Images Classification:
Firstly, I trained a Convolutional Neural Network (CNN) model to classify whether a patient has pneumonia or not using X-Ray images.
3.2 Row Data Classification:
Secondly, I used row data that was made publicly available by Mexican government to classify patients into 3 criticality levels which are low, medium, and high. One of the input variable of this model is pneumonia that is entered as a result of above CNN model using X-Ray image of a patient.
4. Patient Distribution:
After classification, I give a weight to each patient and based on some limits, I distribute these patients among nurses such as a nurse can take only 2 medium patients, 1 high and 1 low patients and other limits.
5. Website Development:
At the end of the project, I developed a user-friendly website for this project using HTML, CSS, and Python (Django) programming languages for easy use.
