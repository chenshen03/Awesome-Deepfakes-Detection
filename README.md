# Awesome Deepfakes Detection![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A list of Deepfakes Detection datasets, tools, papers and code. If this list help you in your research, a star is my pleasure.

If you want to contribute to this list, welcome to send me a pull request or contact me :) .

This repo only collect papers related to Deepfake Detection. If you are also interested in Deepfakes, please refer to: [Awesome Deepfakes](https://github.com/Daisy-Zhang/Awesome-Deepfakes).

## Contents

- [Datasets](#datasets)
  - [Video Datasets](#video-datasets)
  - [Image Datasets](#image-datasets)
- [Competition](#competition)
- [Tools](#tools)
- [Papers](#papers)
  - [CVPR](#cvpr)
  - [ICCV](#iccv)
  - [ECCV](#eccv)
  - [ICML](#icml)
  - [IJCAI](#ijcai)
  - [AAAI](#aaai)
  - [NIPS](#nips)
  - [ACM MM](#acm-mm)
  - [ICME](#icme)
  - [TPAMI](#tpami)
  - [TIFS](#tifs)
  - [Other](#other)



## Datasets

### Video Datasets

* **UADFV**: "Exposing Deep Fakes Using Inconsistent Head Poses." [Paper](https://arxiv.org/abs/1811.00661)
* **EBV**: "In Ictu Oculi: Exposing AI Generated Fake Face Videos by Detecting Eye Blinking." [Paper](https://arxiv.org/abs/1806.02877)    [Download](http://www.cs.albany.edu/~lsw/downloads.html)
* **Deepfake-TIMIT**: "DeepFakes: a New Threat to Face Recognition? Assessment and Detection." [Paper](https://arxiv.org/abs/1812.08685)    [Download](https://conradsanderson.id.au/vidtimit/)
* **DFFD**: "DFFD: Diverse Fake Face Dataset." [Paper](http://cvlab.cse.msu.edu/dffd-diverse-fake-face-dataset.html)    [Download](http://cvlab.cse.msu.edu/dffd-dataset.html)
* **Wild Deepfake**: "WildDeepfake: A Challenging Real-World Dataset for Deepfake Detection." [Paper](https://arxiv.org/abs/2101.01456)    [Download](https://github.com/deepfakeinthewild/deepfake-in-the-wild)
* **Celeb-DF (v1)**: "Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.pdf)    [Download](https://github.com/yuezunli/celeb-deepfakeforensics/tree/master/Celeb-DF-v1)
* **Celeb-DF (v2)**: "Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.pdf)    [Download](https://github.com/yuezunli/celeb-deepfakeforensics/tree/master/Celeb-DF-v2)
* **DFDC**: "The DeepFake Detection Challenge (DFDC) Dataset." [Paper](https://arxiv.org/abs/2006.07397)    [Download](https://www.kaggle.com/c/deepfake-detection-challenge/data) 
* **Deeper Forensic-1.0**: "DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_DeeperForensics-1.0_A_Large-Scale_Dataset_for_Real-World_Face_Forgery_Detection_CVPR_2020_paper.pdf)    [Download](https://github.com/EndlessSora/DeeperForensics-1.0)
* **FaceForensic++**: "FaceForensics++: Learning to Detect Manipulated Facial Images." [Paper](https://arxiv.org/abs/1901.08971)    [Download](https://github.com/ondyari/FaceForensics)
* **DFGC**: "DFGC 2021: A DeepFake Game Competition." [Paper](https://arxiv.org/abs/2106.01217)    [Dowload](https://github.com/bomb2peng/DFGC_starterkit)
* **FFIW-10K**: "Face Forensics in the Wild." [Paper](https://arxiv.org/abs/2103.16076)    [Download](https://github.com/tfzhou/FFIW)
* **ForgeryNet**: "ForgeryNet: A Versatile Benchmark for Comprehensive Forgery Analysis." [Paper](https://arxiv.org/abs/2103.05630)    [Download](https://github.com/yinanhe/forgerynet)

|                     | Real Videos | Fake Videos |
| :-----------------: | :---------: | :---------: |
|        UADFV        |     49      |     49      |
|   Deepfake-TIMIT    |     320     |     640     |
|        DFFD         |    1000     |    3000     |
|    Celeb-DF (v2)    |     590     |    5639     |
|        DFDC         |   23,564    |   104,500   |
| DeeperForensics-1.0 |   50,000    |   10,000    |
|   FaceForensic++    |    1000     |    5000     |
|     ForgeryNet      |   99,630    |   121,617   |



### Image Datasets

* **DFFD**: "On the Detection of Digital Face Manipulation." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dang_On_the_Detection_of_Digital_Face_Manipulation_CVPR_2020_paper.pdf)    [Download](http://cvlab.cse.msu.edu/project-ffd.html)
* **FFHQ**: "A Style-Based Generator Architecture for Generative Adversarial Networks." [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf)    [Download](https://github.com/NVlabs/ffhq-dataset)
* **iFakeFaceDB**: "GANprintR: Improved Fakes and Evaluation of the State of the Art in Face Manipulation Detection." [Paper](https://arxiv.org/abs/1911.05351)    [Download](https://github.com/socialabubi/iFakeFaceDB)
* **100k Faces Generated by AI (Online)**: [Download](https://generated.photos/datasets)
* **ForgeryNet**: "ForgeryNet: A Versatile Benchmark for Comprehensive Forgery Analysis." [Paper](https://arxiv.org/abs/2103.05630)    [Download](https://github.com/yinanhe/forgerynet)

|             | Real Images |    Fake Images     |
| :---------: | :---------: | :----------------: |
|    DFFD     |   58,703    |      240,336       |
|    FFHQ     |      -      | 70,000 (GAN-based) |
| iFakeFaceDB |      -      | 87,000 (StyleGAN)  |
| 100k Faces  |      -      | 100,000 (StyleGAN) |
| ForgeryNet  |  1,438,201  |     1,457,861      |



## Competition

* **Kaggle DFDC**: [Competition](https://www.kaggle.com/c/deepfake-detection-challenge)
* **DFGC**: [Competition](http://dfgc2021.iapr-tc4.org/)
* **DeepForensics Challenge 2020**: [Competition](https://competitions.codalab.org/competitions/25228)



## Tools

* **Sensity**: [Website](https://sensity.ai/)
* **Deepware**: [Website](https://deepware.ai/)
* **Baidu Security**: [Website](http://weishi.baidu.com/product/deepfake)
* **DeepReal**: [Website](https://deepfakes.real-ai.cn/)



## Papers

### CVPR

* "ForgeryNet: A Versatile Benchmark for Comprehensive Forgery Analysis", CVPR 2021: [Paper](https://arxiv.org/abs/2103.05630)    [Github](https://github.com/yinanhe/forgerynet)
* "Representative Forgery Mining for Fake Face Detection", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Representative_Forgery_Mining_for_Fake_Face_Detection_CVPR_2021_paper.pdf)    [Github](https://github.com/crywang/RFM)
* "MagDR: Mask-Guided Detection and Reconstruction for Defending Deepfakes", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_MagDR_Mask-Guided_Detection_and_Reconstruction_for_Defending_Deepfakes_CVPR_2021_paper.pdf)
* "Improving the Efficiency and Robustness of Deepfakes Detection Through Precise Geometric Features", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_Improving_the_Efficiency_and_Robustness_of_Deepfakes_Detection_Through_Precise_CVPR_2021_paper.pdf)    [Github](https://github.com/frederickszk/LRnet)
* "Multi-Attentional Deepfake Detection", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Zhao_Multi-Attentional_Deepfake_Detection_CVPR_2021_paper.html)    [Github](https://github.com/yoctta/multiple-attention)
* "Lips Don't Lie: A Generalisable and Robust Approach To Face Forgery Detection", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Haliassos_Lips_Dont_Lie_A_Generalisable_and_Robust_Approach_To_Face_CVPR_2021_paper.pdf)
* "Spatial-Phase Shallow Learning: Rethinking Face Forgery Detection in Frequency Domain", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Spatial-Phase_Shallow_Learning_Rethinking_Face_Forgery_Detection_in_Frequency_Domain_CVPR_2021_paper.pdf)
* "Frequency-Aware Discriminative Feature Learning Supervised by Single-Center Loss for Face Forgery Detection", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Frequency-Aware_Discriminative_Feature_Learning_Supervised_by_Single-Center_Loss_for_Face_CVPR_2021_paper.pdf)
* "Generalizing Face Forgery Detection With High-Frequency Features", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Luo_Generalizing_Face_Forgery_Detection_With_High-Frequency_Features_CVPR_2021_paper.pdf)
* "Face Forgery Detection by 3D Decomposition", CVPR 2021: [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Face_Forgery_Detection_by_3D_Decomposition_CVPR_2021_paper.pdf)
* "Global Texture Enhancement for Fake Face Detection in the Wild", CVPR 2020: [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Global_Texture_Enhancement_for_Fake_Face_Detection_in_the_Wild_CVPR_2020_paper.pdf)
* "On the Detection of Digital Face Manipulation", CVPR 2020: [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dang_On_the_Detection_of_Digital_Face_Manipulation_CVPR_2020_paper.pdf)    [Github](https://github.com/JStehouwer/FFD_CVPR2020)
* "Face X-Ray for More General Face Forgery Detection", CVPR 2020: [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Face_X-Ray_for_More_General_Face_Forgery_Detection_CVPR_2020_paper.pdf)
* "FReTAL: Generalizing Deepfake Detection using Knowledge Distillation and Representation Learning", CVPR 2021 Workshop: [Paper](https://openaccess.thecvf.com/content/CVPR2021W/WMF/papers/Kim_FReTAL_Generalizing_Deepfake_Detection_Using_Knowledge_Distillation_and_Representation_Learning_CVPRW_2021_paper.pdf)    [Github](https://github.com/alsgkals2/FReTAL-Generalizing_Deepfakes_using_Knowledge_Distillation_and_Representation_Learning)

### ICCV

* "Attributing Fake Images to GANs: Learning and Analyzing GAN Fingerprints", ICCV 2019: [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Attributing_Fake_Images_to_GANs_Learning_and_Analyzing_GAN_Fingerprints_ICCV_2019_paper.pdf)    [Github](https://github.com/ningyu1991/GANFingerprints)

### ECCV

* "Thinking in Frequency: Face Forgery Detection by Mining Frequency-aware Clues", ECCV 2020: [Paper](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570086.pdf)
* "Two-branch Recurrent Network for Isolating Deepfakes in Videos", ECCV 2020: [Paper](https://arxiv.org/abs/2008.03412)

### ICML

* "Leveraging Frequency Analysis for Deep Fake Image Recognition", ICML 2020: [Paper](http://proceedings.mlr.press/v119/frank20a/frank20a.pdf)    [Github](https://github.com/RUB-SysSec/GANDCTAnalysis)

### IJCAI

* "FakeSpotter: A Simple yet Robust Baseline for Spotting AI-Synthesized Fake Faces", IJCAI 2020: [Paper](https://www.ijcai.org/Proceedings/2020/0476.pdf)

### AAAI

* "Domain General Face Forgery Detection by Learning to Weight", AAAI 2021: [Paper](https://www.aaai.org/AAAI21Papers/AAAI-589.SunK.pdf)    [Github](https://github.com/skJack/LTW)
* "Local Relation Learning for Face Forgery Detection", AAAI 2021: [Paper](https://arxiv.org/pdf/2105.02577.pdf)

### NIPS

* "AOT: Appearance Optimal Transport Based Identity Swapping for Forgery Detection", NIPS 2020: [Paper](https://papers.nips.cc/paper/2020/file/f718499c1c8cef6730f9fd03c8125cab-Paper.pdf)

### ACM MM

* "Not made for each other- Audio-Visual Dissonance-based Deepfake Detection and Localization", ACM MM 2020: [Paper](https://dl.acm.org/doi/10.1145/3394171.3413700)    [Github](https://github.com/abhinavdhall/deepfake/)
* "Sharp Multiple Instance Learning for DeepFake Video Detection", ACM MM 2020: [Paper](https://dl.acm.org/doi/pdf/10.1145/3394171.3414034)
* "DeepRhythm: Exposing DeepFakes with Attentional Visual Heartbeat Rhythms", ACM MM 2020: [Paper](https://dl.acm.org/doi/10.1145/3394171.3413707)
* "Emotions Don't Lie: An Audio-Visual Deepfake Detection Method using Affective Cues", ACM MM 2020: [Paper](https://dl.acm.org/doi/abs/10.1145/3394171.3413570)

### ICME

* "FSSPOTTER: Spotting Face-Swapped Video by Spatial and Temporal Clues", ICME 2020: [Paper](https://ieeexplore.ieee.org/document/9102914)

### TPAMI

* "DeepFake Detection Based on Discrepancies Between Faces and their Context", TPAMI 2021: [Paper](https://ieeexplore.ieee.org/document/9468380/)
* "FakeCatcher: Detection of Synthetic Portrait Videos using Biological Signals", TPAMI 2021: [Paper](https://ieeexplore.ieee.org/document/9141516/)

### TIFS

* "Detection of Fake and Fraudulent Faces via Neural Memory Networks", TIFS 2021: [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9309253)
* "Preventing DeepFake Attacks on Speaker Authentication by Dynamic Lip Movement Analysis", TIFS 2021: [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9298826)

### Other

* "FakeCatcher: Detection of Synthetic Portrait Videos using Biological Signals", TPAMI 2020: [Paper](https://ieeexplore.ieee.org/document/9141516)
* "How Do the Hearts of Deep Fakes Beat? Deep Fake Source Detection via Interpreting Residuals with Biological Signals", IJCB 2020: [Paper](https://ieeexplore.ieee.org/abstract/document/9304909)
* "Deepfake Detection using Spatiotemporal Convolutional Networks", arxiv: [Paper](https://arxiv.org/abs/2006.14749)    [Github](https://github.com/oidelima/Deepfake-Detection)
* "A Convolutional LSTM based Residual Network for Deepfake Video Detection", arxiv: [Paper](https://arxiv.org/abs/2009.07480)
* "Spatio-temporal Features for Generalized Detection of Deepfake Videos", submitted to CVIU: [Paper](https://arxiv.org/abs/2010.11844)