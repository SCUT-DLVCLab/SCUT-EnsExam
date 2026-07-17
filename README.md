<img width="1554" height="452" alt="image" src="https://github.com/user-attachments/assets/cb509d03-787c-43e4-8eff-a7661d857b6e" />
# SCUT-EnsExam Release
SCUT-EnsExam is a real-world handwritten text erasure dataset for examination paper scenarios, which consists of 545 examination paper images. The dataset is randomly divided into training set and test set of 430 and 115 images, respectively. SCUT-EnsExam is now released by the Deep Learning and Visual Computing Lab of South China University of Technology. The dataset can be downloaded through the following link:
- [Baidu Cloud](https://pan.baidu.com/s/11b0SQF8YyHrov11Jlfdq-A)(Size=1.14G)
- [Google Drive](https://drive.google.com/file/d/1euZuAJ1JVhPcaRT_5EOvSxaTf09qGqvm/view?usp=sharing) (Size=1.14G)

The The SCUT-EnsExam dataset is available for **non-commercial research purposes only**. To request access, please follow these steps:

**Step 1: Download and complete the agreement:**

[application form](Application_Form/Application_Form_for_Using_SCUT-EnsExam.doc)

Have the document signed and stamped by your institution. Please also prepare 1–2 recent publications (within the last 6 years) as evidence that you or your team conduct research in handwriting verification, handwriting analysis and recognition, document image processing, or related fields.

**Step 2: Submit your application online:**

> 🔗 **[SCUT DLVC Lab Dataset Access Portal → Apply for The SCUT-EnsExam](http://121.41.49.212:9000/apply/scutensexam)**

Upload a signed document through the portal and fill out the "Recent Publications" block. Your application will be reviewed manually and you will be notified by email once a decision has been made (typically within 1–5 business days).

**Step 3: Download the dataset:**

After approval, you will receive the download link and decompression password via email.

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
