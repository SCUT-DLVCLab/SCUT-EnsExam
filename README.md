
# SCUT-EnsExam Release
SCUT-EnsExam is a real-world handwritten text erasure dataset for examination paper scenarios, which consists of 545 examination paper images. The dataset is randomly divided into training set and test set of 430 and 115 images, respectively. SCUT-EnsExam is now released by the Deep Learning and Visual Computing Lab of South China University of Technology. The dataset can be downloaded through the following link:
- [Baidu Cloud](https://pan.baidu.com/s/1_DMXz3Y--8ABvfy6Z1mJfw)(Size=1.14G)

Note: The SCUT-EnsExam dataset can only be used for non-commercial research purposes. For scholars or organizations who want to use the SCUT-EnsExam database, please first fill in this [Application Form](Application_Form/Application_Form_for_Using_SCUT-EnsExam.docx) and send it via email to us ([lianwen.jin@gmail.com](mailto:lianwen.jin@gmail.com) or [eelwjin@scut.edu.cn](mailto:eelwjin@scut.edu.cn)). **We will give you passwords for the dataset after your letter has been received and approved**.

## License
The SCUT-EnsExam dataset should be used and distributed under the [Creative Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) License](https://creativecommons.org/licenses/by-nc-nd/4.0/) for non-commercial research purposes.

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
@InProceedings{
    author    = {Huang, Liufeng and Chen, Bangdong and Liu, Chongyu and Peng, Dezhi and Zhou, Weiying and Wu, Yaqiang and Li, Hui and Ni, Hao and Jin, Lianwen},
    title     = {EnsExam: A Dataset for Handwritten Text Erasure on Examination Papers.},
    booktitle = {Document Analysis and Recognition – ICDAR 2023},
    month     = {August},
    year      = {2023},
    pages     = {470–485}
}
```

For any questions about the dataset, please contact the authors by sending an email to Prof. Jin([eelwjin@scut.edu.cn](mailto:eelwjin@scut.edu.cn), or [lianwen.jin@gmail.com](mailto:lianwen.jin@gmail.com)). 
