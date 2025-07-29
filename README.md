# Neural Cryptography: Tree Parity Machine Key Exchange and Attack Simulation

This project implements a neural key exchange protocol using Tree Parity Machines (TPMs). It demonstrates how two parties (Alice and Bob) can synchronize their weights and generate a shared secret key over a public channel and how an attacker (Eve) may attempt to eavesdrop or interfere.

## Overview

- **Algorithm**: Tree Parity Machine synchronization
- **Goal**: Explore neural-based cryptographic key exchange
- **Bonus**: Visualizations and attack analysis (e.g., Eve vs. Bob sync)

## Project Structure

<pre><code>### 
   . ├── images/ # Diagrams and visual outputs 
     │ ├── Evolution of Weight Alice-Bob.png 
     │ ├── Final TPM Weights Comparison Alice-BobvsEve.png 
     │ ├── TPM Final Weight Matrices Visual Comparison Alice-Bob.png 
     │ └── Tree Parity Machine Synchronization BobvsEve.png 
     │ 
     ├── notebooks/ # Jupyter notebooks for simulation & visualization 
     │ └── Tree_Parity_Machine_Key_Exchange_and_Attack_Simulation.ipynb 
     │ 
     ├── src/ # Core Python implementation  
     │ └── tree_parity_machine_key_exchange_and_attack_simulation.py 
     │ 
     ├── .gitignore 
     ├── LICENSE  
     └── README.md </code></pre>


## How to Run

* **1. Clone the repo:**
   ```bash
   git clone https://github.com/your_username/your_repo_name.git
   cd your_repo_name

* **2. Install dependencies:**
  No external libraries required (only standard Python modules).

* **3. Run the notebook:**
            jupyter notebook notebooks/Tree_Parity_Machine_Key_Exchange_and_Attack_Simulation.ipynb

* **4. Or run the Python script:**
            python src/tree_parity_machine_key_exchange_and_attack_simulation.py

## Visuals
            <img src="images/Final TPM Weights Comparison Alice-BobvsEve.png" width="400"/> 
            <img src="images/Tree Parity Machine Synchronization BobvsEve.png" width="400"/>

## Key Concepts

* **Tree Parity Machine (TPM)**: A neural network model used in mutual learning-based key exchange.
* **Synchronization**: Both Alice and Bob adjust weights iteratively until their TPMs match.
* **Eavesdropper (Eve)**: Attempts to synchronize with either party by observing exchanged data.

## References

## 📚 References

- Kanter, I., Kinzel, W., & Kanter, E. (2002). *Secure exchange of information by synchronization of neural networks*. EPL (Europhysics Letters), 57(1), 141. [DOI:10.1209/epl/i2002-00552-6](https://arxiv.org/abs/cond-mat/0202112)
- Ruttor, A., & Kinzel, W. (2004). *Neural cryptography with queries*. Physica A: Statistical Mechanics and its Applications, 335(3-4), 517–524. [DOI:10.1016/j.physa.2003.12.011](https://www.researchgate.net/publication/1875878_I_Neural_cryptography_with_queries)
- Mislovaty, R., Perchenok, Y., Kanter, I., & Kinzel, W. (2002). *Secure key-exchange protocol with an absence of injective functions*. Physical Review E, 66(6), 066102. [DOI:10.1103/PhysRevE.66.066102](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.66.066102)

## 📄 License

This project is licensed under the MIT License.


