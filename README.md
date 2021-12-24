# IPCV-K30
Master class in Computer Science - Digital Image Processing &amp; Computer Vision (Xử lý ảnh số và Video số - Thị giác máy tính)

## Tài liệu tham khảo

[1] González, Rafael Corsino and Richard E. Woods. “Digital Image Processing.” IEEE Transactions on Pattern Analysis and Machine Intelligence PAMI-3 (1981): 242-243.

[2] Benois-Pineau, Jenny, Frédéric Precioso and Matthieu Cord. “Visual Indexing and Retrieval.” SpringerBriefs in Computer Science (2012).

## Tài liệu tham khảo phân đoạn ảnh y khoa

### Surveys

[1] Mahmoud, Amira & El-Rabaie, El-Sayed & Taha, Taha & El-Fishawy, Adel & Zahran, O. & Abd El-Samie, Fathi. (2018). Medical Image Segmentation Techniques, a Literature Review, and Some Novel Trends. Menoufia Journal of Electronic Engineering Research. 27. 23-58. 10.21608/mjeer.2018.63179.

[2] Taghanaki, Saeid Asgari, Kumar Abhishek, Joseph Paul Cohen, Julien Cohen-Adad and G. Hamarneh. “Deep semantic segmentation of natural and medical images: a review.” Artificial Intelligence Review 54 (2020): 137-178.

[3] Liu, X.; Song, L.; Liu, S.; Zhang, Y. A Review of Deep-Learning-Based Medical Image Segmentation Methods. Sustainability 2021, 13, 1224. https://doi.org/10.3390/su13031224

[4] N. Siddique, S. Paheding, C. P. Elkin and V. Devabhaktuni, "U-Net and Its Variants for Medical Image Segmentation: A Review of Theory and Applications," in IEEE Access, vol. 9, pp. 82031-82057, 2021, doi: 10.1109/ACCESS.2021.3086020.

[5] Ramesh, K K D & GUTHIKONDA, KIRAN & SWAPNA, Dr. KONERU & Datta, Debabrata & Rajest, s.Suman. (2021). A Review of Medical Image Segmentation Algorithms. EAI Endorsed Transactions on Pervasive Health and Technology. 7. 10.4108/eai.12-4-2021.169184. …

### Fully Convolutional Networks

[1] (FCN) Long, J.; Shelhamer, E.; Darrell, T. Fully convolutional networks for semantic segmentation. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, Boston, MA, USA, 7–12 June 2015; pp. 3431–3440.

[2] (DeepLab v1) Chen, L.C.; Papandreou, G.; Kokkinos, I.; Murphy, K.; Yuille, A.L. Semantic image segmentation with deep convolutional nets and fully connected crfs. arXiv 2014, arXiv:1412.7062.

[3] (DeepLab v2) Chen, L.C.; Papandreou, G.; Kokkinos, I.; Murphy, K.; Yuille, A.L. Deeplab: Semantic image segmentation with deep convolutional nets, atrous convolution, and fully connected crfs. IEEE Trans. Pattern Anal. Mach. Intell. 2017, 40, 834–848.

[4] (DeepLab v3) Chen, L.C.; Papandreou, G.; Schroff, F.; Adam, H. Rethinking atrous convolution for semantic image segmentation. arXiv 2017, arXiv:1706.05587.

[5] (DeepLab v3+) Chen, L.C.; Zhu, Y.; Papandreou, G.; Schroff, F.; Adam, H. Encoder-decoder with atrous separable convolution for semantic image segmentation. In Proceedings of the European Conference on Computer Vision (ECCV), Munich, Germany, 8–14 September 2018; pp. 801–818.

[6] (SegNet) Badrinarayanan, V.; Kendall, A.; Cipolla, R. Segnet: A deep convolutional encoder-decoder architecture for image segmentation. IEEE Trans. Pattern Anal. Mach. Intell. 2017, 39, 2481–2495.

[7] Zhou, X.; Takayama, R.; Wang, S.; Hara, T.; Fujita, H. Deep learning of the sectional appearances of 3D CT images for anatomical structure segmentation based on an FCN voting method. Med. Phys. 2017, 44, 5221–5233.

