# Transformer-paper-collection

## Unsupervised Domain Adaptation:
- **Exploiting Both Domain-specific and Invariant Knowledge via a Win-win Transformer for Unsupervised Domain Adaptation，Tsinghua，DeepAI Arxiv**
    Deit as baseline, two class token in deit were used on source/target domain respectively.
    
## Normalisation
- **PowerNorm: Rethinking Batch Normalization in Transformers, UC berkeley** calculate quadratic mean as normalisation
- **Test-Time Personalization with a Transformer for Human Pose Estimation, NIPS2021** Raise a new self-supervised task for Human pose estimation. Having two poses images of the same person, extract keypoint from one image and features from another images, regenerate the ground truth and compare the reconstruction loss. During test time, redo the self-supervised task and tune the model weight. 

