# computational_intelligence

This README provides an overview of the COM3013 coursework, detailing the tasks, objectives, and instructions for completion.

## Module Information
- **Module Name:** Computational Intelligence
- **Module Code:** COM3013
- **Convenor:** Frank Guerin

## General Guidelines
- **Maximum Mark:** 50 (50% of the whole module)
- **Academic Misconduct:** Coursework will be routinely checked for academic misconduct. Submission must be original work.
- **Allowed Libraries:** Use of DEAP, PyTorch, NumPy, SymPy, and other libraries within reason for visualization.
- **Submission Format:** Submit a single PDF file containing the report and code.

## Task Overview
The main objective of this task is to train feed-forward multi-layer perceptron networks with two hidden layers to approximate a given function. The coursework consists of several sub-tasks, each focusing on different aspects of the implementation and evaluation.

### Task Breakdown
1. **Function Visualization**: Visualize the given function with a 3D surface plot.
2. **Data Preparation**: Generate samples for training and testing datasets and visualize them.
3. **Network Creation**: Implement a neural network with specified architecture and activation functions.
4. **Weight Manipulation Functions**: Implement functions to extract and set weights of the neural network and perform tests.
5. **Genetic Algorithm Optimization**: Use a binary coded genetic algorithm to optimize network weights.
6. **Function Visualization with Network Output**: Visualize the function implemented by the neural network.
7. **Chromosome Encoding Function**: Implement functions to encode and decode weights into chromosomes.
8. **Memetic Algorithm Implementation**: Embed Rprop learning in the genetic algorithm as a local search method.
9. **Baldwinian Learning Implementation**: Implement Baldwinian learning approach and compare results with Lamarckian approach.

## Task Execution
Each task requires implementing specific functionalities, testing them, and presenting the results. Hyperparameters tuning, code clarity, and result interpretation are essential aspects of each task.


## Conclusion
The COM3013 coursework provides practical experience in using evolutionary algorithms to solve optimization and learning problems. It enables students to gain hands-on programming skills in computational intelligence.

### Additional Task

In addition to the main tasks outlined above, there is an extra task focusing on the implementation of the Baldwinian learning approach and comparing its results with the Lamarckian approach.

#### Task Details
- **Baldwinian Learning Implementation:** Implement Baldwinian learning approach to replace the Lamarckian approach used in Task 1.8.
- **Result Comparison:** Show a plot of the training and test error across the generations, and a 3D surface plot of the function implemented by the neural network across the range [-1,1].
- **Analysis:** Analyze the difference in results compared to those obtained in Task 1.8 and discuss possible reasons for the observed differences.

#### Analysis Points
- **Effectiveness of Baldwinian Learning:** Evaluate the effectiveness of Baldwinian learning compared to Lamarckian learning.
- **Reasons for Differences:** Explore possible reasons for any observed differences in results.
- **Discussion:** Provide insights and discussion on the implications of using Baldwinian learning in the context of the task.

## Files Description

- `CI_CW1_q1.ipynb`, `CI_CW1_q2ipynb`, `CI_CW1_q3.ipynb`, `CI_CW2.ipynb`: These are Jupyter Notebook files for each question in your coursework.
- `CW2_COM3013_2021.pdf`: This PDF file contains instructions or additional materials of coursework.
- `LICENSE`: This file contains the license for your project.
- `README.md`: You're currently reading it! This file provides an overview of your repository.
- `requirements.txt`: This file lists the Python dependencies required for your project.

## Conclusion
The additional task offers an opportunity to explore alternative learning approaches and compare their performance. It enhances the understanding of different learning mechanisms in evolutionary algorithms.
