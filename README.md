# Summarizing Radiology Reports using Neural Sequence to Sequence Learning


# Model -
  **Neural Sequence to Sequence Learning**
    
    An encoder decoder GRU-based architecture supplemented by an additional Attention based mechanism

# Motivation -
    1. Redundancy
    2. Factor of Human-Error
    3. A time consuming task
Refer to [this](https://www.ncbi.nlm.nih.gov/pubmed/22195100) report for additional information

# Reference
The idea is based on [this](https://arxiv.org/abs/1809.04698) paper 
    
# Dataset

A compilation of approx. 2700 unique reports collected from the [Open-i National Library of Medicine -  National Institues of Health](https://openi.nlm.nih.gov/)
    
# Vanilla Encoder-Decoder with GRU

    Validation split => 0.1
    Epochs => 30 
    Optimizer => Adam

![alt text](https://github.com/abhishekr7/report-summarizer/blob/master/IMG_20190404_231206.png)

