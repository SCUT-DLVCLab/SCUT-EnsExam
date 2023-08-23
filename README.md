# SCUT-EnsExam
SCUT-EnsExam is a real-world handwritten text erasure dataset for examination paper scenarios, which consists of 545 examination paper images. The dataset is randomly divided into training set and test set of 430 and 115 images, respectively. 


## License
The M<sup>6</sup>Doc dataset should be used and distributed under the [Creative Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) License](https://creativecommons.org/licenses/by-nc-nd/4.0/) for non-commercial research purposes.


## Dataset Source
The M<sup>6</sup>Doc datasets were collected from various sources, including [arXiv](https://arxiv.org/), the official website of the [Chinese People's Daily](http://paper.people.com.cn/), and [VKontakte](https://vk.com/). The source and composition of different subsets are shown below.

  * The scientific article subset includes articles obtained by searching with the keywords \"Optical Character Recognition\" and \"Document Layout Analysis\" on arXiv. PDF files were then downloaded and converted to images.
  * The textbook subset contains 2,080 scanned document images from textbooks for three grades (elementary, middle, and high school) and nine subjects (Chinese, Math, English, Physics, Chemistry, Biology, History, Geography, and Politics).
  * The test paper subset consists of 2,000 examination papers covering the same nine subjects as the textbook subset.
  * The magazine subset includes 1,000 Chinese and English magazines in PDF format, respectively. The Chinese magazines were sourced from five publishers: Global Science, The Mystery, Youth Digest, China National Geographic, and The Reader. The English magazines were sourced from five American publishers: The New Yorker, New Scientist, Scientific American, The Economist, and Time USA.
  * The newspaper subset contains 500 PDF document images from the Chinese People's Daily and the Wall Street Journal.
  * The note subset consists of students' handwritten notes in nine subjects, including 500 scanned pages.
  * The book subset contains 500 photographed images, which were acquired from 50 books with 10 pages each. Each book has a distinct layout, resulting in considerable diversity in this subset.


## Directory Format
The dataset is organized in the following directory format:
```
├── SCUT-EnsExam
    ├── train
    │   ├── all_images
    │   │── all_labels
    │   └── quad_annotation
    ├── test
        ├── all_images
        └── all_labels
        └──quad_annotation


```

## Citation and Contact
Please consider to cite our paper when you use our dataset:
```
@InProceedings{Cheng_2023_CVPR,
    author    = {Cheng, Hiuyi and Zhang, Peirong and Wu, Sihang and Zhang, Jiaxin and Zhu, Qiyuan and Xie, Zecheng and Li, Jing and Ding, Kai and Jin, Lianwen},
    title     = {M6Doc: A Large-Scale Multi-Format, Multi-Type, Multi-Layout, Multi-Language, Multi-Annotation Category Dataset for Modern Document Layout Analysis},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2023},
    pages     = {15138-15147}
}
```

For any questions about the dataset, please contact the authors by sending an email to Prof. Jin([eelwjin@scut.edu.cn](mailto:eelwjin@scut.edu.cn), or [lianwen.jin@gmail.com](mailto:lianwen.jin@gmail.com)). 
