Bayesian Network Model Execution

1. Install the required libraries for probabilistic Graphical Models
pgmpy: Python library for Probabilistic Graphical Models

2. Run the model
Upload the model7 file and execute the commands 

3.Understanding the models
The code defines a Bayesian Network model with nodes representing different variables (A, B, C, D) and their relationships.

Conditional Probability Distributions (CPDs) are defined for each variable based on the problem description.

Inference is performed using the Variable Elimination method to answer various queries about the model.

4. Performing Queries
The code executes several predefined queries on the model to obtain probabilistic predictions or make inferences:

Query 1: Probability of patient condition A.
Query 2: Probability distribution of test result B given the patient's condition A is poor.
Query 3: Probability distribution of treatment decision C given the patient's condition A is fair and test result B is negative.
Query 4: Probability distribution of outcome D given the patient's condition A is fair, test result B is positive, and treatment decision C is not treated.
Query 5: Most likely outcome D given observed values of variables A, B, and C.
Query 6: Predicting treatment decision C given the patient's condition and test result.
Query 7: Sensitivity analysis of outcome D to changes in treatment decision C.
Query 8: Probability distribution of the patient's outcome D under varying conditions for variables A, B, and C.

5. Viewing Output
The results of each query are printed to the console.
