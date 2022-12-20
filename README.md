# Implementing strategic games on quantum computers

*Quantum game theory* (https://link.springer.com/article/10.1007/s11128-018-2082-8) studies how strategic interactions, also referred to as strategic or non-cooperative games, can be improved upon when implemented using the emerging technology of quantum computers. Non-cooperative games are ubiqituous, manifesting in biological settings when organisms compete over finite resources, in international relations when self-enforcing policies (like those for climate change) are to be drafted, in financial transactions, and in the desgin of supply-chain and network protocols. In all these settings, the fundamental solution of a non-cooperative game is the *Nash equilibrium*, a specific, stronger instance of multi-criteria optimization (MOO) in which each player's payoff in the game is the best possible, given the payoff of all other players. 

When non-cooperative games are played on a quantum computer, features of the quantum realm produce Nash equilibria that are better paying than those possible on a conventional computer (https://doi.org/10.1103/PhysRevLett.83.3077). This phenomenon holds real-world utility in the form of better paying trades when applied to online trading.

**The currenct version of this project gives Qiskit code for implementing Prisoner's Dilemma on IBM's quantum computer. This is a first step in modeling and implementing high-frequency trading (HFT) as Prisoner's Dilemma using cloud-based quantum processors (https://www.frontiersin.org/articles/10.3389/frai.2021.769392/full). The final version of this project envisions deploying a HFT-on-quantum-cloud platfom.** 

On a related note, calculating Nash equilibrium can be computationally intensive for large games (many players with many strategies). To mitigate this, quantum annealers can be used to accelarate its calculation. For example, see: https://github.com/DarkStarQuantumLab/NashEquilibrium. 

## How to run

1. In Google Collab through pip install qiskit (provided in the Notebook). The IBM Q account token may be required. 
2. Or upload the notebook to the IBM Quntum Lab (https://quantum-computing.ibm.com/). No installations are required, simply import required frameworks.
