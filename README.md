# Edge-AI-Paper-List

**Target venues**: system conferences (*OSDI/SOSP/ATC/EuroSys/ASPLOS*), network conferences (*NSDI/SIGCOMM*) and mobile conferences (*MobiCom/MobiSys/SenSys/UbiComp*).

We will keep maintaining this list :)

Note: Edge here refers to resource-constrained devices, not edge servers; AI here mostly refers to deep learning.

## Smartphones

[MobiCom'21] [AsyMo: scalable and efficient deep-learning inference on asymmetric mobile CPUs](https://dl.acm.org/doi/10.1145/3447993.3448625) </br>
[MobiCom'21] [Elf: accelerate high-resolution mobile deep vision with content-aware parallel offloading](https://dl.acm.org/doi/10.1145/3447993.3448628) </br>
[MobiCom'21] [UltraSE: single-channel speech enhancement using ultrasound](https://dl.acm.org/doi/10.1145/3447993.3448626) </br>
[MobiCom'21] [Experience: a five-year retrospective of MobileInsight](https://dl.acm.org/doi/10.1145/3447993.3448138) </br>
[MobiCom'21] [LegoDNN: block-grained scaling of deep neural networks for mobile vision](https://dl.acm.org/doi/10.1145/3447993.3483249) </br>
[MobiSys�?1] [Tap: an app framework for dynamically composable mobile systems](https://dl.acm.org/doi/10.1145/3458864.3467678) </br>
[MobiSys�?1] [nn-Meter: towards accurate latency prediction of deep-learning model inference on diverse edge devices](https://dl.acm.org/doi/10.1145/3458864.3467882) </br>
[MobiSys�?1] [zTT: learning-based DVFS with zero thermal throttling for mobile devices](https://dl.acm.org/doi/10.1145/3458864.3468161) </br>
[MobiCom'20] [Deep Learning Based Wireless Localization for Indoor Navigation](https://dl.acm.org/doi/pdf/10.1145/3372224.3380894) </br>
[MobiCom'20] [SPINN: Synergistic Progressive Inference of Neural Networks over Device and Cloud](https://dl.acm.org/doi/pdf/10.1145/3372224.3419194) </br>
[MobiCom'20] [Heimdall: Mobile GPU Coordination Platform for Augmented Reality Applications](https://dl.acm.org/doi/pdf/10.1145/3372224.3419192) </br>
[MobiCom'20] [NEMO: Enabling Neural-enhanced Video Streaming on Commodity Mobile Devices](https://dl.acm.org/doi/pdf/10.1145/3372224.3419185) </br>
[MobiCom'20] [OnRL: Improving Mobile Video Telephony via Online Reinforcement Learning](https://dl.acm.org/doi/pdf/10.1145/3372224.3419186) </br>
[ASPLOS'20] [PatDNN: Achieving Real-Time DNN Execution on Mobile Devices with Pattern-based Weight Pruning](https://dl.acm.org/doi/pdf/10.1145/3373376.3378534) </br>
[MobiSys�?0] [Deep Compressive Offloading: Speeding up Neural Network Inference by Trading Edge Computation for Network Latency](https://doi.org/10.1145/3384419.3430898)</br>
[MobiSys�?0] [Fast and scalable In-memory Deep Multitask Learning via Neural Weight Virtualization](https://doi.org/10.1145/3386901.3388947)</br>
[MobiSys�?0] [MDLdroidLite: A Release-and-inhibit Control Approach to Resource-efficient Deep Neural Networks on Mobile Devices](https://doi.org/10.1145/3384419.3430716)</br>
[MobiSys'20] [RF-net: A Unified Meta-learning Framework for RF-enabled One-shot Human Activity Recognition](https://doi.org/10.1145/3384419.3430735)</br>
[SenSys'20] [MobiPose: real-time multi-person pose estimation on mobile devices](https://dl.acm.org/doi/abs/10.1145/3384419.3430726) </br>
[MobiCom'19] [RNN-Based Room Scale Hand Motion Tracking](https://dl.acm.org/doi/10.1145/3300061.3345439) </br>
[MobiCom'19] [MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors](https://dl.acm.org/doi/10.1145/3300061.3345455) </br>
[EuroSys'19] [µLayer: Low Latency On-Device Inference Using Cooperative Single-Layer Acceleration and Processor-Friendly Quantization](https://dl.acm.org/doi/pdf/10.1145/3302424.3303950) </br>
[SenSys�?9] [DeepAPP: A Deep Reinforcement Learning Framework for Mobile Application Usage Prediction](https://doi.org/10.1145/3356250.3360038)</br>
[MobiCom'18] [DeepCache: Principled Cache for Mobile Deep Vision](https://dl.acm.org/doi/10.1145/3241539.3241563) </br>
[MobiCom'18] [NestDNN: Resource-Aware Multi-Tenant On-Device Deep Learning for Continuous Mobile Vision](https://dl.acm.org/doi/10.1145/3241539.3241559) </br>
[MobiCom'18] [FoggyCache: Cross-Device Approximate Computation Reuse](https://dl.acm.org/doi/10.1145/3241539.3241557) </br>
[MobiSys�?8][On-Demand Deep Model Compression for Mobile Devices: A Usage-Driven Model Selection Framework](https://doi.org/10.1145/3210240.3210337)</br>
[MobiSys�?8][FastDeepIoT: Towards Understanding and Optimizing Neural Network Execution Time on Mobile and Embedded Devices](https://doi.org/10.1145/3274783.3274840)</br>
[MobiSys'17] [Accelerating Mobile Audio Sensing Algorithms through On-Chip GPU Offloading](https://dl.acm.org/ft_gateway.cfm?id=3081358&ftid=1882661&dwn=1&CFID=39793162&CFTOKEN=15a0f3fc0be5d576-24EC57D1-9A17-7F75-7BEC8FD035518031) </br>
[MobiSys'17] [MobileDeepPill: A Small-Footprint Mobile Deep Learning System for Recognizing Unconstrained Pill Images](https://dl.acm.org/ft_gateway.cfm?id=3081336&ftid=1882628&dwn=1&CFID=39793162&CFTOKEN=15a0f3fc0be5d576-24EC57D1-9A17-7F75-7BEC8FD035518031) </br>
[MobiSys'17] [DeepEye: Resource Efficient Local Execution of Multiple Deep Vision Models using Wearable Commodity Hardware](https://dl.acm.org/ft_gateway.cfm?id=3081359&ftid=1882636&dwn=1&CFID=39793162&CFTOKEN=15a0f3fc0be5d576-24EC57D1-9A17-7F75-7BEC8FD035518031) </br>
[MobiSys'17] [DeepMon: Building Mobile GPU Deep Learning Models for Continuous Vision Applications](https://dl.acm.org/ft_gateway.cfm?id=3081360&ftid=1882639&dwn=1&CFID=39793162&CFTOKEN=15a0f3fc0be5d576-24EC57D1-9A17-7F75-7BEC8FD035518031) </br>
[ASPLOS'17] [Neurosurgeon: Collaborative Intelligence Between the Cloud and Mobile Edge](https://dl.acm.org/doi/10.1145/3037697.3037698) </br>
[Ubicomp'16] [SpotGarbage: Smartphone App to Detect Garbage Using Deep Learning](https://dl.acm.org/doi/pdf/10.1145/2971648.2971731) </br>
[Ubicomp'15] [DeepEar: robust smartphone audio sensing in unconstrained acoustic environments using deep learning](https://dl.acm.org/doi/pdf/10.1145/2750858.2804262) </br>
[ATC'21] [Octo: INT8 Training with Loss-aware Compensation and Backward Quantization for Tiny On-device Learning](https://www.usenix.org/conference/atc21/presentation/zhou-qihua) </br>


## AR/VR

[MobiCom'21] [Face-Mic: inferring live speech and speaker identity via subtle facial dynamics captured by AR/VR motion sensors](https://dl.acm.org/doi/10.1145/3447993.3483272) </br>
[MobiSys�?1] [Xihe: a 3D vision-based lighting estimation framework for mobile augmented reality](https://dl.acm.org/doi/10.1145/3458864.3467886) </br>
[MobiSys�?1] [LensCap: split-process framework for fine-grained visual privacy control for augmented reality apps](https://dl.acm.org/doi/10.1145/3458864.3467676) </br>
[ASPLOS'20] [Coterie: Exploiting Frame Similarity to Enable High-Quality Multiplayer VR on Commodity Mobile Devices](https://dl.acm.org/doi/pdf/10.1145/3373376.3378516) </br>
[MobiCom'19] [Edge Assisted Real-time Object Detection for Mobile Augmented Reality](https://dl.acm.org/doi/10.1145/3300061.3300116) </br>
[EuroSys'19] [Transparent AR Processing Acceleration at the Edge](https://dl.acm.org/doi/pdf/10.1145/3301418.3313942) </br>
[ASPLOS'21] [Q-VR: System-Level Design for Future Collaborative Virtual Reality Rendering](https://dl.acm.org/doi/abs/10.1145/3445814.3446715) </br>
[ATC'20] [Firefly: Untethered Multi-user VR for Commodity Mobile Devices](https://www.usenix.org/conference/atc20/presentation/liu-xing) </br>


## IoTs

[ATC'21] [Video Analytics with Zero-streaming Cameras](https://xumengwei.github.io/files/ATC-DIVA.pdf)</br>
[ATC'22] [CoVA: Exploiting Compressed-Domain Analysis to Accelerate Video Analytics](https://www.usenix.org/system/files/atc22-hwang.pdf) </br>
[MobiSys'20] [Approximate Query Service on Autonomous IoT Cameras](https://xumengwei.github.io/files/MobiSys-Elf.pdf)</br>
[MobiSys�?0] [EMO: Real-time Emotion Recognition From Single-eye Images for Resource-constrained Eyewear Devices](https://doi.org/10.1145/3386901.3388917)</br>
[MobiCom'20] [CLIO: Enabling Automatic Compilation of Deep Learning Pipelines Across IoT and Cloud](https://dl.acm.org/doi/pdf/10.1145/3372224.3419215) </br>
[MobiCom'20] [EagleEye: Wearable Camera-based Person Identification in Crowded Urban Spaces](https://dl.acm.org/doi/pdf/10.1145/3372224.3380881) </br>
[SigComm'20] [Reducto: On-Camera Filtering for Resource-Efficient Real-Time Video Analytics](https://dl.acm.org/doi/pdf/10.1145/3387514.3405874) </br>
[MobiCom'19] [Source Compression with Bounded DNN Perception Loss for IoT Edge Computer Vision](https://dl.acm.org/doi/10.1145/3300061.3345448) </br>
[SenSys�?9] [Neuro.ZERO: A Zero-energy Neural Network Accelerator for Embedded Sensing and Inference Systems](https://doi.org/10.1145/3356250.3360030)</br>
[Ubicomp�?9] [Performance Characterization of Deep Learning Models for Breathing-based Authentication on Resource-Constrained Devices](https://doi.org/10.1145/3287036)</br>
[ASPLOS'18]  [SC-DCNN: Highly-Scalable Deep Convolutional Neural Network using Stochastic Computing](https://dl.acm.org/doi/pdf/10.1145/3037697.3037746) </br>
[SenSys�?7] [DeepIoT: Compressing Deep Neural Network Structures for Sensing Systems with a Compressor-Critic Framework](https://doi.org/10.1145/3131672.3131675)</br>
[MobiSys'17] [Glimpse: A Programmable Early-Discard Camera Architecture for Continuous Mobile Vision](https://dl.acm.org/ft_gateway.cfm?id=3081347&ftid=1882638&dwn=1&CFID=39793162&CFTOKEN=15a0f3fc0be5d576-24EC57D1-9A17-7F75-7BEC8FD035518031) </br>
[Ubicomp'17] [Low-resource Multi-task Audio Sensing for Mobile and Embedded Devices via Shared Deep Neural Network Representations](https://dl.acm.org/doi/pdf/10.1145/3131895)</br>
[MobiSys�?6] [MCDNN: An Approximation-Based Execution Framework for Deep Stream Processing Under Resource Constraints](https://doi.org/10.1145/2906388.2906396)</br>
[SenSys�?6] [Sparsification and Separation of Deep Learning Layers for Constrained Resource Inference on Wearables](https://doi.org/10.1145/2994551.2994564)</br>
[ASPLOS'21] [Rhythmic Pixel Regions: Visual sensing architecture for flexible spatiotemporal resolution towards high-precision visual computing at low power](https://dl.acm.org/doi/abs/10.1145/3445814.3446737) </br>
[NSDI'21] [AIRCODE: Hidden Screen-Camera Communication on an Invisible and Inaudible Dual Channel](https://www.usenix.org/conference/nsdi21/presentation/qian) </br>
[NSDI'21] [MAVL: Multiresolution Analysis of Voice Localization](https://www.usenix.org/conference/nsdi21/presentation/wang)</br>
[OSDI'20] [A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters](https://www.usenix.org/conference/osdi20/presentation/jiang)</br>
[OSDI'20] [PipeSwitch: Fast Pipelined Context Switching for Deep Learning Applications](https://www.usenix.org/conference/osdi20/presentation/bai)</br>
[OSDI'20] [Serving DNNs like Clockwork: Performance Predictability from the Bottom Up](https://www.usenix.org/conference/osdi20/presentation/gujarati)</br>
[ATC'21] [Fine-tuning giant neural networks on commodity hardware with automatic pipeline model parallelism](https://www.usenix.org/conference/atc21/presentation/eliad) </br>
[ATC'21] [Palleon: A Runtime System for Efficient Video Processing toward Dynamic Class Skew](https://www.usenix.org/conference/atc21/presentation/feng-boyuan) </br>
[EuroSys'20] [Balancing efficiency and fairness in heterogeneous GPU clusters for deep learning](https://dl.acm.org/doi/abs/10.1145/3342195.3387555) </br>
[EuroSys'22] [LiteReconfig: Cost and Content Aware Reconfiguration of Video Object Detection Systems for Mobile GPUs](https://dl.acm.org/doi/pdf/10.1145/3492321.3519577) </br>
[SenSys'22] [AutoMatch: Leveraging Traffic Camera to Improve Perception and Localization of Autonomous Vehicles](https://yanzhenyu.com/assets/pdf/AutoMatch-SenSys22.pdf) </br>


## Energy-harvested devices

[MobiSys�?0] [Approximate Query Service on Autonomous IoT Cameras](https://doi.org/10.1145/3386901.3388948)</br>
[SenSys�?0] [Ember: Energy Management of Batteryless Event Detection Sensors with Deep Reinforcement Learning](https://doi.org/10.1145/3384419.3430734)</br>
[ASPLOS'19] [Intelligence Beyond the Edge: Inference on Intermittent Embedded Systems](https://brandonlucia.com/pubs/2019.asplos.sonic.pdf) </br>
[ASPLOS'21] [Quantifying the Design-Space Tradeoffs in Autonomous Drones](https://dl.acm.org/doi/abs/10.1145/3445814.3446721) </br>
[ASPLOS'21] [Rhythmic Pixel Regions: Visual sensing architecture for flexible spatiotemporal resolution towards high-precision visual computing at low power](https://dl.acm.org/doi/abs/10.1145/3445814.3446737) </br>
[ATC'22] [PilotFish: Harvesting Free Cycles of Cloud Gaming with Deep Learning Training](https://www.usenix.org/system/files/atc22-choi-seungbeom.pdf) </br> 


## Privacy&Security
[ASPLOS'22] [Eavesdropping User Credentials via GPU Side Channels on Smartphones](https://dl.acm.org/doi/10.1145/3503222.3507757) </br>
[NSDI'22] [Privid: Practical, Privacy-Preserving Video Analytics Queries](https://www.usenix.org/system/files/nsdi22-paper-cangialosi.pdf) </br>
[MobiCom'21] [PECAM: privacy-enhanced video streaming and analytics via securely-reversible transformation](https://dl.acm.org/doi/10.1145/3447993.3448618) </br>
[MobiSys�?1] [SafetyNOT: on the usage of the SafetyNet attestation API in Android](https://dl.acm.org/doi/10.1145/3458864.3466627) </br>
[MobiSys�?1] [Rushmore: securely displaying static and animated images using TrustZone](https://dl.acm.org/doi/10.1145/3458864.3467887) </br>
[MobiCom'20] [FaceRevelio: A Face Liveness Detection System for Smartphones with A Single Front Camera](https://dl.acm.org/doi/pdf/10.1145/3372224.3419206) </br>
[ASPLOS'20] [DNNGuard: An Elastic Heterogeneous DNN Accelerator Architecture against Adversarial Attacks](https://dl.acm.org/doi/pdf/10.1145/3373376.3378532) </br>
[Ubicomp'20] [Countering Acoustic Adversarial Attacks in Microphone-equipped mart Home Devices](https://doi.org/10.1145/3397332)</br>
[Ubicomp'19] [DeepType: On-Device Deep Learning for Input Personalization Service with Minimal Privacy Concern](https://doi.org/10.1145/3287075)</br>
[Ubicomp'19] [Keyboard Snooping from Mobile Phone Arrays with Mixed Convolutional and Recurrent Neural Networks](https://doi.org/10.1145/3328916)</br>
[MobiCom'19] [Occlumency: Privacy-preserving Remote Deep-learning Inference Using SGX](https://dl.acm.org/doi/10.1145/3300061.3345447) </br>
[EuroSys'19] [Forward and Backward Private Searchable Encryption with SGX](https://dl.acm.org/doi/pdf/10.1145/3301417.3312496) </br> 
[EuroSys'22] [Minimum Viable Device Drivers for ARM TrustZone](https://dl.acm.org/doi/pdf/10.1145/3492321.3519565) </br> 
[ATC'22] [PRIDWEN: Universally Hardening SGX Programs via Load-Time Synthesis](https://www.usenix.org/system/files/atc22-sang.pdf) </br> 
[ATC'22] [HyperEnclave: An Open and Cross-platform Trusted Execution Environment](https://www.usenix.org/system/files/atc22-jia-yuekai.pdf) </br> 
[SOSP'19] [Privacy Accounting and Quality Control in the Sage Differentially Private ML Platform](https://dl.acm.org/doi/10.1145/3341301.3359639) </br>
[SOSP'19] [Honeycrisp: Large-scale Differentially Private Aggregation Without a Trusted Core](https://dl.acm.org/doi/10.1145/3341301.3359660) </br>
[SOSP'19] [Yodel: Strong Metadata Security for Voice Calls](https://dl.acm.org/doi/10.1145/3341301.3359648) </br>
[OSDI'21] [Privacy Budget Scheduling](https://www.usenix.org/system/files/osdi21-luo.pdf)</br>
[OSDI'21] [Addra: Metadata-private voice communication over fully untrusted infrastructure](https://www.usenix.org/system/files/osdi21-ahmad.pdf)</br>
[OSDI'21] [MAGE: Nearly Zero-Cost Virtual Memory for Secure Computation (Awarded Best Paper!)](https://www.usenix.org/system/files/osdi21-kumar.pdf)</br>
[OSDI'21] [Zeph: Cryptographic Enforcement of End-to-End Data Privacy](https://www.usenix.org/system/files/osdi21-burkhalter.pdf)</br>
[OSDI'22] [BlackBox: A Container Security Monitor for Protecting Containers on Untrusted Operating Systems](https://www.usenix.org/system/files/osdi22-vant-hof.pdf) </br>
[OSDI'22] [Blockaid: Data Access Policy Enforcement for Web Applications](https://www.usenix.org/system/files/osdi22-zhang.pdf) </br>


## Learning
[SigComm'22] [Multi-resource interleaving for deep learning training](https://dl.acm.org/doi/pdf/10.1145/3544216.3544224) </br>
[ASPLOS'22] [Breaking the computation and communication abstraction barrier in distributed machine learning workloads](https://dl.acm.org/doi/10.1145/3503222.3507778) </br>
[MobiCom'21] [Hermes: an efficient federated learning framework for heterogeneous mobile clients](https://dl.acm.org/doi/10.1145/3447993.3483278) </br>
[MobiSys�?1] [PPFL: privacy-preserving federated learning with trusted execution environments](https://dl.acm.org/doi/10.1145/3458864.3466628) </br>
[MobiSys�?1] [ClusterFL: a similarity-aware federated learning system for human activity recognition](https://dl.acm.org/doi/10.1145/3458864.3467681) </br>
[SenSys�?1] [FedDL: Federated Learning via Dynamic Layer Sharing for Human Activity Recognition](https://dl.acm.org/doi/10.1145/3485730.3485946) </br>
[SenSys�?1] [Mercury: Efficient On-Device Distributed DNN Training via Stochastic Importance Sampling](https://dl.acm.org/doi/10.1145/3485730.3485930) </br>
[SenSys�?1] [FedMask: Joint Computation and Communication-Efficient Personalized Federated Learning via Heterogeneous Masking](https://dl.acm.org/doi/10.1145/3485730.3485929)  </br>
[MobiCom'20] [Billion-scale Federated Learning on Mobile Clients: a submodel design with tunable privacy](https://dl.acm.org/doi/pdf/10.1145/3372224.3419188) </br>
[SenSys�?9] [MetaSense: Few-shot Adaptation to Untrained Conditions in Deep Mobile Sensing](https://doi.org/10.1145/3356250.3360020)</br>
[UbiComp'18] [DeepType: On-Device Deep Learning for Input Personalization Service with Minimal Privacy Concern](https://xumengwei.github.io/files/UbiComp-DeepType.pdf)</br>
[NSDI'21] [Mistify: Automating DNN Model Porting for On-Device Inference at the Edge](https://www.usenix.org/conference/nsdi21/presentation/guo)</br>
[OSDI'20] [KungFu: Making Training in Distributed Machine Learning Adaptive](https://www.usenix.org/conference/osdi20/presentation/mai)</br>
[OSDI'20] [A Tensor Compiler for Unified Machine Learning Prediction Serving](https://www.usenix.org/conference/osdi20/presentation/nakandala)</br>
[OSDI'20] [Ansor: Generating High-Performance Tensor Programs for Deep Learning](https://www.usenix.org/conference/osdi20/presentation/zheng)</br>
[OSDI'21] [Oort: Efficient Federated Learning via Guided Participant Selection](https://www.usenix.org/system/files/osdi21-lai.pdf)</br>
[OSDI'21] [Pollux: Co-adaptive Cluster Scheduling for Goodput-Optimized Deep Learning (Awarded Best Paper)](https://www.usenix.org/system/files/osdi21-qiao.pdf)</br>
[OSDI'21] [P3: Distributed Deep Graph Learning at Scale](https://www.usenix.org/system/files/osdi21-gandhi.pdf)</br>
[OSDI'21] [GNNAdvisor: An Adaptive and Efficient Runtime System for GNN Acceleration on GPUs](https://www.usenix.org/system/files/osdi21-wang-yuke.pdf)</br>
[OSDI'21] [Dorylus: Affordable, Scalable, and Accurate GNN Training with Distributed CPU Servers and Serverless Threads](https://www.usenix.org/system/files/osdi21-thorpe.pdf)</br>
[OSDI'22] [SparTA: Deep-Learning Model Sparsity via Tensor-with-Sparsity-Attribute](https://www.usenix.org/system/files/osdi22-zheng-ningxin.pdf)</br>
[OSDI'22] [ROLLER: Fast and Efficient Tensor Compilation for Deep Learning](https://www.usenix.org/system/files/osdi22-zhu.pdf)</br>
[OSDI'22] [Walle: An End-to-End, General-Purpose, and Large-Scale Production System for Device-Cloud Collaborative Machine Learning](https://www.usenix.org/system/files/osdi22-lv.pdf)</br>
[OSDI'22] [Unity: Accelerating DNN Training Through Joint Optimization of Algebraic Transformations and Parallelization](https://www.usenix.org/system/files/osdi22-unger.pdf)</br>
[ATC'21] [Jump-Starting Multivariate Time Series Anomaly Detection for Online Service Systems](https://www.usenix.org/conference/atc21/presentation/ma) </br>
[ATC'21] [Habitat: A Runtime-Based Computational Performance Predictor for Deep Neural Network Training](https://www.usenix.org/conference/atc21/presentation/yu) </br>
[ATC'21] [Zico: Efficient GPU Memory Sharing for Concurrent DNN Training](https://www.usenix.org/conference/atc21/presentation/lim) </br>
[ATC'21] [Refurbish Your Training Data: Reusing Partially Augmented Samples for Faster Deep Neural Network Training](https://www.usenix.org/conference/atc21/presentation/lee) </br>
[ATC'21] [ZeRO-Offload: Democratizing Billion-Scale Model Training](https://www.usenix.org/conference/atc21/presentation/ren-jie) </br>
[ATC'22] [Faith: An Efficient Framework for Transformer Verification on GPUs](https://www.usenix.org/system/files/atc22-feng.pdf) </br> 
[ATC'22] [DVABatch: Diversity-aware Multi-Entry Multi-Exit Batching for Efficient Processing of DNN Services on GPUs](https://www.usenix.org/system/files/atc22-cui.pdf) </br> 
[ATC'22] [Serving Heterogeneous Machine Learning Models on Multi-GPU Servers with Spatio-Temporal Sharing](https://www.usenix.org/system/files/atc22-choi-seungbeom.pdf) </br>
[ATC'22] [PetS: A Unified Framework for Parameter-Efficient Transformers Serving](https://www.usenix.org/system/files/atc22-zhou-zhe.pdf) </br> 
[ATC'22] [Campo: Cost-Aware Performance Optimization for Mixed-Precision Neural Network Training](https://www.usenix.org/system/files/atc22-he.pdf) </br>
[ATC'22] [Primo: Practical Learning-Augmented Systems with Interpretable Models](https://www.usenix.org/system/files/atc22-hu.pdf) </br> 
[ATC'22] [Cachew: Machine Learning Input Data Processing as a Service](https://www.usenix.org/system/files/atc22-graur.pdf) </br>
[ATC'22] [SOTER: Guarding Black-box Inference for General Neural Networks at the Edge](https://www.usenix.org/system/files/atc22-shen.pdf) </br>
[EuroSys'21] [Accelerating graph sampling for graph machine learning using GPUs](https://dl.acm.org/doi/10.1145/3447786.3456244) </br>
[EuroSys'21] [DGCL: An Efficient Communication Library for Distributed GNN Training](https://dl.acm.org/doi/abs/10.1145/3447786.3456233) </br>
[EuroSys'21] [Seastar: Vertex-Centric Programming for Graph Neural Networks](https://dl.acm.org/doi/10.1145/3447786.3456247) </br>
[EuroSys'22] [Varuna: Scalable, Low-cost Training of Massive Deep Learning Models (Best Paper Award)](https://dl.acm.org/doi/pdf/10.1145/3492321.3519584) </br>
[EuroSys'22] [GNNLab: A Factored System for Sample-based GNN Training over GPUs](https://dl.acm.org/doi/pdf/10.1145/3492321.3519557) </br>
[EuroSys'22] [Out-Of-Order BackProp: An Effective Scheduling Technique for Deep Learning](https://dl.acm.org/doi/pdf/10.1145/3492321.3519563) </br>
[EuroSys'22] [Fleche: An Efficient GPU Embedding Cache for Personalized Recommendations](https://dl.acm.org/doi/pdf/10.1145/3492321.3519554) </br>
[SOSP'19] [PipeDream: Generalized Pipeline Parallelism for DNN Training](https://dl.acm.org/doi/10.1145/3341301.3359646) </br>
[SOSP'19] [A Generic Communication Scheduler for Distributed DNN Training Acceleration](https://dl.acm.org/doi/10.1145/3341301.3359642) </br>
[SOSP'21] [Gradient Compression Supercharged High-Performance Data Parallel DNN Training](https://dl.acm.org/doi/10.1145/3477132.3483553) </br>
[SOSP'21] [Generating Complex, Realistic Cloud Workloads using Recurrent Neural Networks](https://dl.acm.org/doi/10.1145/3477132.3483590) </br>
[SenSys'22] [BlastNet: Exploiting Duo-Blocks for Cross-Processor Real-Time DNN Inference](https://yanzhenyu.com/assets/pdf/BlastNet-SenSys22.pdf) </br>
[SenSys'22] [PriMask: Cascadable and Collusion-Resilient Data Masking for Mobile Cloud Inference](https://arxiv.org/pdf/2211.06716v1.pdf) </br>
[UbiComp'22] [Context-Aware Compilation of DNN Training Pipelines across Edge and Cloud](https://dl.acm.org/doi/10.1145/3494981) </br>

Another awesome [paper list about Federated Learning](https://github.com/chaoyanghe/Awesome-Federated-Learning)
