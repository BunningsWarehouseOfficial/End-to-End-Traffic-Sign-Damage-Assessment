# End-to-End Traffic Sign Damage Assessment

Code and model training information for a paper for The International Conference on Digital Image Computing: Techniques and Applications (DICTA) 2022 Sydney.

## Abstract
> Traffic sign damage monitoring is a practical issue facing large operations all over the world. Despite the scale of traffic sign damage and its consequent impact on public safety, damage audits are performed manually. By automating components of damage assessment we can greatly improve the effectiveness and efficiency of the process and in doing so alleviate its negative impact on traffic safety. In this paper, traffic sign damage assessment is explored as a computer vision problem approached with deep learning. We specifically focus on occlusion-type damages that hinder sign legibility. This paper makes several contributions. Firstly, it provides a comprehensive survey of related work on this problem. Secondly, it provides an extension to the generation of synthetic images for such a study. Most importantly, it proposes an extension of the EfficientDet object detection framework to address the challenge. It is shown that synthetic images can be successfully used to train an object detector variant to assess the level of damage, as measured between 0.0 and 1.0, in traffic signs. The extended framework achieves a damage assessment root mean squared error (RMSE) of 0.087 on a synthetic test set while maintaining a mean average precision (mAP) of 86.3% on the typical sign detection task.

## BibTex Citation
```
TODO

@inproceedings{___,
  title={End-to-End Traffic Sign Damage Assessment},
  author={Radoš, Kristian and Downes, Jack and Pham, Duc-Son and Krishna, Aneesh},
  booktitle={___},
  pages={___},
  year={2022}
}
```

# TODO

- [ ] Directory for dataset generation code? If so, leave comment in README here that a subsequent publication will cover further features of code

- [ ] Provide permalinks to the templates backgrounds used (cite Geograph contributors)

- [ ] Directory for sign detection version of EfficientDet

- [ ] Directory for TSDA version of EfficientDet

- [ ] Show experiment training details and results in README
