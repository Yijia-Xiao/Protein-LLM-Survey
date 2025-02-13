# Large Language Models in Protein: A Comprehensive Survey

[![Awesome](https://awesome.re/badge.svg)](https://github.com/lupantech/dl4math) 
[![Survey](https://img.shields.io/badge/Survey-ProteinLLM-blue)](https://github.com/Yijia-Xiao/Protein-LLM-Survey) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## LLM Methods for Protein Engineering and Generation

### Generative Models (Protein Decoder)
- **Large language models generate functional protein sequences across diverse families**  
  Treats protein engineering as an unsupervised sequence generation task, conditioning on annotations such as molecular function or taxonomy.  
  *Nature Biotechnology, 2023*  [[paper](https://www.nature.com/articles/s41587-022-01618-2)]
- **ProtGPT2: Deep Unsupervised Language Model for Protein Design**  
  Generates de novo protein sequences with natural amino acid compositions via autoregressive modeling, exploring uncharted areas of the protein sequence space.  
  *Nature Communications, 2022*  [[paper](https://www.nature.com/articles/s41467-022-32007-7)]
- **ProGen2: Exploring the Boundaries of Protein Language Models**  
  An extended version of ProGen with a larger model (6.4B parameters) and training dataset, capable of predicting protein fitness without extra fine-tuning.  
  *Cell Systems, 2023*  [[paper](https://www.cell.com/cell-systems/fulltext/S2405-4712(23)00272-7)]
- **IgLM: Infilling Language Modeling for Antibody Sequence Design**  
  Specializes in antibody generation by conditioning on chain type and species, with the ability to generate infilled residue spans at indicated positions.  
  *Cell Systems, 2023*  [[paper](https://www.cell.com/cell-systems/fulltext/S2405-4712(23)00271-5)]
- **PALM-H3: Targeted Antibody Generation for SARS-CoV-2**  
  Focuses on generating antibodies specifically targeted for SARS-CoV-2, demonstrating the potential of decoder-based models in designing focused therapeutics.  
  *Nature Communications, 2024*  [[paper](https://www.nature.com/articles/s41467-024-50903-y)]


### Protein Encoder Models
- **ProtST: Multi-modality Learning of Protein Sequences and Biomedical Texts**  
  Leverages both protein (e.g. ESM, ProtBert) and biomedical (PubMedBERT) language models to jointly learn from protein sequences and their natural-language annotations.  
  *ICML 2023*  [[paper](https://arxiv.org/abs/2301.12040)]
- **ProteinBERT: a universal deep-learning model of protein sequence and function**  
- **Bertology meets biology: Interpreting attention in protein language models**  
  *arXiv preprint, 2020*  [[paper](https://arxiv.org/abs/2006.15222)]
- **Prottrans: Toward understanding the language of life through self-supervised learning**  
  *IEEE Transactions on Pattern Analysis and Machine Intelligence, 2021*  [[paper](https://ieeexplore.ieee.org/document/9477085)]
- **Modeling protein using large-scale pretrain language model**  
  *arXiv preprint, 2021*  [[paper](https://arxiv.org/abs/2108.07435)]


### Encoder-Decoder Models
- **ProstT5: Bilingual Modeling of Protein Sequence and Structure**  
  Simultaneously extracts features from both the 1D protein sequence and its 3D structure using a T5-based architecture combined with ProtT5 improvements, enabling tasks such as remote homology detection and structure–sequence translation.  
  *bioRxiv, 2023*  [[paper](https://www.biorxiv.org/content/10.1101/2023.07.23.550085v2)]
- **Fold2Seq: A Joint Sequence–Fold Embedding-based Generative Model for Protein Design**  
  Learns structure–sequence relationships using a multi-step training framework that includes fold-to-sequence reconstruction and fold classification.  
  *ICML 2021*  [[paper](https://proceedings.mlr.press/v139/cao21a.html)]
- **Ankh: Optimized Protein Language Model for Efficient Generation**  
  An encoder-decoder model designed for efficiency and optimization with fewer parameters, focusing on general protein generation rather than explicit structure–sequence translation.  
  *arXiv, 2023*  [[paper](https://arxiv.org/abs/2301.06568)]

### Interactive and Multimodal Models
- **ProtChatGPT: Towards Understanding Proteins with Large Language Models**  
  Provides an interactive interface where users can upload protein data and query properties; the system aligns protein embeddings with a language model to generate insightful responses.  
  *arXiv, 2024*  [[paper](https://arxiv.org/abs/2402.09649)]
- **ProteinChat: ChatGPT-like Functionalities on Protein 3D Structures**  
  Accepts protein 3D structures as input to allow users to query detailed properties and functional insights.  
  *Authorea Preprints, 2023*  [[paper](https://www.techrxiv.org/users/691610/articles/682177-proteinchat-towards-achieving-chatgpt-like-functionalities-on-protein-3d-structures)]
- **ProteinGPT: Multimodal LLM for Protein Property Prediction and Structure Understanding**  
  Integrates protein data with natural language inputs for enhanced alignment and conversation-based inquiry.  
  *arXiv, 2024*  [[paper](https://arxiv.org/abs/2408.11363)]
- **ProteinDT: A Text-guided Protein Design Framework**  
  Robustly integrates textual protein knowledge with sequence-based generative modeling via contrastive alignment and a facilitator module, enabling zero-shot text-to-protein generation and editing.  
  *arXiv, 2023*  [[paper](https://arxiv.org/abs/2302.04611)]


## LLM Methods for Protein Understanding and Prediction

### Protein Sequence Models
- **Learning protein sequence embeddings using information from structure**  
  *arXiv preprint, 2019*  [[paper](https://arxiv.org/abs/1902.08661)]
- **Mutation effect estimation on protein–protein interactions using deep contextualized representation learning**  
  *NAR Genomics and Bioinformatics, 2020*  [[paper](https://doi.org/10.1093/nargab/lqaa015)]
- **Prottrans: Toward understanding the language of life through self-supervised learning**  
  *IEEE Transactions on Pattern Analysis and Machine Intelligence, 2021*  [[paper](https://ieeexplore.ieee.org/document/9477085)]
- **Modeling protein using large-scale pretrain language model**  
  *arXiv preprint, 2021*  [[paper](https://arxiv.org/abs/2108.07435)]
- **Single-sequence protein structure prediction using a language model and deep learning**  
  *Nature Biotechnology, 2022*  [[paper](https://www.nature.com/articles/s41587-022-01432-w)]
- **ProteinBERT: a universal deep-learning model of protein sequence and function**  
  *Bioinformatics, 2022*  [[paper](https://academic.oup.com/bioinformatics/article/38/8/2102/6502274)]
- **Prollama: A protein large language model for multi-task protein language processing**  
  *arXiv e-prints, 2024*  [[paper](https://arxiv.org/abs/2402.16445)]
- **Bertology meets biology: Interpreting attention in protein language models**  
  *arXiv preprint, 2020*  [[paper](https://arxiv.org/abs/2006.15222)]
- **Learning the language of viral evolution and escape**  
  *Science, 2021*  [[paper](https://science.sciencemag.org/content/371/6526/284)]


### Evolutionary Scale Modeling (ESM) Series
- **Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences**  
  *PNAS, 2021*  [[paper](https://doi.org/10.1073/pnas.2016239118)]
- **Language models enable zero-shot prediction of the effects of mutations on protein function**  
  *Advances in Neural Information Processing Systems, 2021*  [[paper](https://dl.acm.org/doi/10.5555/3540261.3542504)]
- **MSA transformer**  
  *ICML, 2021*  [[paper](https://proceedings.mlr.press/v139/rao21a.html)]
- **Axial attention in multidimensional transformers**  
  *arXiv preprint, 2019*  [[paper](https://arxiv.org/abs/1912.12180)]
- **Generating long sequences with sparse transformers**  
  *arXiv preprint, 2019*  [[paper](https://arxiv.org/abs/1904.10509)]
- **Tranception: protein fitness prediction with autoregressive transformers and inference-time retrieval**  
  *ICML, 2022*  [[paper](https://proceedings.mlr.press/v162/notin22a/notin22a.pdf)]
- **Highly accurate protein structure prediction with AlphaFold**  
  *Nature, 2021*  [[paper](https://www.nature.com/articles/s41586-021-03819-2)]
- **Learning inverse folding from millions of predicted structures**  
  *ICML, 2022*  [[paper](https://proceedings.mlr.press/v162/hsu22a.html)]
- **Evolutionary-scale prediction of atomic-level protein structure with a language model**  
  *Science, 2023*  [[paper](https://www.science.org/doi/10.1126/science.ade2574)]

### MSA-based Models
- **MSA transformer**  
  *ICML, 2021*  [[paper](https://proceedings.mlr.press/v139/rao21a.html)]
- **Tranception: protein fitness prediction with autoregressive transformers and inference-time retrieval**  
  *ICML, 2022*  [[paper](https://proceedings.mlr.press/v162/notin22a/notin22a.pdf)]

### Cross Modality Models
- **Prot2text: Multimodal protein’s function generation with gnns and transformers**  
  *AAAI, 2024*  [[paper](https://arxiv.org/abs/2307.14367)]
- **Protranslator: zero-shot protein function prediction using textual description**  
  *International Conference on Research in Computational Molecular Biology, 2022*  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-04749-7_17)]
- **Multilingual translation for zero-shot biomedical classification using BioTranslator**  
  *Nature Communications, 2023*  [[paper](https://www.nature.com/articles/s41467-023-36476-2)]
- **Biot5: Enriching cross-modal integration in biology with chemical knowledge and natural language associations**  
  *arXiv preprint, 2023*  [[paper](https://arxiv.org/abs/2310.07276)]

### Structure-Integrated Models
- **A systematic study of joint representation learning on protein sequences and structures**  
  *arXiv preprint, 2023*  [[paper](https://arxiv.org/abs/2303.06275)]
- **Protein representation learning by geometric structure pretraining**  
  *arXiv preprint, 2022*  [[paper](https://arxiv.org/abs/2203.06125)]
- **Continuous-discrete convolution for geometry-sequence modeling in proteins**  
  *ICLR, 2022*  [[paper](https://openreview.net/forum?id=P5Z-Zl9XJ7)]
- **Saprot: Protein language modeling with structure-aware vocabulary**  
  *bioRxiv, 2023*  [[paper](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v5)]
- **Foldseek: fast and accurate protein structure search**  
  *bioRxiv, 2022*  [[paper](https://www.biorxiv.org/content/10.1101/2022.02.07.479398v5)]

### Knowledge-Enhanced Models
- **OntoProtein: Protein Pretraining With Gene Ontology Embedding**  
  *ICLR, 2022*  [[paper](https://arxiv.org/abs/2201.11147)]
- **ProteinCLIP: enhancing protein language models with natural language**  
  *bioRxiv, 2024*  [[paper](https://www.biorxiv.org/content/10.1101/2024.05.14.594226v1)]

  ---
