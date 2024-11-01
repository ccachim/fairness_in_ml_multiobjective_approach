# fairness_in_ml_multiobjective_approach
The file 'lexicographic_tournament' applies a lexicographic selection function different from the default in Pymoo and runs tests for various thresholds, prioritizing different objectives.

The file 'neural_network_adult_income_dataset.ipynb' trains a simple neural network for the adult_income_dataset and calculates various fairness metrics using the 'fairness_calculator' function.

The file 'fairness_in_ml_multiobjective_approach_adult_income_dataset.ipynb' combines both functions tested—'lexicographic_tournament' and 'fairness_calculator'—to perform multiple tests on the Pareto front (it uses a state variable to identify the current test, allowing for pauses when running the code).