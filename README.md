# fairness_in_ml_multiobjective_approach
ficheiro 'lexicographic_tournament' aplica uma função de seleção lexicográfica diferente da default do pymoo e realiza testes para vários thresholds e tendo diferentes objetivos como prioridade

ficheiro 'neural_network_adult_income_dataset.ipynb' treina uma rede neuronal simples para o 'adult_income_dataset' e calcula os vários tipos de fairness através da função 'fairness_calculator'

ficheiro 'fairness_in_ml_multiobjective_approach_adult_income_dataset.ipynb' junta ambas as funções testadas 'lexicographic_tournment' e 'fairness_calculator' para realizar vários testes sobre a pareto front
(usa uma variável de estado para identificar em que teste está a permitir fazer pausas a correr o código)