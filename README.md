----------------
  - CNN Architectures
    - [LeNet(1998)] 
    - [LeNet-5 (2010)] 
    - [AlexNet (2012)]
    - [ZFNet(2013)]
    - [VGGNet (2014)]
    - [GoogleNet/Inception(2014)]
    - [ResNet(2015)]
    - [FractalNet (2016)]
    - [PolyNet/Inception-Residual(2016)]
    - [DenseNet(2017)]    
    - [SegNet(2015)]
    - [YOLO(2015)]
    - [SqueezeNet(2016)]
    - [ResNeXt(2016)]
    - [CapsueNet(2017)]
    - [MobileNets]
    - [fast region based CNN]
    - [Xception]
    - [RCNN]
    - [IRCNN]
    - [ViP CNN]
    - [Look up based CNN]
    - [FCN]
    - [deep network with stochastic depth]
    - [deeply-supervised networks]
    - [ladder network]

-------------------------

   - [Image Classification]
      - [Face Recognition]    
   - [Object Recognition]
   - [Object Tracking]
   - [Object Localisation]
   - [Object Detection] 
     - [Mask R-CNN]
     - [RetinaNet]
     - [Faster R-CNN]
     - [RPN]
     - [Fast R-CNN]
     - [R-FCN]
   - [Image Segmentation]
   - [Image Captioning]
   - [Biomedical Imaging]
     - [MDNet]
     - [U-Net]
     - [R2U-Net]
   - [Remote Sensing]
   - [Video Analysis]
   - [Motion Detection]
   - [Human Pose Estimation]
   - [3D Vision]
--------------

