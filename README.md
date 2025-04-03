# Adv-DPNP: Adversarial Robustness with Deep Positive Negative Prototypes

This repository contains the official implementation of our paper:
The code and experiment scripts will be available here shortly.

**Abstract:**

Deep neural networks demonstrate significant vulnerability to adversarial per-
turbations, posing risks for critical applications. Current adversarial training
methods predominantly focus on robustness against attacks without explicitly
leveraging geometric structures in the latent space, usually resulting in reduced
accuracy on the original clean data. To address these issues, we propose a novel
adversarial training framework named Adversarial Deep Positive-Negative Proto-
types (Adv-DPNP), which integrates disriminative prototype-based learning with
adversarial training. Adv-DPNP uses unified class prototypes serving dual roles as
classifier weights and robust anchors, enhancing both intra-class compactness and
inter-class separation in the latent space. Moreover, a novel dual-branch training
mechanism maintains stable prototypes by updating them exclusively with clean
data; while the feature extractor layers are learned using both clean and adver-
sarial data to remain invariant against adversarial perturbations. In addition, our
approach utilizes a composite loss function combining positive prototype align-
ment, negative prototype repulsion, and consistency regularization to further
enhance discrimination, adversarial robustness, and clean accuracy. Extensive
experiments conducted on standard benchmark datasets confirm the effectiveness
of Adv-DPNP compared to state-of-the-art methods, achieving higher clean accu-
racy and competitive robustness under adversarial perturbations and common
corruptions.


Stay tuned for updates!

If you have any questions or need additional information, please contact the authors listed in the paper.
