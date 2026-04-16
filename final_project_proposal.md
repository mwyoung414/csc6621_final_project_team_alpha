## Final Project Proposal

Proteins are made of sequences of amino acids (ex. first 10 sequnces of Insulin (G-I-V-E-Q-C-C-T-S-I)(Chain A) - Insulin)
This sequence defines a protein's structure and therefore it's function, protein structure prediction, with this knowledge the procress
of creating new drugs can be increased, more knowledge on the workings of diseases, and bioengineering applications. 

There are two datasets for potential use, ProteinNet and SidechainNet, an extension of ProteinNet that contains all it's data but adds also the angles of the 'Sidechains' which stick off the backbone of protein which is it's main structure, which also can tell what the protein will do.

I've added both datasets because ProteinNet less features than SidechainNet, if SidechainNet is too computational expensive, downgrade to ProteinNet

## Dataset

[ProteinNet](https://github.com/aqlaboratory/proteinnet)

[ProteinNet Research Paper](https://link.springer.com/article/10.1186/s12859-019-2932-0)

[SidechainNet](https://github.com/jonathanking/sidechainnet)

[SidechainNet Research Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC8492522/)

## Models

- BiLSTM (Bi-directional Long Short Term Memory)
- BiGRU (Bi-directional Gated Recurrent Unit)
- LLM (Bidrectional Encoder) ([ES25](https://huggingface.co/docs/transformers/en/model_doc/esm))