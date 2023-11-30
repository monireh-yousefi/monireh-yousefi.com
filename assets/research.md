# Research Experience

### Face Spoofing Attack Detection for Production Environment 

<p style='text-align: justify;'>
During my studies, I completed a one-year internship in Knowledge Enterprise SepidSystem’s AI department. My model was successfully utilized as a product in a real-world system by customers. Handling real-world challenges poses difficulties, as theoretical results may not always suffice. To address this, I thoroughly analyzed the production environment, identifying potential vulnerabilities and specific face spoofing attacks likely to occur. Considering factors like image quality, speed, and compatibility with existing infrastructure, I deployed a real-time face spoofing attack detection system (Figure 1). This system was seamlessly integrated with authentication processes, ensuring face liveness validation during enrollment or verification. Additionally, I actively monitored advancements in face spoofing detection research and adapted our processes to tackle emerging threats effectively.
</p>

<div style="text-align:center">
<img src="./assets/thesis_image2.png" alt="Fig1" width="700"/>
</div>
<p style="text-align: center;"><em>Figure 1. Illustration of the face spoofing attack detection Stage in an online authentication system process.</em></p>

### Farsi Speech Recognition Dataset

<p style='text-align: justify;'>
In order to contribute to the Farsi language speech recognition project, I collected a wide range of text sources, including public domain books, articles, and websites. I recorded my own voice and hired voice actors to record the speech data. I annotated the dataset with linguistic information after transcribing and ensuring accurate transcriptions. I cleaned and preprocessed the text by removing special characters, tokenizing it into sentences or smaller units, and ensuring consistent formatting. To align the text with the corresponding speech data, alignment tools were used, as well as to preprocess audio by normalizing levels, converting to a consistent format, resampling, and segmenting. I considered data augmentation for model robustness like pitch shifting, time stretching, and adding noise to create variations in the training data. In the end, the recordings were analyzed for acoustic features and encoded into a format suitable for training a speech recognition algorithm. 
</p>

### Farsi Lip Reading Dataset

<p style='text-align: justify;'>
In order to facilitate the collection of videos in which users pronounce specific words and numbers, I designed and developed a website that facilitates the collection of videos. The website link was distributed across social networks and I personally invited volunteers to participate. Afterwards, the collected videos were processed for use in the training phase of the Farsi lip reading project.  
</p>

### Face Detection for Face Recognition

<p style='text-align: justify;'>
In this project, my objective was to assess the influence of various face detection algorithms on face recognition methods. To achieve this, I employed different algorithms like MTCNN [2] and Retinaface [3] to extract facial images from the dataset. Subsequently, I trained the company’s existing face recognition model on separate data, adjusting parameters and applying preprocessing techniques to enhance performance. After thorough testing and evaluation, I integrated the most effective face detection algorithm into the server.
</p>

### Trading Support / Resistance Line Indicator

<p style='text-align: justify;'>
In this project I tried to detect effective support and resistance lines throughout an assets trading history. I used Yahoo finance for acquiring the data and to make it more useful in real life, I implemented a Pine code generator to show the results in tradingview. The code can be found <a href="https://github.com/monireh-yousefi/trading-experiments" target="_blank">here</a>.
</p>

### References

[1] Zhang, Yuanhan, et al. ”Celeba-spoof: Large-scale face antispoofing dataset with rich annotations,” in Computer Vision–ECCV 2020: 16th European Conference, Glasgow, UK, Proceedings, Part XII 16. Springer International Publishing, 2020 

[2] Zhang, Kaipeng, et al. ”Joint face detection and alignment using multitask cascaded convolutional networks,” IEEE signal processing letters, 2016, pp. 1499-1503. 

[3] Deng, Jiankang, et al. ”Retinaface: Single-shot multi-level face localisation in the wild,” Proceedings of the IEEE/CVF conference on computer vision and pattern recognition, 2020.
