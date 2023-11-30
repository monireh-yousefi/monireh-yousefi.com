# Master Thesis

<p style='text-align: justify;'>
My master thesis addresses the crucial field of Face Presentation Attack Detection (PAD) with a specific focus on the application of software methods, particularly passive techniques. Due to the limitations of existing approaches, such as their difficulty in generalizing to new attacks, this study explores alternative approaches. In the initial phase of this study, I conducted an evaluation of existing models utilizing a benchmark dataset. During this analysis, I identified notable weaknesses in the performance of these models, as well as a lack of comprehensive databases for the task at hand. In response to these observations, I implemented a diverse set of data augmentation techniques. This strategic approach aimed to enhance the model's robustness, address limitations stemming from insufficient data, and ultimately contribute to a more comprehensive and reliable evaluation framework. This involved generating new data from Celeba-Spoof dataset [1] images and accommodating diverse lighting conditions and resolutions. Additionally, I created a private dataset using company customer data. Extracting images from videos, I applied face detection to the frames. My investigation delved into different classification methods, ultimately yielding significant results through multitask learning. In my thesis, I proposed a model (Figure 1) that relied on the Fourier spectrum, depth mapping, and reflection mapping. This model included an anti-spoofing detection network and a generation network for Fourier transforms, depth maps, and reflection maps. The model achieved notable results in the cross-dataset protocol, however it showed limited competitiveness in the intra-dataset protocol when compared to conventional methods.
</p>

<div style="text-align:center">
<img src="./assets/thesis_image1.png" alt="Fig1" width="700"/>
</div>
<p style="text-align: center;"><em>Figure 1. Visual representation of the multitask learning network for face spoofing attack detection</em></p>

<p style='text-align: justify;'>
Next step, I investigate the potential of Vision Transformers (ViTs) for enhancing face presentation attack detection compared to conventional methods and other deep learning architectures. My study revealed that ViTs offer several compelling advantages. Due to their ability of comprehending global spatial relationships, ViTs are capable of detecting irregularities in presentation attacks. In addition, the self-attention mechanism enables them to focus on pertinent image regions, allowing them to detect subtle details. The models I trained on Celeba-Spoof dataset achieved state-of-the-art results both in intra-dataset and cross-dataset evaluations. These findings underscore the significant potential of ViTs to enhance presentation attack detection, providing a robust defense against various spoof attacks. Notably, Swin models, a relatively new type of transformer architecture, demonstrate outstanding performance, achieving an AUC of 1, an EER of 0.02, and an ACER of 0.0196 in the intra-dataset protocol and exhibiting state-of-the-art performance on cross-dataset evaluation, demonstrating the effectiveness of ViTs in face presentation attack detection. Figure 2 illustrates the framework of the model. A paper based on my research has been written and is currently under review, awaiting publication.
</p>

<div style="text-align:center">
<img src="./assets/thesis_image3.png" alt="Fig2" width="900"/>
</div>
<p style="text-align: center;"><em>Figure 2. The structure of the transformer model</em></p>

### References

[1] Zhang, Yuanhan, et al. ”Celeba-spoof: Large-scale face antispoofing dataset with rich annotations,” in Computer Vision–ECCV 2020: 16th European Conference, Glasgow, UK, Proceedings, Part XII 16. Springer International Publishing, 2020
