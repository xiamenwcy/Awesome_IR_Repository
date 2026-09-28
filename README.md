# Awesome Iris Recognition Repository

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/xiamenwcy/Awesome_IR_Repository.svg?style=social&label=Star)](https://github.com/xiamenwcy/Awesome_IR_Repository)
[![GitHub forks](https://img.shields.io/github/forks/xiamenwcy/Awesome_IR_Repository.svg?style=social&label=Fork)](https://github.com/xiamenwcy/Awesome_IR_Repository)

A curated collection of open-source resources for **iris recognition**, including iris datasets, iris image quality assessment, iris presentation attack detection, iris segmentation, iris feature analysis, open-source iris recognition systems, iris-related competitions, VR/AR-related iris biometrics, iris synthesis, and survey papers.

## Table of Contents

- [Purpose of this Repository](#summary-purpose)
- [Iris Datasets](#iris-datasets)
- [Iris Image Quality Assessment](#iris-image-quality-assessment)
- [Iris Presentation Attack Detection](#iris-pad)
- [Iris Segmentation](#iris-segmentation)
- [Iris Feature Analysis](#iris-feature-analysis)
- [Open-Source Iris Recognition Systems](#open-source-iris-recognition-systems)
- [VR/AR-related Iris Biometrics](#VR/AR)
- [Iris Synthesis](#Iris_synthesis)
- [Survey Papers](#survey-papers)
- [Citations](#citations)
- [Contact](#contact)
- [Contributing](#contributing)
- [License](#license)

<a name="summary-purpose"/></a>
## Purpose of this Repository

The purpose of this repository is to organize and maintain open-source resources related to iris recognition. It aims to provide a structured overview of the iris recognition research field, including representative datasets, algorithms, systems, competitions, and survey papers.

This repository is intended to help researchers, students, and practitioners who are new to iris recognition quickly understand the overall research landscape and reduce the entry barrier to conducting research in this field.

The collected resources cover multiple important stages and topics in iris recognition, including but not limited to iris image acquisition, iris image quality assessment, iris presentation attack detection, iris segmentation, iris feature representation, iris matching, and open-source iris recognition systems.

<a name="iris-datasets"/></a>
## Iris Datasets

A list of existing databases of human iris images is available at [https://irisdata.fei.stuba.sk/](https://irisdata.fei.stuba.sk/) and [https://iapr-tc4.org/iris-datasets/](https://iapr-tc4.org/iris-datasets/).

<a name="iris-image-quality-assessment"/></a>
## Iris Image Quality Assessment
- IrisQualityCapture: [[GitHub]](https://github.com/naveengv7/IrisQualityCapture)
- Nguyen K, Proença H, Alonso-Fernandez F. Deep learning for iris recognition: A survey[J]. ACM Computing Surveys, 2024, 56(9): 223.[[Paper]](https://dl.acm.org/doi/full/10.1145/3651306)   
- Jenadeleh M, Pedersen M, Saupe D. Blind quality assessment of iris images acquired in visible light for biometric recognition[J]. Sensors, 2020, 20(5): 1308.[[Paper]](https://www.mdpi.com/1424-8220/20/5/1308)  
- Wang L, Zhang K, Ren M, et al. Recognition oriented iris image quality assessment in the feature space[C]//2020 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2020: 1-9.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9304896/) [[Code]](https://github.com/Debatrix/DFSNet) 
- Li X, Sun Z, Tan T. Comprehensive assessment of iris image quality[C]//2011 18th IEEE International Conference on Image Processing. IEEE, 2011: 3117-3120.[[Paper]](https://ieeexplore.ieee.org/abstract/document/6116326) 

<a name="iris-pad"/></a>
## Iris Presentation Attack Detection

- Wang C, Li L, Guo F, et al. Attention-assisted multilevel fusion framework for generalized iris presentation attack detection[J]. Pattern Recognition, 2026, 171: 112262.[[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320325009239) [[Code]](https://github.com/xiamenwcy/AMF-IPAD)
- Wang Caiyong, Sun Xianyun, Li Lin, Zhao Guangzhe, He Zhaofeng, Sun Zhenan. Iris presentation attack detection based on spatial and frequency feature fusion[J]. Journal of Image and Graphics, 2026, 31(1):0138-0153.[[Paper]](https://www.cjig.cn/zh/article/doi/10.11834/jig.240783/) [[Code]](https://github.com/XianyunSun/fre-iris-pad)(**in Chinese**)
- Tapia J E, Gonzalez S, Benalcazar D, et al. Are Morphed Periocular Iris Images a Threat to Iris Recognition?[J]. IEEE Transactions on Information Forensics and Security, 2025, 20: 12417-12428.[[Paper]](https://ieeexplore.ieee.org/abstract/document/11244141) 
- Pal D, Sony R, Ross A. A parametric approach to adversarial augmentation for cross-domain iris presentation attack detection[C]//2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV). IEEE, 2025: 5719-5729.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10943318/) [[Code]](https://github.com/iPRoBe-lab/ADV-GEN-IrisPAD)
- Jaswal G, Verma A, Roy S D, et al. Learning joint local-global iris representations via spatial calibration for generalized presentation attack detection[J]. IEEE Transactions on Biometrics, Behavior, and Identity Science, 2024, 6(2): 195-208.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10401986/) [[Code]](https://github.com/AmanVerma2307/DFCANet/tree/main)
- Luo Z, Wang Y, Liu N, et al. Combining 2D texture and 3D geometry features for Reliable iris presentation attack detection using light field focal stack[J]. IET Biometrics, 2022, 11(5): 420-429.[[Paper]](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/bme2.12092) [[Code]](https://github.com/luozhengquan/LFLD)
- Sharma R, Ross A. Image-level iris morph attack[C]//2021 IEEE International Conference on Image Processing (ICIP). IEEE, 2021: 3013-3017.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9506802/) [[Code]](https://github.com/sharmaGIT/IrisMorphing)
- Chen C, Ross A. An explainable attention-guided iris presentation attack detector[C]//Proceedings of the IEEE/CVF winter conference on applications of computer vision. 2021: 97-106.[[Paper]](https://openaccess.thecvf.com/content/WACV2021W/XAI4B/papers/Chen_An_Explainable_Attention-Guided_Iris_Presentation_Attack_Detector_WACVW_2021_paper.pdf) [[Code]](https://github.com/cunjian/AGPAD)
- Fang Z, Czajka A. Open source iris recognition hardware and software with presentation attack detection[C]//2020 IEEE international joint conference on biometrics (IJCB). IEEE, 2020: 1-8.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9304869/) [[Code]](https://github.com/CVRL/RaspberryPiOpenSourceIris)
- Sharma R, Ross A. D-NetPAD: An explainable and interpretable iris presentation attack detector[C]//2020 IEEE international joint conference on biometrics (IJCB). IEEE, 2020: 1-10.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9304880/) [[Code]](https://github.com/iPRoBe-lab/D-NetPAD)
- Czajka A, Fang Z, Bowyer K. Iris presentation attack detection based on photometric stereo features[C]//2019 IEEE winter conference on applications of computer vision (WACV). IEEE, 2019: 877-885.[[Paper]](https://ieeexplore.ieee.org/abstract/document/8658879/) [[Code]](https://github.com/CVRL/PhotometricStereoIrisPAD)
- Kuehlkamp A, Pinto A, Rocha A, et al. Ensemble of multi-view learning classifiers for cross-domain iris presentation attack detection[J]. IEEE Transactions on Information Forensics and Security, 2019, 14(6): 1419-1431.[[Paper]](https://ieeexplore.ieee.org/abstract/document/8513867) [[Code]](https://github.com/akuehlka/emvlc-ipad)
- Yadav S, Chen C, Ross A. Synthesizing Iris Images Using RaSGAN With Application in Presentation Attack Detection[C]//2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW). IEEE, 2019: 2422-2430.[[Paper]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/Biometrics/Yadav_Synthesizing_Iris_Images_Using_RaSGAN_With_Application_in_Presentation_Attack_CVPRW_2019_paper.pdf) [[Code]](https://github.com/yadavshi/RaSGAN)
- McGrath J, Bowyer K W, Czajka A. Open source presentation attack detection baseline for iris recognition[J]. arXiv preprint arXiv:1809.10172, 2018.[[Paper]](https://arxiv.org/abs/1809.10172) [[Code]](https://github.com/CVRL/OpenSourceIrisPAD)

- A useful open-source PAD evaluation toolkit in Python: [PyPAD](https://github.com/jedota/PyPAD)

> The PyPAD toolkit has the following features:
>- It is fully compliant with ISO 30107-3 and configurable to choose and estimate results based on different thresholds.
>- It is able to calculate metrics for binary and multi-class PAD systems.
>- It can plot DET curves containing all the presentation attack species for comparison. The plot depicts the two operational points typically reported, BPCER10 and BPCER20, with values highlighted.
>- An EER plot is automatically created, which can help us understand the relation between BPCER, APCER, and system thresholds.
>- Kernel Distribution Estimation (KDE) plots are reported using a linear and a log scale to highlight details and thresholds.
>- Configurable confusion matrices for multi-class problems and different thresholds.
>- A summary report is automatically generated describing different operational points (BPCER, APCER). 

- Iris presentation attack detection competitions are listed below:
>- LivDet-Iris 2013: [[Paper]](https://ieeexplore.ieee.org/document/6996283/) [[Homepage]](https://iris2013.livdet.org/)
>- MoblLive 2014: [[Paper]](https://ieeexplore.ieee.org/document/6996290/)  
>- LivDet-Iris 2015: [[Paper]](https://ieeexplore.ieee.org/document/7947701/) [[Homepage]](https://iris2015.livdet.org/index.php)
>- LivDet-Iris 2017: [[Paper]](https://ieeexplore.ieee.org/abstract/document/8272763/) [[Homepage]](https://iris2017.livdet.org/)
>- LivDet-Iris 2020: [[Paper]](https://ieeexplore.ieee.org/abstract/document/9304941/) 
>- LivDet-Iris 2023: [[Paper]](https://ieeexplore.ieee.org/abstract/document/10448637/) [[Homepage]](https://livdetiris23.github.io/)
>- LivDet-Iris 2025: [[Paper]](https://ieeexplore.ieee.org/abstract/document/11411572/) [[Homepage]](https://livdet-iris.org/2025/)

<a name="iris-segmentation"/></a>
## Iris Segmentation

- Wang Q, Xia C, Yan Y, et al. A light spatial-frequency network for robust iris segmentation and localization[J]. Applied Soft Computing, 2025, 175: 113009.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1568494625003205) [[Code]](https://github.com/JINULEMON/SFNet/tree/master)
- Farmanifard P, Ross A. Iris-SAM: Iris segmentation using a foundation model[C]//International Conference on Pattern Recognition and Artificial Intelligence. Singapore: Springer Nature Singapore, 2024: 394-409.[[Paper]](https://link.springer.com/chapter/10.1007/978-981-97-8702-9_27) [[Code]](https://github.com/ParisaFarmanifard/Iris-SAM)
- Toizumi T, Takahashi K, Tsukada M. Segmentation-free direct iris localization networks[C]//Proceedings of the IEEE/CVF winter conference on applications of computer vision. 2023: 991-1000.[[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Toizumi_Segmentation-Free_Direct_Iris_Localization_Networks_WACV_2023_paper.pdf) [[Code]](https://github.com/tzm030329/Segmentation-free-Direct-Iris-Localization-Networks)
- Sun Y, Lu Y, Liu Y, et al. Towards more accurate and complete iris segmentation using hybrid transformer u-net[C]//2022 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2022: 1-10.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10007944/) [[Code]](https://github.com/Syloveslife/HTU-Net)
- Lu T, Wang C, Wang Y, et al. Multitask deep active contour-based iris segmentation for off-angle iris images[J]. Journal of Electronic Imaging, 2022, 31(4): 041211-041211.[[Paper]](https://doi.org/10.1117/1.JEI.31.4.041211) [[Code]](https://github.com/lutianhao/IrisGazeSeg)
- Wang C, Muhammad J, Wang Y, et al. Towards complete and accurate iris segmentation using deep multi-task attention network for non-cooperative iris recognition[J]. IEEE Transactions on information forensics and security, 2020, 15: 2944-2959.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9036930) [[Code]](https://github.com/xiamenwcy/IrisParseNet)
- Hofbauer H, Jalilian E, Uhl A. Exploiting superior CNN-based iris segmentation for better recognition accuracy[J]. Pattern Recognition Letters, 2019, 120: 17-23.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865518309395) [[Code]](https://www.wavelab.at/sources/Rathgeb16a/)
- Labati R D, Muñoz E, Piuri V, et al. Non-ideal iris segmentation using Polar Spline RANSAC and illumination compensation[J]. Computer Vision and Image Understanding, 2019, 188: 102787.[[Paper]](https://www.sciencedirect.com/science/article/pii/S1077314219301031) [[Code]](https://github.com/DonidaLabati/PS-RANSAC)
- Zhao Z, Ajay K. An accurate iris segmentation framework under relaxed imaging constraints using total variation model[C]//Proceedings of the IEEE international conference on computer vision. 2015: 3828-3836.[[Paper]](http://openaccess.thecvf.com/content_iccv_2015/html/Zhao_An_Accurate_Iris_ICCV_2015_paper.html) [[Code]](https://www4.comp.polyu.edu.hk/~csajaykr/tvmiris.htm)
- Haindl M, Krupička M. Unsupervised detection of non-iris occlusions[J]. Pattern Recognition Letters, 2015, 57: 60-65.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865515000604) [[Code]](https://ars.els-cdn.com/content/image/1-s2.0-S0167865515000604-mmc1.zip)

- Iris segmentation competitions are listed below:
>- Noisy Iris Challenge Evaluation - Part I (NICE.I) [[Paper]](https://ieeexplore.ieee.org/document/4401910/)
>-  Mobile Iris CHallenge Evaluation part I (MICHE I) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0167865515000574)
>-  NIR-ISL 2021 [[Paper]](https://ieeexplore.ieee.org/document/9484336) [[Homepage]](https://sites.google.com/view/nir-isl2021/home) [[GitHub]](https://github.com/xiamenwcy/NIR-ISL-2021)

<a name="iris-feature-analysis"/></a>
## Iris Feature Analysis

- Sun X, Wang C, Wang Y, et al. IrisFormer: a dedicated transformer framework for iris recognition[J]. IEEE Signal Processing Letters, 2025, 32: 431-435.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10816462/) [[Code]](https://github.com/XianyunSun/IrisFormer)
- Venkataswamy N G, Liu Y, Dey S, et al. An Open-Source Framework for Quality-Assured Smartphone-Based Visible Light Iris Recognition[J]. arXiv preprint arXiv:2512.15548, 2025.[[Paper]](https://arxiv.org/abs/2512.15548) [[Code]](https://github.com/naveengv7/VISIrisHub)
- Kumar A. Iris and Periocular Recognition Using Deep Learning[M]. Elsevier, 2024.[[Book]](https://www.google.com/books?hl=zh-CN&lr=&id=BOvoEAAAQBAJ&oi=fnd&pg=PP1&dq=Iris+and+Periocular+Recognition+using+Deep+Learning&ots=Xo8R25aWEH&sig=DuazobVIBHZWFhR4llj_cfLJQM0)  
- Nguyen K, Fookes C, Sridharan S, et al. Complex-valued iris recognition network[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023, 45(1): 182-196.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9721052) 
- Ren M, Wang Y, Zhu Y, et al. Multiscale dynamic graph representation for biometric recognition with occlusions[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023, 45(12): 15120-15136.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10193782/) [[Code]](https://github.com/RenMin1991/Dyamic-Graph-Representation)
- Ren M, Wang Y, Sun Z, et al. Dynamic graph representation for occlusion handling in biometrics[C]//Proceedings of the AAAI conference on artificial intelligence. 2020, 34(07): 11940-11947.[[Paper]](https://aaai.org/ojs/index.php/AAAI/article/view/6869)  
- Wei J, Huang H, Wang Y, et al. Towards more discriminative and robust iris recognition by learning uncertain factors[J]. IEEE Transactions on Information Forensics and Security, 2022, 17: 865-879.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9722888/) [[Code]](https://github.com/weijianze/uncertainty)
- Wei J, Wang Y, Li Y, et al. Cross-spectral iris recognition by learning device-specific band[J]. IEEE Transactions on Circuits and Systems for Video Technology, 2021, 32(6): 3810-3824.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9557317/) [[Code]](https://github.com/weijianze/CSINv2)
- Wang K, Kumar A. Periocular-assisted multi-feature collaboration for dynamic iris recognition[J]. IEEE Transactions on Information Forensics and Security, 2020, 16: 866-879.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9194073/) [[Code]](https://www4.comp.polyu.edu.hk/~csajaykr/irisperifusion.htm)
- Wang K, Kumar A. Toward more accurate iris recognition using dilated residual features[J]. IEEE Transactions on Information Forensics and Security, 2019, 14(12): 3233-3245.[[Paper]](https://ieeexplore.ieee.org/abstract/document/8698817/) 
- Zhao Z, Kumar A. A deep learning based unified framework to detect, segment and recognize irises using spatially corresponding features[J]. Pattern Recognition, 2019, 93: 546-557.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0031320319301499) 
- Ahmad S, Fuller B. Thirdeye: Triplet based iris recognition without normalization[C]//2019 IEEE 10th International Conference on Biometrics Theory, Applications and Systems (BTAS). IEEE, 2019: 1-9.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9185998) [[Code]](https://github.com/sohaib50k/ThirdEye---Iris-recognition-using-triplets)
- Zhao Z, Kumar A. Towards more accurate iris recognition using deeply learned spatially corresponding features[C]//Proceedings of the IEEE International Conference on Computer Vision (ICCV). 2017: 3809-3818.[[Paper]](https://openaccess.thecvf.com/content_iccv_2017/html/Zhao_Towards_More_Accurate_ICCV_2017_paper.html) [[Code]](https://web.comp.polyu.edu.hk/csajaykr/deepiris.htm) [[UniNet-Pytorch]](https://github.com/Debatrix/UniNet-Pytorch) [[UniNet]](https://github.com/friedrichyuan/UniNet)

- Iris recognition competitions are listed below:
>- Noisy Iris Challenge Evaluation - Part II  (NICE.II) [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865511004144) 
>-  Mobile Iris CHallenge Evaluation II (MICHE II) [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865516303683) 

<a name="open-source-iris-recognition-systems"/></a>
## Open-Source Iris Recognition Systems

This section collects open-source iris recognition systems, toolkits, and software packages.

| System / Toolkit | Main Functionality | Link |
|---|---|---|
| Notre Dame Open-Source Iris Recognition | [[Paper]](https://arxiv.org/abs/2605.20735) | [[Code]](https://github.com/CVRL/OpenSourceIrisRecognition/tree/main) |
| IRIS: Iris Recognition Inference System | [[Blog]](https://world.org/blog/engineering/iris-recognition-inference-system) |[[Code]](https://github.com/worldcoin/open-iris) |
| VISIrisHub| [[Paper]](https://arxiv.org/abs/2512.15548) | [[Code]](https://github.com/naveengv7/VISIrisHub) |
| USIT v3.0.0| [[Paper]](https://link.springer.com/chapter/10.1007/978-1-4471-6784-6_16) | [[Code]](https://www.wavelab.at/sources/Rathgeb16a/) |
| OpenIris| [[Paper]](https://doi.org/10.1145/3649902.3653348) | [[Code]](https://github.com/ocular-motor-lab/OpenIris) |
| OSIRIS | [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865515002986) |[[Code]](https://github.com/Mango233/Osiris) [[osiris-Docker]](https://github.com/tohki/iris-osiris) [[osiris_vmbox]](https://github.com/ClarksonCITeR/osiris_vmbox) |
| IR-MATLAB | [[Paper]](https://peterkovesi.com/studentprojects/libor/LiborMasekThesis.pdf) | [[Code]](https://peterkovesi.com/studentprojects/libor/sourcecode.html) |
| VeriEye (**commercial**) |  | [[30-day SDK Trial]](https://www.neurotechnology.com/verieye.html) |
| Open closed eyes classification |  | [[Code]](https://github.com/PINTO0309/OCEC/tree/main) [[Dataset]](https://huggingface.co/datasets/MichalMlodawski/closed-open-eyes) |
| MediaPipe Iris | [[Blog]](https://research.google/blog/mediapipe-iris-real-time-iris-tracking-depth-estimation/) | [[Face, Iris, and Gaze Estimation]](https://github.com/VincentChoi33/face-iris-gaze-estimation) |

<a name="VR/AR"/></a>
## VR/AR-related Iris Biometrics

- Mi Y, Yuan Q, Zhong Z, et al. ImmerIris: A Large-Scale Dataset and Benchmark for Off-Axis and Unconstrained Iris Recognition in Immersive Applications[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026, pp. 28838-28847. [[Paper]](https://openaccess.thecvf.com/content/CVPR2026/html/Mi_ImmerIris_A_Large-Scale_Dataset_and_Benchmark_for_Off-Axis_and_Unconstrained_CVPR_2026_paper.html)
- Baek J, Park Y, Seok C, et al. Noise-robust biometric authentication using infrared periocular images captured from a head-mounted display[J]. Electronics, 2025, 14(2): 240.[[Paper]](https://www.mdpi.com/2079-9292/14/2/240)  
- Sharma G, Nagaich D, Jaswal G, et al. Vreyesam: Virtual reality non-frontal iris segmentation using foundational model with uncertainty weighted loss[C]//2025 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2025: 1-9.[[Paper]](https://ieeexplore.ieee.org/abstract/document/11411123/) [[Code]](https://github.com/GeetanjaliGTZ/VREyeSAM)
- D. Lohr, M. J. Proulx, M. H. Raju and O. V. Komogortsev, "Ocular Authentication: Fusion of Gaze and Periocular Modalities," 2025 IEEE International Joint Conference on Biometrics (IJCB), Osaka, Japan, 2025, pp. 1-12.[[Paper]](https://ieeexplore.ieee.org/document/11411028)
- Kotwal K, Ulucan I, Özbulak G, et al. VRBiom: A New Periocular Dataset for Biometric Applications of Head-Mounted Display[J]. Electronics, 2025, 14(9): 1835.[[Paper]](https://www.mdpi.com/2079-9292/14/9/1835) [[Dataset]](https://www.idiap.ch/en/scientific-research/data/vrbiom)
- Peng Z, Xu J, Li S, et al. EyeSeg: an uncertainty-aware eye segmentation framework for AR/VR[C]//Proceedings of the Thirty-Fourth International Joint Conference on Artificial Intelligence. 2025: 1775-1783.[[Paper]](https://dl.acm.org/doi/abs/10.24963/ijcai.2025/198) [[Code]](https://github.com/JethroPeng/EyeSeg)
- Kotwal K, Özbulak G, Marcel S. Assessing the reliability of biometric authentication on virtual reality devices[C]//2024 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2024: 1-9.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10744429/) [[Dataset]](https://www.idiap.ch/en/scientific-research/data/vrbiom)
- Seok C, Park Y, Baek J, et al. AffectiVR: A database for periocular identification and valence and arousal evaluation in virtual reality[J]. Electronics, 2024, 13(20): 4112.[[Paper]](https://www.mdpi.com/2079-9292/13/20/4112) [[Dataset]](https://github.com/schaelin/AffectiVR)
- Kuo Wang, Ajay Kumar. Human Identification in Metaverse Using Egocentric Iris Recognition. TechRxiv.19750411.v1, 2022. [[Paper]](https://www.techrxiv.org/doi/full/10.36227/techrxiv.19750411.v1)
- Chaudhary A K, Kothari R, Acharya M, et al. Ritnet: Real-time semantic segmentation of the eye for gaze tracking[C]//2019 IEEE/CVF International Conference on Computer Vision Workshop (ICCVW). IEEE, 2019: 3698-3702.[[Paper]](https://ieeexplore.ieee.org/abstract/document/9022181/) [[Code]](https://bitbucket.org/eye-ush/ritnet/)

<a name="Iris_synthesis"/></a>
## Iris Synthesis
- Mitcheff M, Tinsley P, Czajka A. Privacy-safe iris presentation attack detection[C]//2024 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2024: 1-10.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10744455/) [[Code]](https://github.com/CVRL/PrivacySafeIrisPAD)
- Bhuiyan R A, Czajka A. Forensic iris image synthesis[C]//Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision. 2024: 1015-1023.[[Paper]](https://openaccess.thecvf.com/content/WACV2024W/MAP-A/html/Bhuiyan_Forensic_Iris_Image_Synthesis_WACVW_2024_paper.html) [[Code]](https://github.com/CVRL/Forensic-Iris-Image-Synthesis)
- Yadav S, Ross A. Synthesizing Iris Images using Generative Adversarial Networks: Survey and Comparative Analysis[EB/OL]. arXiv preprint arXiv:2404.17105, 2024.[[Paper]](https://arxiv.org/abs/2404.17105)
- Khan S K, Tinsley P, Czajka A. Deformirisnet: An identity-preserving model of iris texture deformation[C]//Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision. 2023: 900-908.[[Paper]](https://openaccess.thecvf.com/content/WACV2023/html/Khan_DeformIrisNet_An_Identity-Preserving_Model_of_Iris_Texture_Deformation_WACV_2023_paper.html) [[Code]](https://github.com/CVRL/DeformIrisNet)
- Yadav S, Ross A. iWarpGAN: Disentangling Identity and Style to Generate Synthetic Iris Images[C]//2023 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2023: 1-10.[[Paper]](https://arxiv.org/abs/2305.12596) [[Code]](https://github.com/yadavshi/iWarpGAN)
- Wang C, He Z, Wang C, et al. Generating intra-and inter-class iris images by identity contrast[C]//2022 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2022: 1-7.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10007974/) [[Code]](https://github.com/chenwang2022/iris-generation)
- Tomašević D, Peer P, Štruc V. BiOcularGAN: Bimodal synthesis and annotation of ocular images[C]//2022 IEEE International Joint Conference on Biometrics (IJCB). IEEE, 2022: 1-10.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10007982/) [[Code]](https://github.com/dariant/BiOcularGAN)

<a name="survey-papers"/></a>
## Survey Papers

This section collects survey and review papers on iris recognition and related topics.

- Feng Jianjiang, Jia Wei, Li Qi, Cui Zhe, Zhao Cairong, Lei Zhen, Wang Caiyong, Kang Wenxiong, Yu Shiqi, Fei Lunke, Li Xiaobai, Ye Mang, Wei Jianze, Cao Shiwen, Sun Shibo, Xie Tianming, Zheng Weishi, Yang Hongyu, Huang Junduan, Huang Di, and Sun Zhenan. Biometrics disciplinary development report （2021-2025）[J/OL]. Journal of Image and Graphics, 2026, 1-53.[[Paper]](https://www.cjig.cn/zh/article/doi/10.11834/jig.260069/) (**in Chinese**)
- Anand R, Singh S, Dileep A D, et al. A Systematic Failure Analysis of Vision Foundation Models for Open Set Iris Presentation Attack Detection[J]. IEEE Transactions on Biometrics, Behavior, and Identity Science, 2026,doi: 10.1109/TBIOM.2026.3694899.[[Paper]](https://ieeexplore.ieee.org/abstract/document/11526785/) 
- LIU Xunlu, WANG Caiyong, TIAN Jinqiu, ZHAO Guangzhe. Research Review on Revealing Human Gender and Race from Iris Images[J]. Computer Engineering and Applications, 2026, 62(9): 61-82.[[Paper]](http://cea.ceaj.org/CN/10.3778/j.issn.1002-8331.2505-0331) (**in Chinese**)
- Yin Y, He S, Zhang R, et al. Deep learning for iris recognition: a review[J]. Neural Computing and Applications, 2025, 37: 11125-11173.[[Paper]](https://link.springer.com/article/10.1007/s00521-025-11109-5) 
- Shahreza H O, Marcel S. Foundation models and biometrics: A survey and outlook[J]. IEEE Transactions on Information Forensics and Security, 2025, 20:9113-9138.[[Paper]](https://ieeexplore.ieee.org/abstract/document/11137396)
- Nguyen K, Proença H, Alonso-Fernandez F. Deep learning for iris recognition: A survey[J]. ACM Computing Surveys, 2024, 56(9): 223.[[Paper]](https://dl.acm.org/doi/full/10.1145/3651306)   
- Wang Cai-Yong,  Liu Xing-Yu,  Fang Mei-Ling,  Zhao Guang-Zhe,  He Zhao-Feng,  Sun Zhe-Nan.  A survey on iris presentation attack detection.  Acta Automatica Sinica,  2024, 50(2): 241−281.[[Paper]](https://www.aas.net.cn/cn/article/doi/10.16383/j.aas.c230109) (**in Chinese**)
- JIANG Jian, ZHANG Qi, WANG Caiyong. Review of Deep Learning Based Iris Recognition[J]. Journal of Frontiers of Computer Science and Technology, 2024, 18(6): 1421-1437.[[Paper]](http://fcst.ceaj.org/CN/10.3778/j.issn.1673-9418.2312062) (**in Chinese**)
- KONG Jialin, ZHANG Qi, WANG Caiyong. Review of Heterogeneous Iris Recognition[J]. Computer Science, 2024, 51(6): 186-197.[[Paper]](https://www.jsjkx.com/CN/10.11896/jsjkx.231200175) (**in Chinese**)
- Joshi I, Grimmer M, Rathgeb C, et al. Synthetic data in human analysis: A survey[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024, 46(7): 4957-4976.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10423161/)
- Boyd A, Speth J, Parzianello L, et al. Comprehensive study in open-set iris presentation attack detection[J]. IEEE Transactions on Information Forensics and Security, 2023, 18: 3238-3250.[[Paper]](https://ieeexplore.ieee.org/abstract/document/10122228)
- Jain A K, Deb D, Engelsma J J. Biometrics: Trust, but verify[J]. IEEE Transactions on Biometrics, Behavior, and Identity Science, 2022, 4(3): 303-323.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865515004365)  
- Kumari P, Seeja K R. Periocular biometrics: A survey[J]. Journal of King Saud University-Computer and Information Sciences, 2022, 34(4): 1086-1097.[[Paper]](https://www.sciencedirect.com/science/article/pii/S1319157818313302)  
- Zanlorensi L A, Laroca R, Luz E, et al. Ocular recognition databases and competitions: A survey[J]. Artificial Intelligence Review, 2022, 55(1): 129-180.[[Paper]](https://link.springer.com/article/10.1007/s10462-021-10028-w)  
- Zhenan Sun, Ran He, Liang Wang, Meina Kan, Jianjiang Feng, Fang Zheng, Weishi Zheng, Wangmeng Zuo, Wenxiong Kang, Weihong Deng, Jie Zhang, Hu Han, Shiguang Shan, Yunlong Wang, Yiwei Ru, Yuhao Zhu, Yunfan Liu, Yong He. Overview of biometrics research[J]. Journal of Image and Graphics, 2021, 26(6): 1254-1329. [[Paper]](https://www.cjig.cn/zh/article/doi/10.11834/jig.210078/) (**in Chinese**)
- Omelina L, Goga J, Pavlovicova J, et al. A survey of iris datasets[J]. Image and Vision Computing, 2021, 108: 104109.[[Paper]](https://www.sciencedirect.com/science/article/pii/S0262885621000147)  
- Gautam G, Mukhopadhyay S. Challenges, taxonomy and techniques of iris localization: A survey[J]. Digital Signal Processing, 2020, 107: 102852.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1051200420301974)   
- Wang Caiyong, Sun Zhenan. A Benchmark for Iris Segmentation[J]. Journal of Computer Research and Development, 2020, 57(2): 395-412. [[Paper]](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.2020.20190092) (**in Chinese**)
- Sun Y, Zhang M, Sun Z, et al. Demographic analysis from biometric data: Achievements, challenges, and new frontiers[J]. IEEE transactions on pattern analysis and machine intelligence, 2018, 40(2): 332-351.[[Paper]](https://ieeexplore.ieee.org/abstract/document/7855777/)
- Czajka A, Bowyer K W. Presentation attack detection for iris recognition: An assessment of the state-of-the-art[J]. ACM Computing Surveys (CSUR), 2018, 51(4): 86.[[Paper]](https://dl.acm.org/doi/abs/10.1145/3232849)  
- Nguyen K, Fookes C, Jillela R, et al. Long range iris recognition: A survey[J]. Pattern Recognition, 2017, 72: 123-143.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0031320317302182)      
- De Marsico M, Petrosino A, Ricciardi S. Iris recognition through machine learning techniques: A survey[J]. Pattern Recognition Letters, 2016, 82: 106-115.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865516000477)   
- Jain A K, Nandakumar K, Ross A. 50 years of biometric research: Accomplishments, challenges, and opportunities[J]. Pattern recognition letters, 2016, 79: 80-105.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865515004365)  
- Alonso-Fernandez F, Bigun J. A survey on periocular biometrics research[J]. Pattern Recognition Letters, 2016, 82: 92-105.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865515002913)  
- Nigam I, Vatsa M, Singh R. Ocular biometrics: A survey of modalities and fusion approaches[J]. Information Fusion, 2015, 26: 1-35.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1566253515000354)  
- Bowyer K W, Hollingsworth K, Flynn P J. Image understanding for iris biometrics: A survey[J]. Computer vision and image understanding, 2008, 110(2): 281-307.[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1077314207001373)   

<a name="citations"/></a>
## Citations

If you find this repository useful for your research, please consider citing it as follows:

```bibtex
@misc{Awesome_IR_Repository,
  title        = "Awesome Iris Recognition Repository",
  author       = "{Caiyong Wang}",
  howpublished = "\url{https://github.com/xiamenwcy/Awesome_IR_Repository/}",
  year         = 2026,
  note         = "Accessed: 2026-05-26"
}
```

<a name="contact"/></a>
## Contact

In case of questions related to this project and repository, contact Dr. Caiyong Wang ([wangcaiyong@bucea.edu.cn](mailto:wangcaiyong@bucea.edu.cn)).

<a name="contributing"/></a>
## Contributing

Contributions are welcome.

If you would like to add new datasets, papers, algorithms, systems, competitions, or other useful resources, please feel free to open an issue or submit a pull request.

<a name="license"/></a>
## License

This repository is intended for academic and research purposes. Please refer to the licenses of individual datasets, papers, and open-source projects before using them.
