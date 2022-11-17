# SEGMENTATION OF UAV IMAGES: COMPARISON OF LIGHT SOA MODELS

This work is part of the **_"Deep Learning"_** exam project at the **_University of Bari "Aldo Moro"_**, academic year 2021-22.

* Author: **_Andrea Montemurro_**
* E-mail: <a.montemurro23@studenti.uniba.it>

## Abstract

_Image segmentation is the process of partitioning an image into meaningful regions, and applying this process to images taken from drones or other aerial devices is useful in many processes.Such images are very complex to analyse and at the same time these devices have limited computational resources: it is therefore important to use neural networks that work well even if they are not very heavy.
In this work, two state-of-the-art networks are compared, which have a relatively small number of parameters in common with others found in the literature. In particular, we want to demonstrate how the SegFormer-based model performs better on a complex dataset containing more than 20 object classes.
In our experiment, the U-Net EfficientNet architecture achieved about the 40% mIoU and the SegFormer-based model achieved the 53% mIoU, confirming that it performs very well on such complex datasets due to the structure of its encoder._

## Repository description

In the _"report.pdf"_ you can read all about the experiments, the the architecture used and what are the related works in the literature.

In the folders you can find all the material used for the experiments, in particular:

* _models_ folder contains the model files obtained from the training phase;
* _notebooks/train/_ contains the notebooks used for training the models;
* _notebooks/inference_ contains the notebook you can use to make predictions. You can also use this notebook on Kaggle.
* _images_ folder contains some images used in the readme.

## References

[1] Mo, Yujian and Wu, Yan and Yang, Xinneng and Liu, Feilin and Liao, Yujun. Review the state-of-the-art
technologies of semantic segmentation based on deep learning. In Neurocomputing, volume 493, pages 626–646.
Elsevier, 2022.

[2] Green, Glen M and Sussman, Robert W. Deforestation history of the eastern rain forests of Madagascar from
satellite images. In Science, volume 248, pages 212–215. American Association for the Advancement of Science, 1990.

[3] Richards, Daniel R and Friess, Daniel A. Rates and drivers of mangrove deforestation in Southeast Asia. In
Proceedings of the National Academy of Sciences, volume 113, pages 344–349. National Acad Sciences, 2016.
[4] Roser, Max and Ortiz-Ospina, Esteban. Global extreme poverty. In Roser, Max and Ortiz-Ospina, Esteban, Our
world in data, 2013.

[5] Cheng, Gong and Han, Junwei. A survey on object detection in optical remote sensing images. In ISPRS Journal of
Photogrammetry and Remote sensing, volume 117, pages 11–28. Elsevier, 2016.

[6] Ronneberger, Olaf and Fischer, Philipp and Brox, Thomas. U-net: Convolutional networks for biomedical image
segmentation.

[7] Shermeyer, Jacob and Hogan, Daniel and Brown, Jason and Van Etten, Adam and Weir, Nicholas and Pacifici,
Fabio and Hansch, Ronny and Bastidas, Alexei and Soenen, Scott and Bacastow, Todd and others. SpaceNet 6:
Multi-sensor all weather mapping dataset. In Proceedings of the IEEE/CVF Conference on Computer Vision and
Pattern Recognition Workshops, pages 196–197. 2020.

[8] Soman, Kritik. Rooftop detection using aerial drone imagery. In Proceedings of the ACM India Joint International
Conference on Data Science and Management of Data, pages 289–296. 2018.

[9] Sang, Dinh Viet and Minh, Nguyen Duc. Fully residual convolutional neural networks for aerial image segmentation.
In Proceedings of the Ninth International Symposium on Information and Communication Technology, pages
281–284. 2019.

[10] Chen, Liang-Chieh and Papandreou, George and Schroff, Florian and Adam, Hartwig. Rethinking atrous
convolution for semantic image segmentation. In arXiv preprint arXiv:1706.0558. 2017.
[11] Heffels, Michael R and Vanschoren, Joaquin. Aerial imagery pixel-level segmentation. In arXiv preprint
arXiv:2012.02024. 2020.

[12] Chen, Zhe and Duan, Yuchen and Wang, Wenhai and He, Junjun and Lu, Tong and Dai, Jifeng and Qiao, Yu.
Vision Transformer Adapter for Dense Predictions. In arXiv preprint arXiv:2205.08534. 2022.

[13] Xie, Enze and Wang, Wenhai and Yu, Zhiding and Anandkumar, Anima and Alvarez, Jose M and Luo, Ping.
SegFormer: Simple and efficient design for semantic segmentation with transformers. In Advances in Neural
Information Processing Systems, volume 34, pages 12077–12090. 2021.

[14] ICG Drone Dataset, https://www.tugraz.at/index.php?id=22387r

[15] Tan, Mingxing and Le, Quoc. Efficientnet: Rethinking model scaling for convolutional neural networks. In
International conference on machine learning, PMLR, pages 6105–6114. 2019.

[16] Sandler, Mark and Howard, Andrew and Zhu, Menglong and Zhmoginov, Andrey and Chen, Liang-Chieh.
Mobilenetv2: Inverted residuals and linear bottlenecks. In Proceedings of the IEEE conference on computer vision
and pattern recognition, pages 4510–4520. 2018.

[17] Dosovitskiy, Alexey and Beyer, Lucas and Kolesnikov, Alexander and Weissenborn, Dirk and Zhai, Xiaohua
and Unterthiner, Thomas and Dehghani, Mostafa and Minderer, Matthias and Heigold, Georg and Gelly, Sylvain
and others. An image is worth 16x16 words: Transformers for image recognition at scale. In arXiv preprint
arXiv:2010.11929. 2020.

[18] Segmentation Models Pytorch, https://github.com/qubvel/segmentation_models.pytorch

[19] Thomas Wolf and Lysandre Debut and Victor Sanh and Julien Chaumond and Clement Delangue and Anthony
Moi and Pierric Cistac and Tim Rault and Rémi Louf and Morgan Funtowicz and Joe Davison and Sam Shleifer
and Patrick von Platen and Clara Ma and Yacine Jernite and Julien Plu and Canwen Xu and Teven Le Scao and
Sylvain Gugger and Mariama Drame and Quentin Lhoest and Alexander M. Rush. Transformers: State-of-the-Art
Natural Language Processing. In Proceedings of the 2020 Conference on Empirical Methods in Natural Language
Processing: System Demonstrations, Association for Computational Linguistics, https://www.aclweb.org/
anthology/2020.emnlp-demos.6, pages38–45, oct. 2020.

