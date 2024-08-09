# PaveCap: The First Multimodal Framework for Comprehensive Pavement Condition Assessment with Dense Captioning and PCI Estimation.
> __ABSTRACT__ <br>
_This research introduces the first multimodal approach for pavement condition assessment, providing both quantitative Pavement Condition Index (PCI) predictions and qualitative descriptions. We introduce PaveCap, a novel framework for automated pavement condition assessment. The framework consists of two main parts: a Single-Shot PCI Estimation Network and a Dense Captioning Network. The PCI Estimation Network uses YOLOv8 for object detection, the Segment Anything Model (SAM) for zero-shot segmentation, and a four-layer convolutional neural network to predict PCI. The Dense Captioning Network uses a YOLOv8 backbone, a Transformer encoder-decoder architecture, and a convolutional feed-forward module to generate detailed descriptions of pavement conditions. To train and evaluate these networks, we developed a pavement dataset with bounding box annotations, textual annotations, and PCI values. The results of our PCI Estimation Network showed a strong positive correlation (0.70) between predicted and actual PCIs, demonstrating its effectiveness in automating condition assessment. Also, the Dense Captioning Network produced accurate pavement condition descriptions, evidenced by high BLEU (0.7445), GLEU (0.5893), and METEOR (0.7252) scores. Additionally, the dense captioning model handled complex scenarios well, even correcting some errors in the ground truth data. The framework developed here can greatly improve infrastructure management and decision-making in pavement maintenance._

---

![image](https://github.com/user-attachments/assets/dbae7861-df31-40cf-96ca-bdccebb6bdef)

--- 

### Results from Dense Captioning Network:
![image](https://github.com/user-attachments/assets/df80aba7-0555-4f53-aede-11c60d07d7b0)

--- 

Contact Blessing Agyei Kyem at (blessing.agyeikyem@ndsu.edu) to request for the [Dataset](https://drive.google.com/drive/folders/1KuvUORyBN7uQIIjeoaQTGYmrVEGgTPbm?usp=sharing) used for the project. 
