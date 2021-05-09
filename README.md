<p align="center">
<h3 align="center">VLSP 2020: Relation Extraction</h3>
<p align="center">Vietnamese Relation Extraction with BERT-based Models at VLSP 2020</p>
</p>



<!-- ABOUT THE PROJECT -->
## About The Project

This project contains source code for [our approach](https://www.aclweb.org/anthology/2020.vlsp-1.6/) to solve [Relation Extraction task at VSLP 2020](https://vlsp.org.vn/vlsp2020/eval/re). The detail of our approach is described in the following paper: 

[Thuat Nguyen and Hieu Man Duc Trong. Vietnamese Relation Extraction with BERT-based 
Models at VLSP 2020. In Proceedings of the 7th International Workshop on Vietnamese Language 
and Speech Processing, 2020.](https://www.aclweb.org/anthology/2020.vlsp-1.6.pdf)

<!-- USAGE -->
## Usage

### Dataset

Please contact VLSP 2020 Organizers for dataset. You can follow their guide at: [https://vlsp.org.vn/resources](https://vlsp.org.vn/resources)

### Notebooks

In the project, we have five notebooks, you can upload and use it with [Google Colab](https://colab.research.google.com/).

* **VLSP2020_RE_extract_*[training, dev, test]***: You can use these notebooks to extract information from the raw datasets. Please remember to upload original VLSP 2020 dataset to respective notebooks. You don't need GPU to run these notebook.
* **VSLP2020_RE_model_training**: This notebook uses output extracted from the raw training and development data to train the model.
* **VLSP2020_RE_model_test**: This notebook uses saved flags.txt and pretrained model from the training notebook's output to get final results on test data. However, due to an accident, I lost the code that helps to save the final results to files in the format required by the organizers.

<!-- CONTACT -->
## Contact

Please feel free to contact me at: [nguyenhuuthuat09@gmail.com](mailto:nguyenhuuthuat09@gmail.com)

## Citation

```
@inproceedings{nguyen-man-2020-vietnamese,
    title = "{V}ietnamese Relation Extraction with {BERT}-based Models at {VLSP} 2020",
    author = "Nguyễn, Thuật  and
      Mẫn, Hiếu",
    booktitle = "Proceedings of the 7th International Workshop on Vietnamese Language and Speech Processing",
    month = dec,
    year = "2020",
    address = "Hanoi, Vietnam",
    publisher = "Association for Computational Lingustics",
    url = "https://www.aclweb.org/anthology/2020.vlsp-1.6",
    pages = "30--34",
}
```







































