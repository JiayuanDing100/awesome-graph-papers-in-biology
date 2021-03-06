# Awesome-GNN-Papers-in-Biology (genomics, xx, xx, xx, ...)

Single cell analysis:
1. Deep learning tackles single-cell analysis – A survey of deep learning for scRNA-seq analysis
2. Eleven grand challenges in single-cell data science
3. Graph Representation Learning in Biomedicine
4. Biological network analysis with deep learning


https://pubmed.ncbi.nlm.nih.gov/30555904/ (some related papers)

https://www.pandelab.org/about

### Drug discovery

Predicting the properties of molecules or compounds is a fundamental problem in drug discovery

Each molecule is represented as a graph. Many data in this domain are graph-based (Molecules, biomedical knowledge graphs).

Could graph neural networks learn better molecular representation for drug discovery? A comparison study of descriptor-based and graph-based models， 2021


#### Problems

1. **Molecule properties prediction**
2. **De novo melecule design and optimization**
3. **Molecular Geometry Prediction**
4. **Retrosythesis reaction prediction**
5. **reasoning on biomedical knowledge graphs with applications in drug repurposing**

## [Molecule properties prediction](#content)   
1. **A compact review of molecular property prediction with graph neural networks**, 2020, citation: 16

2. **3D Pre-training improves GNNs for Molecular Property Prediction， ICLR 2022**

3. **Simple GNN Regularisation for 3D Molecular Property Prediction and Beyond, ICLR 2022**

## [De novo melecule design and optimization](#content) 
1. **Advances in De Novo Drug Design: From Conventional to Machine Learning Methods**, 2021


## [Molecular Geometry Prediction](#content) 
1. **Molecular Geometry Prediction using a Deep Generative Graph Neural Network**, 2019, citation: 35

1. **Learning neural generative dynamics for molecular conformation generation.**, 2021, citation: 9

1. **An End-to-End Framework for Molecular Conformation Generation via Bilevel Programming**, 2021, citation: 1

1. **Learning gradient fields for molecular conformation generation.**, 2021, citation: 1


## [Retrosythesis reaction prediction](#content) 
1. **Enhancing Retrosynthetic Reaction Prediction with Deep Learning Using Multiscale Reaction Classification**, 2019, citation: 49

1. **Retrosynthetic reaction prediction using neural sequence-to-sequence models**, 2017, citation: 218
https://www.cas.org/resources/blog/ai-retrosynthesis-planning

2. **SemiRetro: Semi-template framework boosts deep retrosynthesis prediction, ICLR 2022**

3. **Permutation invariant graph-to-sequence model for template-free retrosynthesis and reaction prediction, ICLR 2022**

## [Drug Repurposing](#content)
1. **Neural Bellman-Ford Networks: A General Graph Neural Network Framework for Link Prediction**, 2021

1. **RNNLogic: Learning Logic Rules for Reasoning on Knowledge Graphs**, ICLR, 2021

1. **Probabilistic Logic Neural Networks for Reasoning**, NIPS, 2019

1. **RotatE: Knowledge Graph Embedding by Relational Rotation in Complex Space**, ICLR, 2019


## [polypharmacy side effect prediction](#content)
1. **polypharmacy side effects with graph convolutional networks**, 2018, citation: 443





The fundamental problem: how to represent a whole molecule (graph)

1. **InfoGraph: Unsupervised and Semi-supervised
Whole-Graph Representation Learning**, ICLR, 2020

1. **Utilising graph machine learning within drug discovery and development**, Arxiv, 2021, 

1. **Drug-drug adverse effect prediction with graph co-attention**, Arxiv, 2019, citation: 15

1. **GraphAF: an Autoregressive Flow for Molecular Graph Generation**, ICLR, 2020

1. **A Graph to Graphs Framework for
Retrosynthesis Prediction**, ICML, 2020

1. **Generating Focussed Molecule Libraries for Drug Discovery with Recurrent Neural Networks**，2017, citation: 652

1.  **Molecular De Novo Design through Deep Reinforcement Learning**, 2017, citation:  455

1. **Application of generative autoencoder in de novo molecular design**, 2018, citation: 233

1. **Objective-Reinforced Generative Adversarial Networks (ORGAN) for Sequence Generation Models**, 2017, citation: 280

1. **Optimizing distributions over molecular space. An Objective-Reinforced Generative Adversarial Network for Inverse-design Chemistry**, 2017, citation: 151

1. **MoleculeNet: A Benchmark for Molecular Machine Learning**, 2017, citation: 850

1. **Retrosynthetic reaction prediction using neural sequence-to-sequence models**, 2018, citation: 218

1. **druGAN: An Advanced Generative Adversarial Autoencoder Model for de Novo Generation of New Molecules with Desired Molecular Properties in Silico**, 2017,  citation:  254





#### Reasoing on. Knowledge Graph (drug discovery)

1. **Rotate: Knowledge graph embedding by relational
rotation in complex space**, ICLR, 2019

1. **Probabilistic logic neural networks for reasoning**, NIPS, 2019

