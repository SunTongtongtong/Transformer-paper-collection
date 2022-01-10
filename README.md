# Vision-Transformer-paper-collectionCancel changes

## Unsupervised Domain Adaptation:
- **Exploiting Both Domain-specific and Invariant Knowledge via a Win-win Transformer for Unsupervised Domain Adaptation，Tsinghua，DeepAI Arxiv**
    Deit as baseline, two class token in deit were used on source/target domain respectively.
- **Delving Deep into the Generalization of Vision Transformers under Distribution Shifts**
    
## Normalisation
- **PowerNorm: Rethinking Batch Normalization in Transformers, UC berkeley** calculate quadratic mean as normalisation
- **Test-Time Personalization with a Transformer for Human Pose Estimation, NIPS2021** Raise a new self-supervised task for Human pose estimation. Having two poses images of the same person, extract keypoint from one image and features from another images, regenerate the ground truth and compare the reconstruction loss. During test time, redo the self-supervised task and tune the model weight. 

## Generalization
**Delving Deep into the Generalization of Vision Transformers under Distribution Shifts** Define four kinds of shift for images and three generalization methods combined with vision transformer, including adversarial learning, information theory, and self-supervised learning. The key idea is based on entropy maximization and minimization. 
