# Neuromatch-2024

These are some of the project files created during the [NeuroMatchAcademy](https://github.com/NeuromatchAcademy/course-content/tree/main) course. 
This project is based on the open source dataset from the [Allen Brain Atlas](https://allensdk.readthedocs.io/en/latest/visual_behavior_optical_physiology.html). 
You can read more about the scientific discoveries related to this dataset in the following preprint.

Garrett, M. et. al. (2023) Stimulus novelty uncovers coding diversity in visual cortical circuits. bioRxiv [doi](https://www.biorxiv.org/content/10.1101/2023.02.14.528085v2)

## Investigating cell type and layer-specific processing of novelty in mouse primary visual cortex

Accurate detection of change is a fundamental aspect of sensory processing that enables organisms to respond appropriately to their environment. 
Recent studies have identified a key circuit motif in the mouse primary visual cortex that processes novel visual stimuli ([Krabbe et al., 2019](https://www.nature.com/articles/s41593-019-0508-y); [Pi et al., 2013](https://www.nature.com/articles/nature12676)). 
This circuit consists of reciprocally connected excitatory neurons and inhibitory interneurons, including those expressing vasoactive intestinal peptide (VIP) 
and somatostatin (SST). These studies suggest that novelty induces a net disinhibition of excitatory neurons through Vip-mediated inhibition of SSt interneurons 
([Furutachi et al. 2024](https://www.nature.com/articles/s41586-024-07851-w)). Given the well-established diversity of both excitatory and inhibitory neurons across cortical layers, layer-specific processing of novelty 
signals is an important question. Prediction error signals have been primarily observed in layer 2/3 of the visual cortex ([Homann et al., 2022](https://www.pnas.org/doi/10.1073/pnas.2108882119); [Keller and 
Mrsic-Flogel, 2018](https://www.sciencedirect.com/science/article/pii/S0896627318308572); [Muzzu and Saleem, 2021](https://pubmed.ncbi.nlm.nih.gov/34610298/)), while deeper layers are thought to encode memory-related signals (Doron et al., 2019; Murayama et al., 2009). 
The differential processing of novel stimuli by neurons in the excitatory-Vip-Sst circuit motif across superficial and deep cortical layers remains understudied. 
We aim to address whether novelty processing is depth-specific or not by using the Allen Institute 2-photon Visual Behaviour dataset (de Vries et al., 2020, Siegle 
et al., 2021., Garrett et al., 2023), which includes imaging and behavioral data from mice performing a visual change detection task. After filtering and collating 
the 2-photon imaging traces according to cell type, recording depth, and session type for familiar, novel, and novel-re-exposure visual stimuli, our analysis 
employs non-linear dimensionality reduction (t-SNE) to investigate how image feature, change detection, and omission error encoding vary across cortical depth 
for each cell type. This work will enable us to identify V1 layer-specific differences in novelty processing in the excitatory-Vip-Sst circuit motif.


**This project was developed by**
* Aishwarya Vedula | PhD Candidate at Oxford
* Ekaterina Koulakova | Research Associate at NYU
* Cyril Akafia | Postgraduate Associate at Yale
* Maxime Vounatsos | PhD Candidate at Carnegie Mellon University