[8] Christ, P.F.; Elshaer, M.E.A.; Ettlinger, F.; Tatavarty, S.; Bickel, M.; Bilic, P.; Rempfler, M.; Armbruster, M.; Hoffman, F.; D’Anastasi, M.; et al. Automatic liver and lesion segmentation in CT using cascaded fully convolutional neural networks and 3D conditional random fields. In Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, Athens, Greece, 17–21 October 2016; pp. 415–423.

[9] Zhou, X.Y.; Shen, M.; Riga, C.; Yang, G.-Z.; Lee, S.-L. Focal fcn: Towards small object segmentation with limited training data. arXiv 2017, arXiv:1711.01506.

### UNet and its variants

[1] (2D UNet) Ronneberger, O.; Fischer, P.; Brox, T. U-net: Convolutional networks for biomedical image segmentation. In Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, Munich, Germany, 5–9 October 2015; pp. 234–241.

[2] (3D UNet) Çiçek, Ö.; Abdulkadir, A.; Lienkamp, S.S.; Brox, T.; Ronneberger, O. 3D U-Net: Learning dense volumetric segmentation from sparse annotation. In Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, Athens, Greece, 17–21 October 2016; pp. 424–432.

[3] (VNet) Milletari, F.; Navab, N.; Ahmadi, S.-A. V-net: Fully convolutional neural networks for volumetric medical image segmentation. In Proceedings of the 2016 Fourth International Conference on 3D Vision (3DV), Stanford, CA, USA, 25–28 October 2016; pp. 565–571.

[4] (Weighted Res-UNet) Xiao, X.; Lian, S.; Luo, Z.; Li, S. Weighted Res-UNet for high-quality retina vessel segmentation. In Proceedings of the 9th International Conference on Information Technology in Medicine and Education (ITME), Hangzhou, China, 19–21 October 2018; pp. 327–331.

[5] (Hybrid densely connected UNet) Li, X.; Chen, H.; Qi, X.; Dou, Q.; Fu, C.-W.; Heng, P.A. H-DenseUNet: Hybrid densely connected UNet for liver and tumor segmentation from CT volumes. IEEE Trans. Med. Imaging 2018, 37, 2663–2674.

[6] (MultiResUNet) Ibtehaz, N.; Rahman, M.S. MultiResUNet: Rethinking the U-Net architecture for multimodal biomedical image segmentation. Neural Netw. 2020, 121, 74–87.

[7] (Attention UNet) Oktay, O.; Schlemper, J.; Folgoc, L.L.; Lee, M.; Heinrich, M.; Misawa, K.; Mori, K.; Mcdonagh, S.; Hammerla, N.Y.; Kainz, B.; et al. Attention u-net: Learning where to look for the pancreas. arXiv 2018, arXiv:1804.03999.

[8] (Non-local UNet) Wang, Z.; Zou, N.; Shen, D.; Ji, S. Non-Local U-Nets for Biomedical Image Segmentation. In Proceedings of the AAAI, New York, NY, USA, 7–12 February 2020; pp. 6315–6322.

[9]  Cai, Yutong and Yong Wang. “MA-Unet: An improved version of Unet based on multi-scale and attention mechanism for medical image segmentation.” ArXiv abs/2012.10952 (2020): n. pag.

[10] Chen, Xiaocong, Lina Yao and Yanyan Zhang. “Residual Attention U-Net for Automated Multi-Class Segmentation of COVID-19 Chest CT Images.” ArXiv abs/2004.05645 (2020): n. pag.

[11] Chen, Jieneng, Yongyi Lu, Qihang Yu, Xiangde Luo, Ehsan Adeli, Yan Wang, Le Lu, Alan Loddon Yuille and Yuyin Zhou. “TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation.” ArXiv abs/2102.04306 (2021): n. pag.

[12] Chen, Bingzhi, Yishu Liu, Zheng Zhang, Guangming Lu and David Zhang. “TransAttUnet: Multi-level Attention-guided U-Net with Transformer for Medical Image Segmentation.” ArXiv abs/2107.05274 (2021): n. Pag. 

[13] Peiris, H.T.R., Munawar Hayat, Zhaolin Chen, Gary Egan and Mehrtash Harandi. “A Volumetric Transformer for Accurate 3D Tumor Segmentation.” ArXiv abs/2111.13300 (2021): n. pag.

[14] Zhou, Hong-Yu, Jiansen Guo, Yinghao Zhang, Lequan Yu, Liansheng Wang and Yizhou Yu. “nnFormer: Interleaved Transformer for Volumetric Segmentation.” ArXiv abs/2109.03201 (2021): n. pag.

