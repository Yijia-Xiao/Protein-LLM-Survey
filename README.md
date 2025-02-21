
# Large Language Models in Protein: A Comprehensive Survey

[![Awesome](https://awesome.re/badge.svg)](https://github.com/lupantech/dl4math) 
[![Survey](https://img.shields.io/badge/Survey-ProteinLLM-blue)](https://github.com/Yijia-Xiao/Protein-LLM-Survey) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## LLM Methods for Protein Understanding and Prediction

### Protein Sequence Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [Unified rational protein engineering with sequence-based deep representation learning](https://www.nature.com/articles/s41592-019-0598-1 ) | *Nature Methods, 2019* |  |
| [Learning protein sequence embeddings using information from structure](https://arxiv.org/abs/1902.08661) | *arXiv preprint, 2019* | [Code](https://github.com/tbepler/protein-sequence-embedding-iclr2019) |
| [Mutation effect estimation on protein–protein interactions using deep contextualized representation learning](https://doi.org/10.1093/nargab/lqaa015) | *NAR Genomics and Bioinformatics, 2020* | [Code](https://github.com/guangyu-zhou/MuPIPR) |
| [Prottrans: Toward understanding the language of life through self-supervised learning](https://ieeexplore.ieee.org/document/9477085) | *IEEE Transactions on Pattern Analysis and Machine Intelligence, 2021* | [Code](https://github.com/agemagician/ProtTrans) |
| [Modeling protein using large-scale pretrain language model](https://arxiv.org/abs/2108.07435) | *arXiv preprint, 2021* | [Code](https://github.com/THUDM/ProteinLM) |
| [Single-sequence protein structure prediction using a language model and deep learning](https://www.nature.com/articles/s41587-022-01432-w) | *Nature Biotechnology, 2022* | [Code](https://github.com/aqlaboratory/rgn2) |
| [Bertology meets biology: Interpreting attention in protein language models](https://arxiv.org/abs/2006.15222) | *arXiv preprint, 2020* | [Code](https://github.com/salesforce/provis) |
| [Learning the language of viral evolution and escape](https://science.sciencemag.org/content/371/6526/284) | *Science, 2021* | [Code](https://github.com/brianhie/viral-mutation) |
| [TCR-BERT: learning the grammar of T-cell receptors for flexible antigen-xbinding analyses](https://www.biorxiv.org/content/10.1101/2021.11.18.469186v1) | *bioRxiv, 2021* | [Code](https://github.com/wukevin/tcr-bert) |
| [xTrimoPGLM: Unified 100B-Scale Pre-trained Transformer for Deciphering the Language of Protein](https://arxiv.org/abs/2401.06199) | *arXiv e-prints, 2024* | [Model and Data](https://huggingface.co/proteinglm) |
| [Turnover number predictions for kinetically uncharacterized enzymes using machine and deep learning](https://www.nature.com/articles/s41467-023-39840-4) | *Nature Communications, 2023* | [Code](https://github.com/AlexanderKroll/kcat_prediction) |
| [Enzyme function prediction using contrastive learning](https://www.science.org/doi/10.1126/science.adf2465) | *Science, 2023* | [Code](https://github.com/tttianhao/CLEAN) |




### Evolutionary Scale Modeling (ESM) Series

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences](https://doi.org/10.1073/pnas.2016239118) | *PNAS, 2021* | [Code](https://github.com/facebookresearch/esm) |
| [Language models enable zero-shot prediction of the effects of mutations on protein function](https://dl.acm.org/doi/10.5555/3540261.3542504) | *Advances in Neural Information Processing Systems, 2021* | [Code](https://github.com/facebookresearch/esm) |
| [Learning inverse folding from millions of predicted structures](https://proceedings.mlr.press/v162/hsu22a.html) | *ICML, 2022* | [Code](https://github.com/facebookresearch/esm) |
| [Evolutionary-scale prediction of atomic-level protein structure with a language model](https://www.science.org/doi/10.1126/science.ade2574) | *Science, 2023* | [Code](https://github.com/facebookresearch/esm) |
| [Simulating 500 million years of evolution with a language model](https://www.biorxiv.org/content/10.1101/2024.07.01.600583v1) | *bioRxiv, 2024* | [Code](https://github.com/evolutionaryscale/esm)|



### MSA-based Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [MSA transformer](https://proceedings.mlr.press/v139/rao21a.html) | *ICML, 2021* | [Code](https://github.com/rmrao/msa-transformer) |
| [Tranception: protein fitness prediction with autoregressive transformers and inference-time retrieval](https://proceedings.mlr.press/v162/notin22a/notin22a.pdf) | *ICML, 2022* | [Code](https://github.com/OATML-Markslab/Tranception) |
| [Leveraging protein language models for accurate multiple sequence alignments](https://genome.cshlp.org/content/early/2023/07/06/gr.277675.123.full.pdf) | *Genome Research, 2023* | [Code](https://github.com/clairemcwhite/vcmsa) |
| [PoET: A generative model of protein families as sequences-of-sequences](https://papers.nips.cc/paper_files/paper/2023/file/f4366126eba252699b280e8f93c0ab2f-Paper-Conference.pdf) | *Neurips, 2023* | [Code](https://github.com/OpenProteinAI/PoET) |
| [Deep transfer learning for inter-chain contact predictions of transmembrane protein complexes](https://www.nature.com/articles/s41467-023-40426-3) | * Nature Communications, 2023* | [Code](https://github.com/jianlin-cheng/DeepComplex) |


### Structure-Integrated Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [A systematic study of joint representation learning on protein sequences and structures](https://arxiv.org/abs/2303.06275) | *arXiv preprint, 2023* | [Code](https://github.com/DeepGraphLearning/ESM-GearNet) |
| [Saprot: Protein language modeling with structure-aware vocabulary](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v5) | *bioRxiv, 2023* | [Code](https://github.com/westlake-repl/SaProt) |
| [Simple, Efficient and Scalable Structure-aware Adapter Boosts Protein Language Models](https://arxiv.org/abs/2404.14850) | *arXiv preprint, 2024* | [Code](https://github.com/tyang816/SES-Adapter) |
| [Multi-level Protein Structure Pre-training via Prompt Learning](https://openreview.net/forum?id=XGagtiJ8XC) | *ICLR, 2023* | [Code](https://github.com/HICAI-ZJU/PromptProtein) |
| [Structure-informed protein language models are robust predictors for variant effects](https://link.springer.com/article/10.1007/s00439-024-02695-w) | *Human Genetics, 2024* |  |
| [Integration of pre-trained protein language models into geometric deep learning networks](https://www.nature.com/articles/s42003-023-05133-1) | *Communications Biology, 2023* | [Code](https://github.com/smiles724/GGNN_Meets_PLM?tab=readme-ov-file) |
| [Structure-Informed Protein Language Model](https://arxiv.org/abs/2402.05856) | *arXiv preprint, 2024* | [Code](https://github.com/DeepGraphLearning/esm-s) |
| [S-PLM: Structure-Aware Protein Language Model via Contrastive Learning Between Sequence and Structure](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202404212) | *Advanced Science, 2024* | [Code](https://github.com/duolinwang/S-PLM) |
| [CCPL: Cross-modal Contrastive Protein Learning](https://www.google.com/search?client=safari&rls=en&q=Ccpl%3A+Cross-modal+contrastive+protein+learning&ie=UTF-8&oe=UTF-8) | *Pattern Recognition, 2024* | |



### Knowledge-Enhanced Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [OntoProtein: Protein Pretraining With Gene Ontology Embedding](https://arxiv.org/abs/2201.11147) | *ICLR, 2022* | [Code](https://github.com/zjunlp/OntoProtein) |
| [ProteinCLIP: enhancing protein language models with natural language](https://www.biorxiv.org/content/10.1101/2024.05.14.594226v1) | *bioRxiv, 2024* | [Code](https://github.com/wukevin/proteinclip) |
| [ProteinBERT: a universal deep-learning model of protein sequence and function](https://academic.oup.com/bioinformatics/article/38/8/2102/6502274) | *Bioinformatics, 2022* | [Code](https://github.com/nadavbra/protein_bert) |
| [Protein Representation Learning via Knowledge Enhanced Primary Structure Reasoning](https://openreview.net/forum?id=VbCMhg7MRmj) | *ICLR, 2023* | [Code](https://github.com/RL4M/KeAP) |
| [MolBind: Multimodal Alignment of Language, Molecules, and Proteins](https://arxiv.org/abs/2403.08167) | *arXiv preprint, 2024* |  |


### Protein Description and Annotation Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [Prot2text: Multimodal protein’s function generation with gnns and transformers](https://arxiv.org/abs/2307.14367) | *AAAI, 2024* | [Code](https://github.com/hadi-abdine/Prot2Text) |
| [Protranslator: zero-shot protein function prediction using textual description](https://link.springer.com/chapter/10.1007/978-3-031-04749-7_17) | *International Conference on Research in Computational Molecular Biology, 2022* | [Code](https://github.com/HanwenXuTHU/ProTranslator) |
| [Multilingual translation for zero-shot biomedical classification using BioTranslator](https://www.nature.com/articles/s41467-023-36476-2) | *Nature Communications, 2023* | [Code](https://github.com/HanwenXuTHU/BioTranslatorProject) |
| [Biot5: Enriching cross-modal integration in biology with chemical knowledge and natural language associations](https://aclanthology.org/2023.emnlp-main.70/) | *EMNLP, 2023* | [Code](https://github.com/QizhiPei/BioT5?tab=readme-ov-file) |
| [BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning](https://aclanthology.org/2024.findings-acl.71/) | *ACL, 2024* | [Code](https://github.com/QizhiPei/BioT5?tab=readme-ov-file)|
| [ProtST: Multi-Modality Learning of Protein Sequences and Biomedical Texts](https://proceedings.mlr.press/v202/xu23t/xu23t.pdf) | *ICML, 2023* | [Code](https://github.com/DeepGraphLearning/ProtST) |
| [ProtChatGPT: Towards Understanding Proteins with Large Language Models](https://arxiv.org/abs/2402.09649) | *arXiv, 2024* |  |
| [ProteinChat: Towards Achieving ChatGPT-Like Functionalities on Protein 3D Structures](https://www.techrxiv.org/users/691610/articles/682177-proteinchat-towards-achieving-chatgpt-like-functionalities-on-protein-3d-structures) | *TechRxiv, 2023* |  |


## LLM Methods for Protein Engineering and Generation

### Generative Models (Protein Decoder)

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [Large language models generate functional protein sequences across diverse families](https://www.nature.com/articles/s41587-022-01618-2) | *Nature Biotechnology, 2023* | [Code](https://github.com/salesforce/progen) |
| [ProtGPT2: Deep Unsupervised Language Model for Protein Design](https://www.nature.com/articles/s41467-022-32007-7) | *Nature Communications, 2022* | [Code](https://huggingface.co/nferruz/ProtGPT2) |
| [ProGen2: Exploring the Boundaries of Protein Language Models](https://www.cell.com/cell-systems/fulltext/S2405-4712(23)00272-7) | *Cell Systems, 2023* | [Code](https://github.com/enijkamp/progen2) |
| [IgLM: Infilling Language Modeling for Antibody Sequence Design](https://www.cell.com/cell-systems/fulltext/S2405-4712(23)00271-5) | *Cell Systems, 2023* | [Code](https://github.com/Graylab/IgLM) |
| [PALM-H3: Targeted Antibody Generation for SARS-CoV-2](https://www.nature.com/articles/s41467-024-50903-y) | *Nature Communications, 2024* | [Code](https://github.com/TencentAILabHealthcare/PALM) |
| [Integrating protein language models and automatic biofoundry for enhanced protein evolution](https://www.nature.com/articles/s41467-025-56751-8) | *Nature Communications, 2025* | [Code](https://github.com/HICAI-ZJU/PLMeAE_Project) |

### Protein Encoder Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [ProtST: Multi-modality Learning of Protein Sequences and Biomedical Texts](https://arxiv.org/abs/2301.12040) | *ICML 2023* | [Code](https://github.com/DeepGraphLearning/ProtST) |
| [ProteinBERT: a universal deep-learning model of protein sequence and function](https://academic.oup.com/bioinformatics/article/38/8/2102/6502274) | *Bioinformatics, 2022* | [Code](https://github.com/nadavbra/protein_bert) |
| [Bertology meets biology: Interpreting attention in protein language models](https://arxiv.org/abs/2006.15222) | *arXiv preprint, 2020* | [Code](https://github.com/salesforce/provis) |
| [Prottrans: Toward understanding the language of life through self-supervised learning](https://ieeexplore.ieee.org/document/9477085) | *IEEE Transactions on Pattern Analysis and Machine Intelligence, 2021* | [Code](https://github.com/agemagician/ProtTrans) |
| [Modeling protein using large-scale pretrain language model](https://arxiv.org/abs/2108.07435) | *arXiv preprint, 2021* | [Code](https://github.com/THUDM/ProteinLM) |

### Encoder-Decoder Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [ProstT5: Bilingual Modeling of Protein Sequence and Structure](https://www.biorxiv.org/content/10.1101/2023.07.23.550085v2) | *bioRxiv, 2023* | [Code](https://github.com/mheinzinger/ProstT5) |
| [Fold2Seq: A Joint Sequence–Fold Embedding-based Generative Model for Protein Design](https://proceedings.mlr.press/v139/cao21a.html) | *ICML 2021* | [Code](https://github.com/Shen-Lab/Fold2Seq-icml2021) |
| [Ankh: Optimized Protein Language Model for Efficient Generation](https://arxiv.org/abs/2301.06568) | *arXiv, 2023* | [Code](https://github.com/agemagician/Ankh) |

### Interactive and Multimodal Models

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [ProteinGPT: Multimodal LLM for Protein Property Prediction and Structure Understanding](https://arxiv.org/abs/2408.11363) | *arXiv, 2024* | [Code](https://huggingface.co/spaces/AI-BIO/ProteinGPT-Llama3) |
| [ProteinChat: ChatGPT-like Functionalities on Protein 3D Structures](https://www.techrxiv.org/users/691610/articles/682177-proteinchat-towards-achieving-chatgpt-like-functionalities-on-protein-3d-structures) | *Authorea Preprints, 2023* | [Code](GITHUB_LINK) |
| [ProtChatGPT: Towards Understanding Proteins with Large Language Models](https://arxiv.org/abs/2402.09649) | *arXiv, 2024* | [Code](GITHUB_LINK) |
| [ProteinDT: A Text-guided Protein Design Framework](https://arxiv.org/abs/2302.04611) | *arXiv, 2023* | [Code](https://github.com/chao1224/ProteinDT) |


## Traditional Experimental Methods for Protein
### X-ray Crystallography

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [Artificial intelligence to solve the X-ray crystallography phase problem: a case study report](https://www.biorxiv.org/content/10.1101/2021.12.14.472726v1.full) | *BiorXiv, 2021* | N/A |

### Nuclear Magnetic Resonance (NMR) Spectroscopy

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [FID-Net: A versatile deep neural network architecture for NMR spectral reconstruction and virtual decoupling](https://link.springer.com/article/10.1007/s10858-021-00366-w) | *Journal of Biomolecular NMR, 2021* | [Code](https://github.com/gogulan-k/FID-Net) |
| [Accelerated Nuclear Magnetic Resonance Spectroscopy with Deep Learning](https://arxiv.org/abs/1904.05168) | *Angewandte Chemie, 2020* | [Code](https://github.com/PiotrKlukowski/ARTINA) |


### Cryo-EM

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [CryoDRGN: reconstruction of heterogeneous cryo-EM structures using neural networks](https://www.nature.com/articles/s41592-020-01049-4) | *Nature Methods, 2021* | [Code](https://www.nature.com/articles/s41592-020-01049-4) |
| [CryoGAN: A New Reconstruction Paradigm for Single-Particle Cryo-EM Via Deep Adversarial Learning](https://ieeexplore.ieee.org/document/9483649) | *IEEE Transactions on Computational Imaging , 2021* | [Code](https://ieeexplore.ieee.org/document/9483649) |
| [Deep learning-based mixed-dimensional Gaussian mixture model for characterizing variability in cryo-EM](https://www.nature.com/articles/s41592-021-01220-5) | *Nature Methods, 2021* | [Code](https://github.com/phonchi/Computational-CryoEM) |
| [3dflex: determining structure and motion of flexible proteins from cryo-em](https://www.nature.com/articles/s41592-023-01853-8) | *Nature Methods, 2023* | [Code](https://www.nature.com/articles/s41592-023-01853-8) |
| [Cryostar: leveraging structural priors and constraints for cryo-em heterogeneous reconstruction](https://www.nature.com/articles/s41592-024-02486-1) | *Nature Methods, 2024* | [Code](https://www.nature.com/articles/s41592-024-02486-1) |


## Protein Datasets: Training Data and Benchmarks
### Pretraining Dataset
| Dataset Name  | Resources |
|-------|:---------:|
| UniProtKB/Swiss-Prot |  [link](https://www.uniprot.org/uniprotkb) |
| UniProtKB/TrEMBL |  [link](https://www.uniprot.org/uniprotkb)   |
| UniRef Clusters  |  [link](https://www.uniprot.org/uniref/) |
| Pfam | [link](https://www.ebi.ac.uk/interpro/entry/pfam/#table) |
| PDB | [link](https://www.rcsb.org/)|
| BFD | [link](https://bfd.mmseqs.com/) |
| UniParc | [link](https://www.uniprot.org/help/uniparc) |
| PIR | [link](https://proteininformationresource.org/) |
| AlphaFoldDB | [link](https://alphafold.ebi.ac.uk/) |
### Benchmark
| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [Critical assessment of methods of protein structure prediction (CASP)—Round XV](https://onlinelibrary.wiley.com/doi/pdf/10.1002/prot.26617) | *Proteins: Structure, Function, and Bioinformatics* | [link](https://predictioncenter.org/) |
| [ProteinGym: Large-Scale Benchmarks for Protein Fitness Prediction and Design](https://proceedings.neurips.cc/paper_files/paper/2023/file/cac723e5ff29f65e3fcbb0739ae91bee-Paper-Datasets_and_Benchmarks.pdf) | *Neurips, 2023* | [code](https://github.com/OATML-Markslab/ProteinGym) |
| [Evaluating protein transfer learning with tape](https://proceedings.neurips.cc/paper_files/paper/2019/file/37f65c068b7723cd7809ee2d31d7861c-Paper.pdf)| *Neurips, 2019* | [code](https://github.com/songlab-cal/tape) |
| [CATH–a hierarchic classification of protein domain structures](https://www.cell.com/structure/fulltext/S0969-2126(97)00260-8?cc\u003dy=)| *Structure, 1997* | [link](https://www.cathdb.info/) |
| [Peer: a comprehensive and multi-task benchmark for protein sequence understanding](https://proceedings.neurips.cc/paper_files/paper/2022/file/e467582d42d9c13fa9603df16f31de6d-Paper-Datasets_and_Benchmarks.pdf) | *Neurips, 2022* | [code](https://github.com/DeepGraphLearning/PEER_Benchmark) |
| [ExplorEnz: the primary source of the IUBMB enzyme list](https://academic.oup.com/nar/article-pdf/37/suppl_1/D593/3205990/gkn582.pdf) | *Nucleic acids research, 2009* | [link](https://www.enzyme-database.org/) |
| [HIPPIE: Integrating protein interaction networks with experiment based quality scores](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0031826&type=printable) | *PloS One, 2012* | [link](https://cbdm-01.zdv.uni-mainz.de/~mschaefer/hippie/) |
| [A Fine-tuning Dataset and Benchmark for Large Language Models for Protein Understanding](https://arxiv.org/pdf/2406.05540) | *arXiv, 2019* | [code](https://github.com/tsynbio/proteinlmdataset) |

### Example Table

| Paper | Published in | Resources |
|-------|:------------:|:---------:|
| [ProteinGPT: Multimodal LLM for Protein Property Prediction and Structure Understanding](https://arxiv.org/abs/2408.11363) | *arXiv, 2024* | [Code](GITHUB_LINK) |
| [ProteinChat: ChatGPT-like Functionalities on Protein 3D Structures](https://www.techrxiv.org/users/691610/articles/682177-proteinchat-towards-achieving-chatgpt-like-functionalities-on-protein-3d-structures) | *Authorea Preprints, 2023* | [Code](GITHUB_LINK) |