1. **RNNLogic: Learning Logic Rules
for Reasoning on Knowledge Graphs**, ICLR, 2021



### Diffusion maps:

Diffusion maps for high-dimensional single-cell analysis of differentiation data, Bioinformatics, 2021

Visualizing structure and transitions in high-dimensional biological data,  nature biotechnology, 2019

### Protein structure:

Structure-based protein function prediction using graph convolutional networks, Nature Communications, 2021

Single-cell classification using graph convolutional networks, BMC Bioinformatics, 2021

scGNN is a novel graph neural network framework for single-cell RNA-Seq analyses, Nature Communications, 2021

Protein Docking Model Evaluation by Graph Neural Networks, Front. Mol. Biosci, 2021

Self-supervised graph transformer on large-scale molecular data， NeurIPS, 2020

GraphDF: A Discrete Flow Model for Molecular Graph Generation, ICML, 2021

GraphEBM: Molecular Graph Generation with Energy-Based Models, Workshap, 2021

Deep Learning of High-Order Interactions for Protein Interface Prediction, KDD, 2020

Non-local U-Nets for Biomedical Image Segmentation, AAAI, 2020

Deep Model Based Transfer and Multi-Task Learning for Biological Image Analysis, IEEE Transactions on Big Data, 2020

Computational Modeling of Cellular Structures Using Conditional Deep Generative Networks, Bioinformatics, 2019

LM-GVP: A Generalizable Deep Learning Framework for Protein Property Prediction from Sequence and Structure, 2021

Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation, NIPS 2018


## [Single Cell RNA sequence](#content)  

Graph representation learning for single-cell biology, 2021

Potential applications of deep learning in single-cell RNA sequencing analysis for cell therapy and regenerative medicine, 2021

Disease State Prediction From Single-Cell Data Using Graph Attention Networks, 2020

SCGNN: scRNA-seq Dropout Imputation via Induced Hierarchical Cell Similarity Graph, ICML 2020 workshop

GNNfam: utilizing sparsity in protein family predictions using graph neural networks, 2021

## [Cancer](#content)  
Biologically informed deep neural network for prostate cancer discovery, Nature, 2021

## [Protein-GNN-ICLR 2022](#content)  
Fast fixed-backbone protein sequence and rotamer design

Independent SE(3)-Equivariant Models for End-to-End Rigid Protein Docking

De novo design of protein target specific scaffold-based Inhibitors via Reinforcement Learning

An Effective GCN-based Hierarchical Multi-label classification for Protein Function Prediction

Geometric Transformers for Protein Interface Contact Prediction

Iterative Refinement Graph Neural Network for Antibody Sequence-Structure Co-design

Granger causal inference on DAGs identifies genomic loci regulating transcription

## [Molecular-GNN-ICLR 2022](#content)  
Spanning Tree-based Graph Generation for Molecules

Molecular Graph Generation via Geometric Scattering

Generating Realistic 3D Molecules with an Equivariant Conditional Likelihood Model

Chemical-Reaction-Aware Molecule Representation Learning

Relative Molecule Self-Attention Transformer

Differentiable Scaffolding Tree for Molecule Optimization

MS2-Transformer: An End-to-End Model for MS/MS-assisted Molecule Identification

Graph Piece: Efficiently Generating High-Quality Molecular Graphs with Substructures

Pre-training Molecular Graph Representation with 3D Geometry

Spherical Message Passing for 3D Molecular Graphs

GraphEBM: Towards Permutation Invariant and Multi-Objective Molecular Graph Generation

Data-Efficient Graph Grammar Learning for Molecular Generation

Learning to Extend Molecular Scaffolds with Structural Motifs

Stepping Back to SMILES Transformers for Fast Molecular Representation Inference

An Autoregressive Flow Model for 3D Molecular Geometry Generation from Scratch

Learning 3D Representations of Molecular Chirality with Invariance to Bond Rotations

GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation

3D-Transformer: Molecular Representation with Transformer in 3D Space

Crystal Diffusion Variational Autoencoder for Periodic Material Generation

Knowledge Guided Geometric Editing for Unsupervised Drug Design

Spatial Graph Attention and Curiosity-driven Policy for Antiviral Drug Discovery

MoReL: Multi-omics Relational Learning

## [Molecular-GNN-NIPS 2021](#content) 

Molecules: 

GemNet: Universal Directional Graph Neural Networks for Molecules

Directional Message Passing on Molecular Graphs via Synthetic Coordinates

GeoMol: Torsional Geometric Generation of Molecular 3D Conformer Ensembles

Autobahn: Automorphism-based Graph Neural Nets

Predicting Molecular Conformation via Dynamic Graph Score Matching

Multi-Scale Representation Learning on Proteins

Molecular Property Prediction:

Motif-based Graph Self-Supervised Learning for Molecular Property Prediction

Property-aware Adaptive Relation Networks for Molecular Property Prediction

Retrosynthesis:

Towards understanding retrosynthesis by energy-based models

Learning Graph Models for Retrosynthesis Prediction