[15] Cheng, Junlong, Chengrui Gao, Chaoqing Wang, Zhang Ming, Yong Yang and Min Zhu. “PL-Net: Progressive Learning Network for Medical Image Segmentation.” ArXiv abs/2110.14484 (2021): n. pag.

### Generative Adversarial Network

[1] Luc, P.; Couprie, C.; Chintala, S.; Verbeek, J. Semantic segmentation using adversarial networks. arXiv 2016, arXiv:1611.08408.

[2] Xue, Y.; Xu, T.; Zhang, H.; Long, L.R.; Huang, X. SegAN: Adversarial Network with Multi-scale L1 Loss for Medical Image Segmentation. Neuroinformatics 2018, 16, 383–392.

[3] Dai, W.; Dong, N.; Wang, Z.; Liang, X.; Zhang, H.; Xing, E.P. Scan: Structure correcting adversarial network for organ segmentation in chest x-rays. In Mining Data for Financial Applications; Springer: Cham, Switzerland, 2018; pp. 263–273.

[4] Khosravan, N.; Mortazi, A.; Wallace, M.; Bagci, U. Pan: Projective adversarial network for medical image segmentation. In Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, Shenzhen, China, 13–18 October 2019; pp. 68–76.

[5] Chang, Q.; Qu, H.; Zhang, Y.; Sabuncu, M.; Chen, C.; Zhang, T.; Metaxas, D.N. Synthetic Learning: Learn from Distributed Asynchronized Discriminator GAN Without Sharing Medical Image Data. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, Virtual, 14–19 June 2020; pp. 13856–13866.

[6] Zhao, M.; Wang, L.; Chen, J.; Nie, D.; Cong, Y.; Ahmad, S.; Ho, A.; Yuan, P.; Fung, S.H.; Deng, H.H.; et al. Craniomaxillofacial bony structures segmentation from MRI with deep-supervision adversarial learning. In Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, Granada, Spain, 16–20 September 2018; pp. 720–727.

[7] Mondal, A.K.; Dolz, J.; Desrosiers, C. Few-shot 3d multi-modal medical image segmentation using generative adversarial learning.
arXiv 2018, arXiv:1810.12241.

[8] Zhang, Y.; Yang, L.; Chen, J.; Fredericksen, M.; Hughes, D.P.; Chen, D.Z. Deep adversarial networks for biomedical image segmentation utilizing unannotated images. In Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, Quebec City, QC, Canada, 10–14 September 2017; pp. 408–416.

[9] Yang, D.; Xu, D.; Zhou, S.K.; Georgescu, B.; Chen, M.; Grbic, S.; Metaxas, D.; Comaniciu, D. Automatic liver segmentation using an adversarial image-to-image network. In Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention, Quebec City, QC, Canada, 10–14 September 2017; pp. 507–515.

[10] Mirza, M.; Osindero, S. Conditional generative adversarial nets. arXiv 2014, arXiv:1411.1784.

[11] Zhu, J.Y.; Park, T.; Isola, P.; Efros, A.A. Unpaired image-to-image translation using cycle-consistent adversarial networks. In Proceedings of the IEEE International Conference on Computer Vision, Venice, Italy, 22–29 October 2017; pp. 2223–2232.

[12] Bayramoglu, N.; Kaakinen, M.; Eklund, L.; Heikkila, J. Towards virtual h&e staining of hyperspectral lung histology images using conditional generative adversarial networks. In Proceedings of the IEEE International Conference on Computer Vision, Venice, Italy, 22–29 October 2017; pp. 64–71.

[13] Dar, S.U.H.; Yurt, M.; Karacan, L.; Erdem, A.; Erdem, E.; Çukur, T. Image synthesis in multi-contrast MRI with conditional generative adversarial networks. IEEE Trans. Med. Imaging 2019, 38, 2375–2388.

[14] Wolterink, J.M.; Dinkla, A.M.; Savenije, M.H.F.; Seevinck, P.R.; van den Berg, C.A.; Išgum, I. Deep MR to CT synthesis using unpaired data. In Proceedings of the International Workshop on Simulation and Synthesis in Medical Imaging, Quebec City, QC, Canada, 10 September 2017; pp. 14–23.

