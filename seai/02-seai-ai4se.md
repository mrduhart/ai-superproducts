- Sources

  - https://ckaestne.github.io/seai/S2020/slides/02_aibasics1/introml.html#/3
  - https://ckaestne.github.io/seai/S2020/slides/03_aibasics2/aioverview.html#/


- AI -> ML -> DL
  - AI: think / act humanly / rationally (Norvig)
  - ML: program, experience E, task T, performance P (Mitchell)
  - DL: bunch of neurons

- Artificial intelligence (good old-fashioned)
  - Symbolic: logic, propositional clauses, formal proofs, SAT problem (NP complete) - NO LEARNING!
  - Probabilistic programming (bayesian and all that): some cool programming languages can consider and work with uncertainty (really, this is cool), + ML = new hype

- Machine learning
  - Complex function mapping inputs to outputs
  - Paradigms: supervised, unsupervised, reinforcement
  - Tasks: regression, classification, ranking (recommendation), probability estimation
  - The tribes of ML (Pedro Domingos)
  - Dataframes
  - Overfitting, underfitting
  - Parameters (degrees of freedom) and hyperparameters
  - Decision trees are cool

- Deep learning
  - Artificial neuron, perceptron
  - Multilayer networks
  - Nonlinearization of weights * inputs, approximate arbitrary functions
  - Backpropagation as learning algorithm
  - Many layers of different types: FCN, CNN, RNN
  - Hierarchy of learned representations
  - Too many parameters: expensive inference and training
  - Fine-tuning (lineage: inheritance of bias)

- Model evaluation
  - Accuracy is tip of iceberg
  - Train / dev / test sets (under/overfitting)
  - Cross-validation (k-fold)
  - Researchers overfit benchmarks (leakage)

- ML pipeline
  - Requirements -> Data-ing -> Modeling -> Deploying (see CRISP-DM)
  - Data scientists have narrower focus (data + model)
  - Challenges usually arise in other steps

- Data science is iterative and exploratory
  - Data science ~ spiral and agile (uncertainty all over the place!!!, trial and error, an art, sleep-machinelearn-repeat)
  - Notebooks rock (they're quite old, actually: Knuth, Wolfram)
