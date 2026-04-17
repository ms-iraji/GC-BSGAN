#  Stronger adversarial examples: A novel adversarial direction using Gradient consistency for bad semi supervised GANs

#  Authors
Mohammad Saber Iraji 
Department of Computer Engineering and Information Technology, Payame Noor University, Tehran, Iran 
# Email:  iraji.ms@pnu.ac.ir 

#  Abstract
Adversarial examples, particularly those generated through gradient-based methods, have revealed fundamental vulnerabilities in deep neural networks while also providing opportunities to improve model robustness. These perturbations exploit the gradients of the loss function to manipulate model predictions, often leading to incorrect classifications or unstable decision boundaries. While such approaches have been widely explored in supervised learning, their integration into semi-supervised generative frameworks remains limited and underdeveloped. In this paper, we propose a novel method termed Gradient Consistency-Based Bad Semi-Supervised Generative Adversarial Network (GC-BSGAN), which introduces a new adversarial direction by enforcing gradient consistency on generated samples within the Bad GAN framework. Unlike conventional approaches that apply adversarial perturbations uniformly, the proposed method focuses on bad fake samples and low-confidence regions, where decision boundaries are most vulnerable. The core contribution of this work lies in integrating gradient-based adversarial perturbations with consistency regularization, enabling the classifier to maintain stable predictions under adversarial directions. Additionally, the proposed framework leverages Mixup-based interpolation between real and generated samples to further enhance boundary-aware learning. Extensive experiments conducted on MNIST and Fashion-MNIST datasets demonstrate that the proposed method significantly improves performance over existing semi-supervised approaches. GC-BSGAN achieves error rates as low as 1.06% and improves classification accuracy up to 99.15%, particularly under limited labeled data scenarios. The results confirm that enforcing gradient consistency leads to stronger adversarial examples, smoother decision boundaries, and improved generalization, making GC-BSGAN an effective framework for semi-supervised adversarial learning.
#  Keywords
Interpolation consistency, Semi-supervised learning, Generative Adversarial Network, Gradient adversarial consistency

#  Contributing
Contributions to this project are welcome. If you have any suggestions, improvements, or bug fixes, please submit a pull request or open an issue on the GitHub repository.

#  License
This project is licensed under the MIT License.
