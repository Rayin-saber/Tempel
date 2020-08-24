#Tempel: Time-series Mutation Prediction of Influenza A Viruses via Attention-based Recurrent Neural Networks

Motivation: Influenza viruses are persistently threatening public health, causing annual epidemics, and sporadic pandemics. The evolution of influenza viruses remains to be the main obstacle in the effectiveness of antiviral treatments due to rapid mutations. The goal of this work is to predict whether mutations are likely to occur in the next flu season using historical glycoprotein hemagglutinin (HA) sequence data. One of the major challenges is to model the temporality and dimensionality of sequential influenza strains and to interpret the prediction results.

Results: In this paper, we propose an efficient and robust time-series mutation prediction model Tempel for the mutation prediction of influenza A viruses. We first construct the sequential training samples with splittings and embeddings. By employing recurrent neural networks (RNNs) with attention mechanisms, Tempel is capable of considering the historical residue information. Attention mechanisms are being increasingly used to improve the performance of mutation prediction by selectively focusing on the parts of the residues. A framework is established based on Tempel that enables us to predict the mutations at any specific residue site. Experimental results on three influenza datasets show that Tempel can significantly enhance the predictive performance compared with widely used approaches and provide novel insights into the dynamics of viral mutation and evolution.

Contact: yinr0002@e.ntu.edu.sg

Supplementary information: The datasets, source code and supplementary documents are available at: https://drive.google.com/open?id=15WULR5__6k47iRotRPl3H7ghi3RpeNXH

Citation: Yin R, Luusua E, Dabrowski J, et al. Tempel: time-series mutation prediction of influenza A viruses via attention-based recurrent neural networks[J]. Bioinformatics, 2020, 36(9): 2697-2704.
