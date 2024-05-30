# Insights from the Olfactory System:
## Exploring Expansion and Sparseness for Efficient Spiking Neural Network Architectures

This project started from 4 lads with different backgrounds and the simple question "how does smell work?". Among the outcomes of the project was contributing to the effort of informed ANN architecture choices by showing that in SNNs, _local learning rules make the system performance sensitive to the expansion ratio_ between layers, while _non-local learning rules making the system insensitive_ to expansion ratios.

This discovery guides further research in efficient deep learning (SNNs) architectures in the following way: 
- if we want **local learning** rules (e.g., STDP) between two layers we better have a **high expansion ratio betwen the pre- and pos-synaptic neurons**.
- if we want **non-local** learning rules (e.g., DECOLLE) between two layers we can be economical with our network capacity and **have as little post-synaptic neurons as pre-synaptic ones**. 


![image](https://github.com/AndreiLix/the-smelly-project/assets/94043928/2a1c7a7e-5474-4769-b365-9843d252f32b)
