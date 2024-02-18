### 项目仓
- https://github.com/malware-defense/detectors_review(FS、MagNet)
- https://github.com/mzweilin/EvadeML-Zoo(FS、MagNet)

### malware domin：dversarial examples detecting
- When a tree falls: Using diversity in ensemble classifiers to identify evasion in malware detectors (NDSS2016, 目前未找到开源)
- Automated poisoning attacks and defenses in malware detection systems: An adversarial machine learning approach （Comput.Security，目前未找到开源）
- On the (statistical) detection of adversarial examples  (未开源，论文中说可以联系作者获取code)
- Robust android malware detection against adversarial example attacks  (恶意软件检测的，但也简单提到了对抗样本检测)


### all domin：dversarial examples detecting
- Detecting adversarial examples on deep neural networks with mutual information neural estimation (MIAED)[[TDSC2023, CCF-A](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10034820)]
  - **1. 未给出baseline选取理由，仅说是sota 2. 阐述了防御和检测的关系**
  - On detecting adversarial perturbations (GND)
  - Detecting adversarial samples from artifacts (KD+BU)
  - Characterizing adversarial subspaces using local intrinsic dimensionality (LID)
  - Adversarial and clean data are not twins (SSD)
  - Detecting adversarial image examples in deep neural networks with adaptive noise reduction (TSD)
  
- What You See is Not What the Network Infers: Detecting Adversarial Examples Based on Semantic Contradiction.NDSS2022, CCF-A `Generative-based AE detection` [[pdf](https://arxiv.org/pdf/2201.09650.pdf)] [[code](https://github.com/cure-lab/ContraNet)]



- A Simple Unsupervised Data Depth-based Method to Detect Adversarial Images[[ICLR2023, CCF-A, 未录用](https://openreview.net/pdf?id=RIcaT3C0wP)]
  - **1. Supervised methods depend on the knowledge about the perpetrated attack, Unsupervised methods do not assume any knowledge of the attacker. 2. 选取的理由是Unsupervised methods(但没说明为什么不选其他的)，  We could consider NIC (Ma and Liu, 2019) but extracting features at each layer is computationally expensive，考虑adaptive attack**
   - Feature squeezing: Detecting adversarial examples in deep neural networks (FS)
   - Magnet: A two-pronged defense against adversarial examples (Magnet)


- Adversarial Detection by Latent Style Transformations[[TIFS2022, CCF-A](https://arxiv.org/pdf/2006.09701.pdf)]
  - **1.给出了Adversarial defenses的分类  2. sota比较：MagNet, Defense-GAN,FBGAN； transformation based multi-point defense techniques比较：RIT, NFP**
  - image transformation based multi-point defense techniques 
  - Defense-gan:Protecting classifiers against adversarial attacks using generative models (Defense-GAN)
  - Magnet: a two-pronged defense against adversarial examples (Magnet)
  - Featurized bidirectional gan:Adversarial defense via adversarially learned semantic inference (FBGAN)
  - Detecting adversarial examples via neural fingerprinting (NFP)
  - Detecting adversarial examples through image transformation (RIT)
  
- ViDetecting adversarial examples is (nearly) as hard as classifying them[[USENIX Security2021, CCF-A](https://www.usenix.org/system/files/sec21-hussain.pdf)]
  - 无baseline

- {WaveGuard}: Understanding and mitigating audio adversarial examples
  - **1.audio domin, attack和defense均是选取本领域的，可借鉴  2. domain的baseline 3. 围绕domin和audio领域阐述目前防御无法抵御adaptive attack,可参考**
  - Isolated and ensemble audio preprocessing methods for detecting adversarial examples against automatic speech recognition
  - Characterizing audio adversarial examples using temporal dependency
  
  - Magnet: a two-pronged defense against adversarial examples
  - Countering adversarial images using input transformations
  - Defensive quantization: When efficiency meets robustness
  - Qusecnets: Quantization based defense mechanism for securing deep neural network against adversarial attacks
  - Detecting adversarial image examples in deep neural networks with adaptive noise reduction (TSD)


- **Attack as Detection: Using Adversarial Attack Methods to Detect Abnormal Examples**
[[TOSMA2023, CCF-A](https://dl.acm.org/doi/pdf/10.1145/3631977)]]
[[ISSTA2021, CCF-A](https://dl.acm.org/doi/pdf/10.1145/3460319.3464822)]
  - **1.基于leveraging (adversarial) robustness，解释了鲁棒性的原因 2. 标签翻转所耗费的cost 3.adversarial attack based abnormal example detection method 4. 用CLEVER来检测** 
  - Detecting adversarial samples from artifacts.
  - Characterizing Adversarial Subspaces Using Local Intrinsic Dimensionality (LID)
  - Dissector: Input Validation for Deep Learning Applications by Crossing-layer Dissection
  - Adversarial sample detection for deep neural network through model mutation testing


- **Beating attackers at their own games: Adversarial example detection using adversarial gradient directions**
  -[[AAAI2021, CCF-A, **](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Detecting+Adversarial+Sample&btnG=)] 
  - **1.也是利用攻击的思路，根据角度/方向的差异 2. baseline选取：transformed-based、Neighborhood-based**
  - A New Defense Against Adversarial Images: Turning a Weakness into a Strength.
  - Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks. (FS)
  - A Simple Unified Framework for Detecting Out-of-Distribution Samples and Adversarial Attacks.
  - Deep k-Nearest Neighbors: Towards Confident, Interpretable and Robust Deep Learning. (DkNN)


- Adversarial Example Detection Using Latent Neighborhood Graph
  - **1. baseline选取：仅描述sota**
  - Deep k-Nearest Neighbors: Towards Confident, Interpretable and Robust Deep Learning. (DkNN)
  - Defense against adversarial images using web-scale nearest-neighbor search. (KNN)
  - Characterizing adversarial subspaces using local intrinsic dimensionality (LID)
  - A new defense against adversarial images: Turning a weakness into a strength.

- Detecting Adversarial Examples from Sensitivity Inconsistency of Spatial-Transform Domain
  - **1. baseline选取：We compare SID with the state-of-the-art schemes based，未给出schemes based的含义**
  - Characterizing adversarial subspaces using local intrinsic dimensionality (LID)
  - A Simple Unified Framework for Detecting Out-Of-Distribution Samples and Adversarial Attacks. 
  - Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks. (FS)


- Class-disentanglement and applications in adversarial detection and defense 
  - adversarial training based methods and preprocessing based methods

- Detecting adversarial attacks via subset scanning of autoencoder activations and reconstruction error
  - Defense-gan: Protecting classifiers against adversarial attacks using generative models.
  - baseline
  

- Libre: A practical bayesian approach to adversarial detection
  - the fine-tuning start point MAP; 
  - two standard adversarial detection approaches KD [14] and LID [39], which both work on the extracted features by MAP; 
  - three popular BNN baselines MC dropout [17], MFVI [2], and LMFVI.

  
- EMShepherd: Detecting Adversarial Samples via Side-channel Leakage
  - Detecting adversarial samples with neural network invariant checking. (KDE)
  - Detecting adversarial samples from artifacts. (NIC)
  - Feature squeezing: Detecting adversarial examples in deep neural networks (FS)
  - Magnet: A two-pronged defense against adversarial examples (Magnet)
  