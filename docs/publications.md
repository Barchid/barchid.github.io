# Publications

## 2022

### Bina-Rep Event Frames: a Simple and Effective Representation for Event-based cameras
Barchid, Sami, José Mennesson, and Chaabane Djéraba. "Bina-Rep Event Frames: a Simple and Effective Representation for Event-based cameras." arXiv preprint arXiv:2202.13662 (2022). 

**Abstract:** This paper presents "Bina-Rep", a simple representation method that converts asynchronous streams of events from event cameras to a sequence of sparse and expressive event frames. By representing multiple binary event images as a single frame of -bit numbers, our method is able to obtain sparser and more expressive event frames thanks to the retained information about event orders in the original stream. Coupled with our proposed model based on a convolutional neural network, the reported results achieve state-of-the-art performance and repeatedly outperforms other common event representation methods. Our approach also shows competitive robustness against common image corruptions, compared to other representation techniques.

``` title="Bibtex"
@article{barchid2022bina,
  title={Bina-Rep Event Frames: a Simple and Effective Representation for Event-based cameras},
  author={Barchid, Sami and Mennesson, Jos{\'e} and Dj{\'e}raba, Chaabane},
  journal={arXiv preprint arXiv:2202.13662},
  year={2022}
}
```

<br/>

### Spiking Neural Networks for Frame-based and Event-based Single Object Localization
Barchid, Sami, et al. "Spiking Neural Networks for Frame-based and Event-based Single Object Localization." arXiv preprint arXiv:2206.06506 (2022).

**Abstract:** Spiking neural networks have shown much promise as an energy-efficient alternative to artificial neural networks. However, understanding the impacts of sensor noises and input encodings on the network activity and performance remains difficult with common neuromorphic vision baselines like classification. Therefore, we propose a spiking neural network approach for single object localization trained using surrogate gradient descent, for frame- and event-based sensors. We compare our method with similar artificial neural networks and show that our model has competitive/better performance in accuracy, robustness against various corruptions, and has lower energy consumption. Moreover, we study the impact of neural coding schemes for static images in accuracy, robustness, and energy efficiency. Our observations differ importantly from previous studies on bio-plausible learning rules, which helps in the design of surrogate gradient trained architectures, and offers insight to design priorities in future neuromorphic technologies in terms of noise characteristics and data encoding methods.

``` title="Bibtex"
@article{barchid2022spiking,
  title={Spiking Neural Networks for Frame-based and Event-based Single Object Localization},
  author={Barchid, Sami and Mennesson, Jos{\'e} and Eshraghian, Jason and Dj{\'e}raba, Chaabane and Bennamoun, Mohammed},
  journal={arXiv preprint arXiv:2206.06506},
  year={2022}
}
```

<br>

## 2021

### Deep Spiking Convolutional Neural Network for Single Object Localization Based On Deep Continuous Local Learning
Barchid, Sami, José Mennesson, and Chaabane Djéraba. "Deep Spiking Convolutional Neural Network for Single Object Localization Based On Deep Continuous Local Learning." 2021 International Conference on Content-Based Multimedia Indexing (CBMI). IEEE, 2021.

**Abstract:** With the advent of neuromorphic hardware, spiking neural networks can be a good energy-efficient alternative to artificial neural networks. However, the use of spiking neural networks to perform computer vision tasks remains limited, mainly focusing on simple tasks such as digit recognition. It
remains hard to deal with more complex tasks (e.g. segmentation, object detection) due to the small number of works on deep spiking neural networks for these tasks. The objective of this paper is to make the first step towards modern computer vision with supervised spiking neural networks. We propose a deep
convolutional spiking neural network for the localization of a single object in a grayscale image. We propose a network based on DECOLLE, a spiking model that enables local surrogate gradient-based learning. The encouraging results reported on Oxford-IIIT-Pet validates the exploitation of spiking neural networks with a supervised learning approach for more elaborate vision tasks in the future.

``` title="Bibtex"
@inproceedings{barchid2021deep,
  title={Deep Spiking Convolutional Neural Network for Single Object Localization Based On Deep Continuous Local Learning},
  author={Barchid, Sami and Mennesson, Jos{\'e} and Dj{\'e}raba, Chaabane},
  booktitle={2021 International Conference on Content-Based Multimedia Indexing (CBMI)},
  pages={1--5},
  year={2021},
  organization={IEEE}
}
```

<br/>

### Review on Indoor RGB-D Semantic Segmentation with Deep Convolutional Neural Networks
Barchid, Sami, José Mennesson, and Chaabane Djéraba. "Review on Indoor RGB-D Semantic Segmentation with Deep Convolutional Neural Networks." 2021 International Conference on Content-Based Multimedia Indexing (CBMI). IEEE, 2021.

``` title="Bibtex"
@inproceedings{barchid2021review,
  title={Review on Indoor RGB-D Semantic Segmentation with Deep Convolutional Neural Networks},
  author={Barchid, Sami and Mennesson, Jos{\'e} and Dj{\'e}raba, Chaabane},
  booktitle={2021 International Conference on Content-Based Multimedia Indexing (CBMI)},
  pages={1--4},
  year={2021},
  organization={IEEE}
}
```

**Abstract:** Many research works focus on leveraging the complementary geometric information of indoor depth sensors in vision tasks performed by deep convolutional neural networks, notably semantic segmentation. These works deal with a specific vision task known as "RGB-D Indoor Semantic Segmentation". The challenges and resulting solutions of this task differ from its standard RGB counterpart. This results in a new active research topic. The objective of this paper is to introduce the field of Deep Convolutional Neural Networks for RGB-D Indoor Semantic Segmentation. This review presents the most popular public datasets, proposes a categorization of the strategies employed by recent contributions, evaluates the performance of the current state-of-the-art, and discusses the remaining challenges and promising directions for future works.

<br/>