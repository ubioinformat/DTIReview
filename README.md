# DTIReview
Drug-target interaction (DTI) prediction is a relevant but challenging task in the field of drug repurposing. Machine learning approaches, and more concretely graph-embedding-based methods, have drawn special attention as they can significantly reduce the associated costs and time commitment of traditional methodologies due to their high accuracy and robustness in DTI prediction tasks. However, structural differences among current transductive and inductive-based methods hinder fair benchmarking across DTI prediction models. Drug repurposing approaches requiring high-demanding additional information complicate their evaluation process and usability. Finally, current gold standard datasets are often limited in size, rising concerns when developing robust and reliable drug repurposing approaches. Therefore, there is a pressing need for evaluating state-of-the-art models to uncover pitfalls across ever-growing number of different methodologies that are being developed to discover drug-target interactions. In this work, we analyze several DTI prediction models, with especial emphasis on the employed datasets, the used graph embedding techniques, as well as the model evaluation. We identified the aforementioned key limitations and provide insights to address them. We hope that this work will serve as the underpinning for future fair benchmarking and robust DTI prediction model design.

| ![Review Figure](panel_fig1.png) |
|:--:|
|**A**. Datasets colored by origin of the data; number of nodes (drugs and proteins) for each dataset are shown in brackets. **B**. Models to be reviewed from different data, incl. publication year and feature extraction method.  **C**. Benchmarking of DTI prediction models. **Left**. Results obtained from the naive classifier based on *node2vec* followed by a 2-layer Neural Network (NN). **Right**. Evaluation of transductive vs. inductive methods. |
