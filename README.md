# When Sparse Meets Dense: Learning Advanced Graph Neural Networks with DGL-Sparse Package

**Presenters**: Minjie Wang, Hongzhi (Steve) Chen, Quan Gan, George Karypis and Zheng Zhang  
**When**: 2023-05-01 (Mon) 1:30 PM – 5:00 PM  
**Where**: AT&T Hotel and Conference Center - Classroom #101  
**Slack Channel**: [#webconf23-tutorial](https://deep-graph-library.slack.com/archives/C054W9UMQFP)  
**Provide Feedback**: [Survey](https://docs.google.com/forms/d/e/1FAIpQLSdTkFxJkQpE7TMQb6wYgviaAfC6Lf_pDsptaNzuFrP-AoR03w/viewform?usp=sf_link)  
![](./the_qrcode.jpg)

## Abstract

Learning from graph and relational data plays a major role in many applications including social network analysis, marketing, e-commerce, information retrieval, knowledge modeling, medical and biological sciences, engineering, and others. In the last few years, Graph Neural Networks (GNNs) have emerged as a promising new supervised learning framework capable of bringing the power of deep representation learning to graph and relational data. This ever-growing body of research has shown that GNNs achieve state-of-the-art performance for problems such as link prediction, fraud detection, target-ligand binding activity prediction, knowledge-graph completion, and product recommendations. The power of GNNs comes from its capability of collecting and aggregating information from local neighborhood using a paradigm called message passing. However, the message passing paradigm suffers from two notable issues. First, the learnt node representations quickly be- come indistinguishable with more layers, a phenomenon called oversmoothing. Second, generalizing it to more complex graphs such as hypergraphs is not straightforward. Therefore, many recent research work attempt to develop new GNNs beyond the message passing paradigm. Instead of defining a GNN in terms of node-wise and edge-wise operations, their models are typically defined as a series of operations over the sparse adjacency matrix of the input graph plus other dense tensor inputs like node embeddings. Pre- vious work have shown, both theoretically and empirically, that those new architectures can be very deep and also extends well to complex graphs.

This tutorial introduced DGL-Sparse, a new package of the pop- ular GNN framework Deep Graph Library (DGL). DGL- Sparse provides flexible and efficient sparse matrix operations for users to develop, train and apply advanced GNNs beyond the message pass- ing paradigm. The tutorial was organized as three sections. First, the presenters gave an overview of the recent development of GNNs and its applications. Second, they introduced the basic operations of the DGL-Sparse package with an interactive notebook tutorial followed by hands-on quiz to strengthen attendee’s understanding. In the last part, they walked-through an end-to-end example of a graph diffusion based GNN implemented in DGL-Sparse.

## Prerequisite

The attendees should have some experience with deep learning and have used Pytorch. Attendees should have experience with the various problems and techniques arising and used in graph learning and analysis, but it is not required.

## Agenda

| Time         | Topic                                               | Host    |
|--------------|-----------------------------------------------------|---------|
| 1:30 - 2:15  | Introduction of GNN and DGL                         | Minjie  |
| 2:15 - 3:15  | DGL Sparse basics & Graph Convolutional Network     | Steve   |
| 3:15 - 3:45  | Coffee Break                                        |         |
| 3:45 - 4:45  | Build Hypergraph Neural Networks with DGL Sparse    | Quan    |
| 4:45 - 5:00  | Wrap up                                             | Steve   |

## Tutorials

The tutorial set cover the basic usage of DGL's sparse matrix class and operators. You can begin with "Quickstart" and "Building a Graph Convolutional Network Using Sparse Matrices". The rest of the tutorials demonstrate the usage by end-to-end examples. All the tutorials are written in Jupyter Notebook and can be played on Google Colab.

- [Quickstart](https://colab.research.google.com/github/dmlc/dgl/blob/master/notebooks/sparse/quickstart.ipynb)
- [Building a Graph Convolutional Network Using Sparse Matrices](https://colab.research.google.com/github/dmlc/dgl/blob/master/notebooks/sparse/gcn.ipynb)
  - [More Exercise](https://colab.research.google.com/github/dglai/Thewebconf2023-Tutorial/blob/master/sign_exercise.ipynb)
- [Hypergraph Neural Networks](https://colab.research.google.com/github/dglai/Thewebconf2023-Tutorial/blob/main/Hypergraph%20neural%20networks.ipynb)