![cnn_models](https://github.com/gopala-kr/CNNs/blob/master/resources/img/cnn_models.PNG)

------------

<p align="center">
  <img width="1000" src="https://github.com/hoya012/deep_learning_object_detection/blob/master/assets/deep_learning_object_detection_history.PNG" "Example of anomaly detection.">
</p>

-------------




### ImageNet Classification
* Microsoft (Deep Residual Learning) [[Paper](http://arxiv.org/pdf/1512.03385v1.pdf)][[Slide](http://image-net.org/challenges/talks/ilsvrc2015_deep_residual_learning_kaiminghe.pdf)]
  * Deep Residual Learning for Image Recognition, arXiv:1512.03385.
* Microsoft (PReLu/Weight Initialization) [[Paper]](http://arxiv.org/pdf/1502.01852)
  * Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification, arXiv:1502.01852.
* Batch Normalization [[Paper]](http://arxiv.org/pdf/1502.03167)
  * Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift, arXiv:1502.03167.
* GoogLeNet, CVPR, 2015. [[Paper]](http://arxiv.org/pdf/1409.4842)
* VGG-Net [[Web]](http://www.robots.ox.ac.uk/~vgg/research/very_deep/) [[Paper]](http://arxiv.org/pdf/1409.1556)
  *  Very Deep Convolutional Networks for Large-Scale Visual Recognition, ICLR, 2015.
* AlexNet [[Paper]](http://papers.nips.cc/book/advances-in-neural-information-processing-systems-25-2012)
  * ImageNet Classification with Deep Convolutional Neural Networks, NIPS, 2012.

### Object Detection

* PVANET [[Paper]](https://arxiv.org/pdf/1608.08021) [[Code]](https://github.com/sanghoon/pva-faster-rcnn)
  *  PVANET: Deep but Lightweight Neural Networks for Real-time Object Detection, arXiv:1608.08021
* OverFeat, NYU [[Paper]](http://arxiv.org/pdf/1312.6229.pdf)
  * OverFeat: Integrated Recognition, Localization and Detection using Convolutional Networks, ICLR, 2014.
* R-CNN, UC Berkeley [[Paper-CVPR14]](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf) [[Paper-arXiv14]](http://arxiv.org/pdf/1311.2524)
  * Rich feature hierarchies for accurate object detection and semantic segmentation, CVPR, 2014.
* SPP, Microsoft Research [[Paper]](http://arxiv.org/pdf/1406.4729)
  * Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition, ECCV, 2014.
* Fast R-CNN, Microsoft Research [[Paper]](http://arxiv.org/pdf/1504.08083)
* Faster R-CNN, Microsoft Research [[Paper]](http://arxiv.org/pdf/1506.01497)
  * Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks, arXiv:1506.01497.
* R-CNN minus R, Oxford [[Paper]](http://arxiv.org/pdf/1506.06981)
* End-to-end people detection in crowded scenes [[Paper]](http://arxiv.org/abs/1506.04878)
* You Only Look Once: Unified, Real-Time Object Detection [[Paper]](http://arxiv.org/abs/1506.02640), [[Paper Version 2]](https://arxiv.org/abs/1612.08242), [[C Code]](https://github.com/pjreddie/darknet), [[Tensorflow Code]](https://github.com/thtrieu/darkflow)
* Inside-Outside Net [[Paper]](http://arxiv.org/abs/1512.04143)
  * Inside-Outside Net: Detecting Objects in Context with Skip Pooling and Recurrent Neural Networks
* Deep Residual Network (Current State-of-the-Art) [[Paper]](http://arxiv.org/abs/1512.03385)
  *  Deep Residual Learning for Image Recognition
* Weakly Supervised Object Localization with Multi-fold Multiple Instance Learning [[Paper](http://arxiv.org/pdf/1503.00949.pdf)]
* R-FCN [[Paper]](https://arxiv.org/abs/1605.06409) [[Code]](https://github.com/daijifeng001/R-FCN)
  * R-FCN: Object Detection via Region-based Fully Convolutional Networks
* SSD [[Paper]](https://arxiv.org/pdf/1512.02325v2.pdf) [[Code]](https://github.com/weiliu89/caffe/tree/ssd)

* Speed/accuracy trade-offs for modern convolutional object detectors [[Paper]](https://arxiv.org/pdf/1611.10012v1.pdf)


### Video Classification
*  "Delving Deeper into Convolutional Networks for Learning Video Representations", ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06432v4.pdf)]
* "Deep Multi Scale Video Prediction Beyond Mean Square Error", ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.05440v6.pdf)]

### Object Tracking
* Online Tracking by Learning Discriminative Saliency Map with Convolutional Neural Network, arXiv:1502.06796. [[Paper]](http://arxiv.org/pdf/1502.06796)
*  DeepTrack: Learning Discriminative Feature Representations by Convolutional Neural Networks for Visual Tracking, BMVC, 2014. [[Paper]](http://www.bmva.org/bmvc/2014/files/paper028.pdf)
*  Learning a Deep Compact Image Representation for Visual Tracking, NIPS, 2013. [[Paper]](http://winsty.net/papers/dlt.pdf)
* Hierarchical Convolutional Features for Visual Tracking, ICCV 2015 [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Ma_Hierarchical_Convolutional_Features_ICCV_2015_paper.pdf)] [[Code](https://github.com/jbhuang0604/CF2)]
* Visual Tracking with fully Convolutional Networks, ICCV 2015  [[Paper](http://202.118.75.4/lu/Paper/ICCV2015/iccv15_lijun.pdf)] [[Code](https://github.com/scott89/FCNT)]
* Learning Multi-Domain Convolutional Neural Networks for Visual Tracking, [[Paper](http://arxiv.org/pdf/1510.07945.pdf)] [[Code](https://github.com/HyeonseobNam/MDNet)] [[Project Page](http://cvlab.postech.ac.kr/research/mdnet/)]

### Low-Level Vision

#### Super-Resolution
* Iterative Image Reconstruction
  * Sven Behnke: Learning Iterative Image Reconstruction. IJCAI, 2001. [[Paper]](http://www.ais.uni-bonn.de/behnke/papers/ijcai01.pdf)
  * Sven Behnke: Learning Iterative Image Reconstruction in the Neural Abstraction Pyramid. International Journal of Computational Intelligence and Applications, vol. 1, no. 4, pp. 427-438, 2001. [[Paper]](http://www.ais.uni-bonn.de/behnke/papers/ijcia01.pdf)
* Super-Resolution (SRCNN) [[Web]](http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html) [[Paper-ECCV14]](http://personal.ie.cuhk.edu.hk/~ccloy/files/eccv_2014_deepresolution.pdf) [[Paper-arXiv15]](http://arxiv.org/pdf/1501.00092.pdf)
  *  Learning a Deep Convolutional Network for Image Super-Resolution, ECCV, 2014.
  *  Image Super-Resolution Using Deep Convolutional Networks, arXiv:1501.00092.
* Very Deep Super-Resolution
  *  Accurate Image Super-Resolution Using Very Deep Convolutional Networks, arXiv:1511.04587, 2015. [[Paper]](http://arxiv.org/abs/1511.04587)
* Deeply-Recursive Convolutional Network
  * Deeply-Recursive Convolutional Network for Image Super-Resolution, arXiv:1511.04491, 2015. [[Paper]](http://arxiv.org/abs/1511.04491)
* Casade-Sparse-Coding-Network
  *  Deep Networks for Image Super-Resolution with Sparse Prior. ICCV, 2015. [[Paper]](http://www.ifp.illinois.edu/~dingliu2/iccv15/iccv15.pdf) [[Code]](http://www.ifp.illinois.edu/~dingliu2/iccv15/)
* Perceptual Losses for Super-Resolution
  *  Perceptual Losses for Real-Time Style Transfer and Super-Resolution, arXiv:1603.08155, 2016. [[Paper]](http://arxiv.org/abs/1603.08155) [[Supplementary]](http://cs.stanford.edu/people/jcjohns/papers/fast-style/fast-style-supp.pdf)
* SRGAN
  * Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network, arXiv:1609.04802v3, 2016. [[Paper]](https://arxiv.org/pdf/1609.04802v3.pdf)
* Others
  *  Image Super-Resolution with Fast Approximate Convolutional Sparse Coding, ICONIP, 2014. [[Paper ICONIP-2014]](http://brml.org/uploads/tx_sibibtex/281.pdf)

#### Other Applications
* Optical Flow (FlowNet) [[Paper]](http://arxiv.org/pdf/1504.06852)
  * FlowNet: Learning Optical Flow with Convolutional Networks, arXiv:1504.06852.
* Compression Artifacts Reduction [[Paper-arXiv15]](http://arxiv.org/pdf/1504.06993)
  * Compression Artifacts Reduction by a Deep Convolutional Network, arXiv:1504.06993.
* Blur Removal
  *  Learning to Deblur, arXiv:1406.7444 [[Paper]](http://arxiv.org/pdf/1406.7444.pdf)
  *  Learning a Convolutional Neural Network for Non-uniform Motion Blur Removal, CVPR, 2015 [[Paper]](http://arxiv.org/pdf/1503.00593)
* Image Deconvolution [[Web]](http://lxu.me/projects/dcnn/) [[Paper]](http://lxu.me/mypapers/dcnn_nips14.pdf)
  *  Deep Convolutional Neural Network for Image Deconvolution, NIPS, 2014.
* Deep Edge-Aware Filter [[Paper]](http://jmlr.org/proceedings/papers/v37/xub15.pdf)
* Computing the Stereo Matching Cost with a Convolutional Neural Network [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zbontar_Computing_the_Stereo_2015_CVPR_paper.pdf)
  *  Computing the Stereo Matching Cost with a Convolutional Neural Network, CVPR, 2015.
* Colorful Image Colorization Richard Zhang, Phillip Isola, Alexei A. Efros, ECCV, 2016 [[Paper]](http://arxiv.org/pdf/1603.08511.pdf), [[Code]](https://github.com/richzhang/colorization)
*  [[Blog]](http://tinyclouds.org/colorize/)
* Feature Learning by Inpainting[[Paper]](https://arxiv.org/pdf/1604.07379v1.pdf)[[Code]](https://github.com/pathak22/context-encoder)
  * Context Encoders: Feature Learning by Inpainting, CVPR, 2016

### Edge Detection

* Holistically-Nested Edge Detection [[Paper]](http://arxiv.org/pdf/1504.06375) [[Code]](https://github.com/s9xie/hed)
  * Holistically-Nested Edge Detection, arXiv:1504.06375.
* DeepEdge [[Paper]](http://arxiv.org/pdf/1412.1123)
  *  DeepEdge: A Multi-Scale Bifurcated Deep Network for Top-Down Contour Detection, CVPR, 2015.
* DeepContour [[Paper]](http://mc.eistar.net/UpLoadFiles/Papers/DeepContour_cvpr15.pdf)
  * DeepContour: A Deep Convolutional Feature Learned by Positive-Sharing Loss for Contour Detection, CVPR, 2015.

### Semantic Segmentation

* PASCAL VOC2012 Challenge Leaderboard (01 Sep. 2016)
  (from PASCAL VOC2012 [leaderboards](http://host.robots.ox.ac.uk:8080/leaderboard/displaylb.php?challengeid=11&compid=6))
* SEC: Seed, Expand and Constrain
  *   Expand and Constrain: Three Principles for Weakly-Supervised Image Segmentation, ECCV, 2016. [[Paper]](http://pub.ist.ac.at/~akolesnikov/files/ECCV2016/main.pdf) [[Code]](https://github.com/kolesman/SEC)
* Adelaide
  *  Efficient piecewise training of deep structured models for semantic segmentation, arXiv:1504.01013. [[Paper]](http://arxiv.org/pdf/1504.01013) (1st ranked in VOC2012)
  *  Deeply Learning the Messages in Message Passing Inference, arXiv:1508.02108. [[Paper]](http://arxiv.org/pdf/1506.02108) (4th ranked in VOC2012)
* Deep Parsing Network (DPN)
  *  Semantic Image Segmentation via Deep Parsing Network, arXiv:1509.02634 / ICCV 2015 [[Paper]](http://arxiv.org/pdf/1509.02634.pdf) (2nd ranked in VOC 2012)
* CentraleSuperBoundaries, INRIA [[Paper]](http://arxiv.org/pdf/1511.07386)
  *  Surpassing Humans in Boundary Detection using Deep Learning, arXiv:1411.07386 (4th ranked in VOC 2012)
* BoxSup [[Paper]](http://arxiv.org/pdf/1503.01640)
  *  BoxSup: Exploiting Bounding Boxes to Supervise Convolutional Networks for Semantic Segmentation, arXiv:1503.01640. (6th ranked in VOC2012)
* POSTECH
  *  Learning Deconvolution Network for Semantic Segmentation, arXiv:1505.04366. [[Paper]](http://arxiv.org/pdf/1505.04366) (7th ranked in VOC2012)
  * Decoupled Deep Neural Network for Semi-supervised Semantic Segmentation, arXiv:1506.04924. [[Paper]](http://arxiv.org/pdf/1506.04924)
  * Learning Transferrable Knowledge for Semantic Segmentation with Deep Convolutional Neural Network, arXiv:1512.07928 [[Paper](http://arxiv.org/pdf/1512.07928.pdf)] [[Project Page](http://cvlab.postech.ac.kr/research/transfernet/)]
* Conditional Random Fields as Recurrent Neural Networks [[Paper]](http://arxiv.org/pdf/1502.03240)
  *  Conditional Random Fields as Recurrent Neural Networks, arXiv:1502.03240. (8th ranked in VOC2012)
* DeepLab
  *  Weakly-and semi-supervised learning of a DCNN for semantic image segmentation, arXiv:1502.02734. [[Paper]](http://arxiv.org/pdf/1502.02734) (9th ranked in VOC2012)
* Zoom-out [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Mostajabi_Feedforward_Semantic_Segmentation_2015_CVPR_paper.pdf)
  *  Feedforward Semantic Segmentation With Zoom-Out Features, CVPR, 2015
* Joint Calibration [[Paper]](http://arxiv.org/pdf/1507.01581)
  * Joint Calibration for Semantic Segmentation, arXiv:1507.01581.
* Fully Convolutional Networks for Semantic Segmentation [[Paper-CVPR15]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf) [[Paper-arXiv15]](http://arxiv.org/pdf/1411.4038)
  *  Fully Convolutional Networks for Semantic Segmentation, CVPR, 2015.
* Hypercolumn [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hariharan_Hypercolumns_for_Object_2015_CVPR_paper.pdf)
  *  Hypercolumns for Object Segmentation and Fine-Grained Localization, CVPR, 2015.
* Deep Hierarchical Parsing
  *  Deep Hierarchical Parsing for Semantic Segmentation, CVPR, 2015. [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Sharma_Deep_Hierarchical_Parsing_2015_CVPR_paper.pdf)
* Learning Hierarchical Features for Scene Labeling [[Paper-ICML12]](http://yann.lecun.com/exdb/publis/pdf/farabet-icml-12.pdf) [[Paper-PAMI13]](http://yann.lecun.com/exdb/publis/pdf/farabet-pami-13.pdf)
  * Scene Parsing with Multiscale Feature Learning, Purity Trees, and Optimal Covers, ICML, 2012.
  * Learning Hierarchical Features for Scene Labeling, PAMI, 2013.
* University of Cambridge [[Web]](http://mi.eng.cam.ac.uk/projects/segnet/)
  * "SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation." arXiv preprint arXiv:1511.00561, 2015. [[Paper]](http://arxiv.org/abs/1511.00561)
*  "Bayesian SegNet: Model Uncertainty in Deep Convolutional Encoder-Decoder Architectures for Scene Understanding." arXiv preprint arXiv:1511.02680, 2015. [[Paper]](http://arxiv.org/abs/1511.00561)
* Princeton
  * "Multi-Scale Context Aggregation by Dilated Convolutions", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.07122v2.pdf)]
* Univ. of Washington, Allen AI
  * "Segment-Phrase Table for Semantic Segmentation, Visual Entailment and Paraphrasing", ICCV, 2015, [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Izadinia_Segment-Phrase_Table_for_ICCV_2015_paper.pdf)]
* INRIA
  * "Pusing the Boundaries of Boundary Detection Using deep Learning", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.07386v2.pdf)]
* UCSB
  * "Weakly supervised graph based semantic segmentation by learning communities of image-parts", ICCV, 2015, [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Pourian_Weakly_Supervised_Graph_ICCV_2015_paper.pdf)]

### Visual Attention and Saliency

* Mr-CNN [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Liu_Predicting_Eye_Fixations_2015_CVPR_paper.pdf)
  * Predicting Eye Fixations using Convolutional Neural Networks, CVPR, 2015.
* Learning a Sequential Search for Landmarks [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Singh_Learning_a_Sequential_2015_CVPR_paper.pdf)
  *  Learning a Sequential Search for Landmarks, CVPR, 2015.
* Multiple Object Recognition with Visual Attention [[Paper]](http://arxiv.org/pdf/1412.7755.pdf)
  *  Multiple Object Recognition with Visual Attention, ICLR, 2015.
* Recurrent Models of Visual Attention [[Paper]](http://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf)
  * Recurrent Models of Visual Attention, NIPS, 2014.

### Object Recognition
* Weakly-supervised learning with convolutional neural networks [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Oquab_Is_Object_Localization_2015_CVPR_paper.pdf)
  * Is object localization for free? – Weakly-supervised learning with convolutional neural networks, CVPR, 2015.
* FV-CNN [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Cimpoi_Deep_Filter_Banks_2015_CVPR_paper.pdf)
  * Deep Filter Banks for Texture Recognition and Segmentation, CVPR, 2015.

### Human Pose Estimation
* Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields, CVPR, 2017.
* Deepcut: Joint subset partition and labeling for multi person pose estimation, CVPR, 2016.
* Convolutional pose machines, CVPR, 2016.
*  Stacked hourglass networks for human pose estimation, ECCV, 2016.
*  Flowing convnets for human pose estimation in videos, ICCV, 2015.
* Joint training of a convolutional network and a graphical model for human pose estimation, NIPS, 2014.

### Understanding CNN

*  Understanding image representations by measuring their equivariance and equivalence, CVPR, 2015. [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Lenc_Understanding_Image_Representations_2015_CVPR_paper.pdf)
* Deep Neural Networks are Easily Fooled:High Confidence Predictions for Unrecognizable Images, CVPR, 2015. [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Nguyen_Deep_Neural_Networks_2015_CVPR_paper.pdf)
* Understanding Deep Image Representations by Inverting Them, CVPR, 2015. [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Mahendran_Understanding_Deep_Image_2015_CVPR_paper.pdf)
*  Object Detectors Emerge in Deep Scene CNNs, ICLR, 2015. [[arXiv Paper]](http://arxiv.org/abs/1412.6856)
*  Inverting Visual Representations with Convolutional Networks, arXiv, 2015. [[Paper]](http://arxiv.org/abs/1506.02753)
*  Visualizing and Understanding Convolutional Networks, ECCV, 2014. [[Paper]](https://www.cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf)


### Image and Language

#### Image Captioning

* UCLA / Baidu [[Paper]](http://arxiv.org/pdf/1410.1090)
  *  Explain Images with Multimodal Recurrent Neural Networks, arXiv:1410.1090.
* Toronto [[Paper]](http://arxiv.org/pdf/1411.2539)
  *  Unifying Visual-Semantic Embeddings with Multimodal Neural Language Models, arXiv:1411.2539.
* Berkeley [[Paper]](http://arxiv.org/pdf/1411.4389)
  * Long-term Recurrent Convolutional Networks for Visual Recognition and Description, arXiv:1411.4389.
* Google [[Paper]](http://arxiv.org/pdf/1411.4555)
  * Show and Tell: A Neural Image Caption Generator, arXiv:1411.4555.
* Stanford [[Web]](http://cs.stanford.edu/people/karpathy/deepimagesent/) [[Paper]](http://cs.stanford.edu/people/karpathy/cvpr2015.pdf)
  *  Deep Visual-Semantic Alignments for Generating Image Description, CVPR, 2015.
* UML / UT [[Paper]](http://arxiv.org/pdf/1412.4729)
  * Translating Videos to Natural Language Using Deep Recurrent Neural Networks, NAACL-HLT, 2015.
* CMU / Microsoft [[Paper-arXiv]](http://arxiv.org/pdf/1411.5654) [[Paper-CVPR]](http://www.cs.cmu.edu/~xinleic/papers/cvpr15_rnn.pdf)
  *  Learning a Recurrent Visual Representation for Image Caption Generation, arXiv:1411.5654.
  *  Mind’s Eye: A Recurrent Visual Representation for Image Caption Generation, CVPR 2015
* Microsoft [[Paper]](http://arxiv.org/pdf/1411.4952)
  * From Captions to Visual Concepts and Back, CVPR, 2015.
* Univ. Montreal / Univ. Toronto [[Web](http://kelvinxu.github.io/projects/capgen.html)] [[Paper](http://www.cs.toronto.edu/~zemel/documents/captionAttn.pdf)]
  * Show, Attend, and Tell: Neural Image Caption Generation with Visual Attention, arXiv:1502.03044 / ICML 2015
* Idiap / EPFL / Facebook [[Paper](http://arxiv.org/pdf/1502.03671)]
  *  Phrase-based Image Captioning, arXiv:1502.03671 / ICML 2015
* UCLA / Baidu [[Paper](http://arxiv.org/pdf/1504.06692)]
  *  Learning like a Child: Fast Novel Visual Concept Learning from Sentence Descriptions of Images, arXiv:1504.06692
* MS + Berkeley
  *  Exploring Nearest Neighbor Approaches for Image Captioning, arXiv:1505.04467 [[Paper](http://arxiv.org/pdf/1505.04467.pdf)]
  *  Language Models for Image Captioning: The Quirks and What Works, arXiv:1505.01809 [[Paper](http://arxiv.org/pdf/1505.01809.pdf)]
* Adelaide [[Paper](http://arxiv.org/pdf/1506.01144.pdf)]
  * Image Captioning with an Intermediate Attributes Layer, arXiv:1506.01144
* Tilburg [[Paper](http://arxiv.org/pdf/1506.03694.pdf)]
  *  Learning language through pictures, arXiv:1506.03694
* Univ. Montreal [[Paper](http://arxiv.org/pdf/1507.01053.pdf)]
  * Describing Multimedia Content using Attention-based Encoder-Decoder Networks, arXiv:1507.01053
* Cornell [[Paper](http://arxiv.org/pdf/1508.02091.pdf)]
  *  Image Representations and New Domains in Neural Image Captioning, arXiv:1508.02091
* MS + City Univ. of HongKong [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Yao_Learning_Query_and_ICCV_2015_paper.pdf)]
  * "Learning Query and Image Similarities
    with Ranking Canonical Correlation Analysis", ICCV, 2015

#### Video Captioning
* Berkeley [[Web]](http://jeffdonahue.com/lrcn/) [[Paper]](http://arxiv.org/pdf/1411.4389.pdf)
  *  Long-term Recurrent Convolutional Networks for Visual Recognition and Description, CVPR, 2015.
* UT / UML / Berkeley [[Paper]](http://arxiv.org/pdf/1412.4729)
  *  Translating Videos to Natural Language Using Deep Recurrent Neural Networks, arXiv:1412.4729.
* Microsoft [[Paper]](http://arxiv.org/pdf/1505.01861)
  * Joint Modeling Embedding and Translation to Bridge Video and Language, arXiv:1505.01861.
* UT / Berkeley / UML [[Paper]](http://arxiv.org/pdf/1505.00487)
  *  Sequence to Sequence--Video to Text, arXiv:1505.00487.
* Univ. Montreal / Univ. Sherbrooke [[Paper](http://arxiv.org/pdf/1502.08029.pdf)]
  *  Describing Videos by Exploiting Temporal Structure, arXiv:1502.08029
* MPI / Berkeley [[Paper](http://arxiv.org/pdf/1506.01698.pdf)]
  *  The Long-Short Story of Movie Description, arXiv:1506.01698
* Univ. Toronto / MIT [[Paper](http://arxiv.org/pdf/1506.06724.pdf)]
  * Aligning Books and Movies: Towards Story-like Visual Explanations by Watching Movies and Reading Books, arXiv:1506.06724
* Univ. Montreal [[Paper](http://arxiv.org/pdf/1507.01053.pdf)]
  * Describing Multimedia Content using Attention-based Encoder-Decoder Networks, arXiv:1507.01053
* TAU / USC [[paper](https://arxiv.org/pdf/1612.06950.pdf)]
  *  Temporal Tessellation for Video Annotation and Summarization, arXiv:1612.06950.

#### Question Answering


* Virginia Tech / MSR [[Web]](http://www.visualqa.org/) [[Paper]](http://arxiv.org/pdf/1505.00468)
  *  VQA: Visual Question Answering, CVPR, 2015 SUNw:Scene Understanding workshop.
* MPI / Berkeley [[Web]](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/vision-and-language/visual-turing-challenge/) [[Paper]](http://arxiv.org/pdf/1505.01121)
  *  Ask Your Neurons: A Neural-based Approach to Answering Questions about Images, arXiv:1505.01121.
* Toronto [[Paper]](http://arxiv.org/pdf/1505.02074) [[Dataset]](http://www.cs.toronto.edu/~mren/imageqa/data/cocoqa/)
  *  Image Question Answering: A Visual Semantic Embedding Model and a New Dataset, arXiv:1505.02074 / ICML 2015 deep learning workshop.
* Baidu / UCLA [[Paper]](http://arxiv.org/pdf/1505.05612) [[Dataset]]()
  *  Are You Talking to a Machine? Dataset and Methods for Multilingual Image Question Answering, arXiv:1505.05612.
* POSTECH [[Paper](http://arxiv.org/pdf/1511.05756.pdf)] [[Project Page](http://cvlab.postech.ac.kr/research/dppnet/)]
  *  Image Question Answering using Convolutional Neural Network with Dynamic Parameter Prediction, arXiv:1511.05765
* CMU / Microsoft Research [[Paper](http://arxiv.org/pdf/1511.02274v2.pdf)]
  *  Stacked Attention Networks for Image Question Answering. arXiv:1511.02274.
* MetaMind [[Paper](http://arxiv.org/pdf/1603.01417v1.pdf)]
  * "Dynamic Memory Networks for Visual and Textual Question Answering." arXiv:1603.01417 (2016).
* SNU + NAVER [[Paper](http://arxiv.org/abs/1606.01455)]
  * *Multimodal Residual Learning for Visual QA*, arXiv:1606:01455
* UC Berkeley + Sony [[Paper](https://arxiv.org/pdf/1606.01847)]
  * *Multimodal Compact Bilinear Pooling for Visual Question Answering and Visual Grounding*, arXiv:1606.01847
* Postech [[Paper](http://arxiv.org/pdf/1606.03647.pdf)]
  *  *Training Recurrent Answering Units with Joint Loss Minimization for VQA*, arXiv:1606.03647
* SNU + NAVER [[Paper](http://arxiv.org/abs/1610.04325)]
  * *Hadamard Product for Low-rank Bilinear Pooling*, arXiv:1610.04325.

### Image Generation
* Convolutional / Recurrent Networks
  * "Conditional Image Generation with PixelCNN Decoders"[[Paper]](https://arxiv.org/pdf/1606.05328v2.pdf)[[Code]](https://github.com/kundan2510/pixelCNN)
  * "Learning to Generate Chairs with Convolutional Neural Networks", CVPR, 2015. [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Dosovitskiy_Learning_to_Generate_2015_CVPR_paper.pdf)
  * "DRAW: A Recurrent Neural Network For Image Generation", ICML, 2015. [[Paper](https://arxiv.org/pdf/1502.04623v2.pdf)] 
* Adversarial Networks
  * Generative Adversarial Networks, NIPS, 2014. [[Paper]](http://arxiv.org/abs/1406.2661)
  * Deep Generative Image Models using a ￼Laplacian Pyramid of Adversarial Networks, NIPS, 2015. [[Paper]](http://arxiv.org/abs/1506.05751)
  * "A note on the evaluation of generative models", ICLR 2016. [[Paper](http://arxiv.org/abs/1511.01844)]
  *  "Variationally Auto-Encoded Deep Gaussian Processes", ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06455v2.pdf)]
  * "Generating Images from Captions with Attention", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.02793v2.pdf)]
  *  "Unsupervised and Semi-supervised Learning with Categorical Generative Adversarial Networks", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.06390v1.pdf)]
  *  "Censoring Representations with an Adversary", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.05897v3.pdf)]
  * "Distributional Smoothing with Virtual Adversarial Training", ICLR 2016, [[Paper](http://arxiv.org/pdf/1507.00677v8.pdf)]
  * "Generative Visual Manipulation on the Natural Image Manifold", ECCV 2016. [[Paper](https://arxiv.org/pdf/1609.03552v2.pdf)] [[Code](https://github.com/junyanz/iGAN)] [[Video](https://youtu.be/9c4z6YsBGQ0)]
* Mixing Convolutional and Adversarial Networks
  * "Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks", ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06434.pdf)]

### Other Topics
* Visual Analogy [[Paper](https://web.eecs.umich.edu/~honglak/nips2015-analogy.pdf)]
  * Deep Visual Analogy Making, NIPS, 2015
* Surface Normal Estimation [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Designing_Deep_Networks_2015_CVPR_paper.pdf)
  * Designing Deep Networks for Surface Normal Estimation, CVPR, 2015.
* Action Detection [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Gkioxari_Finding_Action_Tubes_2015_CVPR_paper.pdf)
  * Finding Action Tubes, CVPR, 2015.
* Crowd Counting [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zhang_Cross-Scene_Crowd_Counting_2015_CVPR_paper.pdf)
  * Cross-scene Crowd Counting via Deep Convolutional Neural Networks, CVPR, 2015.
* 3D Shape Retrieval [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Sketch-Based_3D_Shape_2015_CVPR_paper.pdf)
  * Sketch-based 3D Shape Retrieval using Convolutional Neural Networks, CVPR, 2015.
* Weakly-supervised Classification
  * "Auxiliary Image Regularization for Deep CNNs with Noisy Labels", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.07069v2.pdf)]
* Artistic Style [[Paper]](http://arxiv.org/abs/1508.06576) [[Code]](https://github.com/jcjohnson/neural-style)
  *  A Neural Algorithm of Artistic Style.
* Human Gaze Estimation
  * Appearance-Based Gaze Estimation in the Wild, CVPR, 2015. [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zhang_Appearance-Based_Gaze_Estimation_2015_CVPR_paper.pdf) [[Website]](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/gaze-based-human-computer-interaction/appearance-based-gaze-estimation-in-the-wild-mpiigaze/)
* Face Recognition
  *  DeepFace: Closing the Gap to Human-Level Performance in Face Verification, CVPR, 2014. [[Paper]](https://www.cs.toronto.edu/~ranzato/publications/taigman_cvpr14.pdf)
  * DeepID3: Face Recognition with Very Deep Neural Networks, 2015. [[Paper]](http://arxiv.org/abs/1502.00873)
  * FaceNet: A Unified Embedding for Face Recognition and Clustering, CVPR, 2015. [[Paper]](http://arxiv.org/abs/1503.03832)
* Facial Landmark Detection
  * Facial Landmark Detection with Tweaked Convolutional Neural Networks, 2015. [[Paper]](http://arxiv.org/abs/1511.04031) [[Project]](http://www.openu.ac.il/home/hassner/projects/tcnn_landmarks/)
  
  ----------------

