# Topic-on-Table-Processing
This is a survey on the topic of Table Processing:blush:

## Brief introduction to Table Processing Problems and this Repository
**Table Processing** has long been a difficult problem for computer researchers. The mainstream of the academic world is to divide the problem of table processing into **Table detection** and **Table Structure Recognition**. 

Especially after the rise of **Deep Learning** in 2016, many researchers have entered this field and combined deep learning methods to explore **Table Processing**, which has brought us a lot of inspiration. At the same time, there are still many problems that have not been well solved.

So this is a repository for the collection of **Table Detection** and **Table Structure Recognition** Models and Datasets based on **Deep Learning** methods.

## Classification of Table Processing papers based on different topics(Some papers will cover several topics, so they will be repeated in these topics)
### DataSet (Baseline or Benchmark)
* Göbel, Max, Tamir Hassan, Ermelinda Oro, and Giorgio Orsi. "ICDAR 2013 table competition." In 2013 12th International Conference on Document Analysis and Recognition, pp. 1449-1453. IEEE, 2013 [Paper Link](https://ieeexplore.ieee.org/abstract/document/6628853), [Home Page Link](https://rrc.cvc.uab.es/).
* Gao, Liangcai, Xiaohan Yi, Zhuoren Jiang, Leipeng Hao, and Zhi Tang. "ICDAR2017 competition on page object detection." In 2017 14th IAPR International Conference on Document Analysis and Recognition (ICDAR), vol. 1, pp. 1417-1422. IEEE, 2017. [Paper Link](https://ieeexplore.ieee.org/abstract/document/8270162), [Home Page Link](https://rrc.cvc.uab.es/).
* Gao, Liangcai, Yilun Huang, Hervé Déjean, Jean-Luc Meunier, Qinqin Yan, Yu Fang, Florian Kleber, and Eva Lang. "ICDAR 2019 competition on table detection and recognition (cTDaR)." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 1510-1515. IEEE, 2019.  [Paper Link](https://ieeexplore.ieee.org/abstract/document/8978120), [Home Page Link](https://rrc.cvc.uab.es/).
* Yang, F., Hu, L., Liu, X. et al. A large-scale dataset for end-to-end table recognition in the wild. Sci Data 10, 110 (2023).  [Paper Link](https://doi.org/10.1038/s41597-023-01985-8)
* Li, Yiren, Zheng Huang, Junchi Yan, Yi Zhou, Fan Ye, and Xianhui Liu. "GFTE: graph-based financial table extraction." In International Conference on Pattern Recognition, pp. 644-658. Springer, Cham, 2021. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-68790-8_50)
* Zhong, Xu, Elaheh ShafieiBavani, and Antonio Jimeno Yepes. "Image-based table recognition: data, model, and evaluation." In European Conference on Computer Vision, pp. 564-580. Springer, Cham, 2020. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_34), [Home Page Link](https://github.com/ibm-aur-nlp/PubTabNet).
* Smock, Brandon, Rohith Pesala, and Robin Abraham. "PubTables-1M: Towards comprehensive table extraction from unstructured documents." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 4634-4642. 2022. [Paper Link](https://openaccess.thecvf.com/content/CVPR2022/html/Smock_PubTables-1M_Towards_Comprehensive_Table_Extraction_From_Unstructured_Documents_CVPR_2022_paper.html), [Home Page Link](https://github.com/microsoft/table-transformer).
* Li, Minghao, Lei Cui, Shaohan Huang, Furu Wei, Ming Zhou, and Zhoujun Li. "Tablebank: Table benchmark for image-based table detection and recognition." In Proceedings of The 12th language resources and evaluation conference, pp. 1918-1925. 2020. [Paper Link](https://aclanthology.org/2020.lrec-1.236/)
* Samari, Arash, Andrew Piper, Alison Hedley, and Mohamed Cheriet. "Weakly supervised bounding box extraction for unlabeled data in table detection." In International Conference on Pattern Recognition, pp. 339-352. Springer, Cham, 2021.[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-68787-8_25)
*  Zheng, Xinyi, Douglas Burdick, Lucian Popa, Xu Zhong, and Nancy Xin Ru Wang. "Global table extractor (gte): A framework for joint table identification and cell structure recognition using visual context." In Proceedings of the IEEE/CVF winter conference on applications of computer vision, pp. 697-706. 2021. [Paper Link](https://openaccess.thecvf.com/content/WACV2021/html/Zheng_Global_Table_Extractor_GTE_A_Framework_for_Joint_Table_Identification_WACV_2021_paper.html), [Home Page Link](https://developer.ibm.com/data/fintabnet/).

### End-to-End Methods
* Yang, F., Hu, L., Liu, X. et al. A large-scale dataset for end-to-end table recognition in the wild. Sci Data 10, 110 (2023).  [Paper Link](https://doi.org/10.1038/s41597-023-01985-8)
* Ly, N. T., Takasu, A., Nguyen, P., & Takeda, H. (2023). Rethinking Image-based Table Recognition Using Weakly Supervised Methods. arXiv preprint arXiv:2303.07641. [Paper Link]( https://arxiv.org/abs/2303.07641)
* Ly, N. T., & Takasu, A. (2023). An End-to-End Multi-Task Learning Model for Image-based Table Recognition. arXiv preprint arXiv:2303.08648. [Paper Link]( https://arxiv.org/abs/2303.08648 )
* Prasad, Devashish, Ayan Gadpal, Kshitij Kapadni, Manish Visave, and Kavita Sultanpure. "CascadeTabNet: An approach for end to end table detection and structure recognition from image-based documents." In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops, pp. 572-573. 2020. [Paper Link](https://openaccess.thecvf.com/content_CVPRW_2020/html/w34/Prasad_CascadeTabNet_An_Approach_for_End_to_End_Table_Detection_and_CVPRW_2020_paper.html)
* Guo, Zengyuan, Yuechen Yu, Pengyuan Lv, Chengquan Zhang, Haojie Li, Zhihui Wang, Kun Yao, Jingtuo Liu, and Jingdong Wang. "TRUST: An Accurate and End-to-End Table structure Recognizer Using Splitting-based Transformers." arXiv preprint arXiv:2208.14687 (2022). [Paper Link](https://arxiv.org/abs/2208.14687)
* Paliwal, Shubham Singh, D. Vishwanath, Rohit Rahul, Monika Sharma, and Lovekesh Vig. "Tablenet: Deep learning model for end-to-end table detection and tabular data extraction from scanned document images." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 128-133. IEEE, 2019. [Paper Link](https://ieeexplore.ieee.org/abstract/document/8978013)
* Hashmi, Khurram Azeem, Alain Pagani, Marcus Liwicki, Didier Stricker, and Muhammad Zeshan Afzal. "CasTabDetectoRS: cascade network for table detection in document images with recursive feature pyramid and switchable atrous convolution." Journal of Imaging 7, no. 10 (2021): 214. [Paper Link](https://www.mdpi.com/2313-433X/7/10/214)
* Agarwal, Madhav, Ajoy Mondal, and C. V. Jawahar. "Cdec-net: Composite deformable cascade network for table detection in document images." In 2020 25th International Conference on Pattern Recognition (ICPR), pp. 9491-9498. IEEE, 2021. *  [Paper Link](https://ieeexplore.ieee.org/abstract/document/9411922)
* Nazir, Danish, Khurram Azeem Hashmi, Alain Pagani, Marcus Liwicki, Didier Stricker, and Muhammad Zeshan Afzal. "HybridTabNet: Towards better table detection in scanned document images." Applied Sciences 11, no. 18 (2021): 8396.  [Paper Link]( https://www.mdpi.com/2076-3417/11/18/8396)
  
### SOTA(or just the mainstream)
* Zhong, Xu, Elaheh ShafieiBavani, and Antonio Jimeno Yepes. "Image-based table recognition: data, model, and evaluation." In European Conference on Computer Vision, pp. 564-580. Springer, Cham, 2020. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_34), [Home Page Link](https://github.com/ibm-aur-nlp/PubTabNet).
* Agarwal, Madhav, Ajoy Mondal, and C. V. Jawahar. "Cdec-net: Composite deformable cascade network for table detection in document images." In 2020 25th International Conference on Pattern Recognition (ICPR), pp. 9491-9498. IEEE, 2021. *  [Paper Link](https://ieeexplore.ieee.org/abstract/document/9411922)
* Kazdar, Takwa, Wided Souidene Mseddi, Moulay A. Akhloufi, Ala Agrebi, Marwa Jmal, and Rabah Attia. 2023. "DCTable: A Dilated CNN with Optimizing Anchors for Accurate Table Detection" Journal of Imaging 9, no. 3: 62. [Paper Link](https://doi.org/10.3390/jimaging9030062)
* Li, Junlong, Yiheng Xu, Tengchao Lv, Lei Cui, Cha Zhang, and Furu Wei. "Dit: Self-supervised pre-training for document image transformer." arXiv preprint arXiv:2203.02378 (2022). [Paper Link](https://arxiv.org/abs/2203.02378)
* Namysl, Marcin, Alexander M. Esser, Sven Behnke, and Joachim Köhler. "Tab. IAIS: Flexible Table Recognition and Semantic Interpretation System." arXiv preprint arXiv:2105.11879 (2021). [Paper Link](https://arxiv.org/abs/2105.11879)
* Zheng, Xinyi, Douglas Burdick, Lucian Popa, Xu Zhong, and Nancy Xin Ru Wang. "Global table extractor (gte): A framework for joint table identification and cell structure recognition using visual context." In Proceedings of the IEEE/CVF winter conference on applications of computer vision, pp. 697-706. 2021. [Paper Link](https://openaccess.thecvf.com/content/WACV2021/html/Zheng_Global_Table_Extractor_GTE_A_Framework_for_Joint_Table_Identification_WACV_2021_paper.html), [Home Page Link](https://developer.ibm.com/data/fintabnet/).
* Hashmi, Khurram Azeem, Didier Stricker, Marcus Liwicki, Muhammad Noman Afzal, and Muhammad Zeshan Afzal. "Guided table structure recognition through anchor optimization." IEEE Access 9 (2021): 113521-113534.  [Paper Link](https://ieeexplore.ieee.org/document/9508971)
* Nazir, Danish, Khurram Azeem Hashmi, Alain Pagani, Marcus Liwicki, Didier Stricker, and Muhammad Zeshan Afzal. "HybridTabNet: Towards better table detection in scanned document images." Applied Sciences 11, no. 18 (2021): 8396.  [Paper Link]( https://www.mdpi.com/2076-3417/11/18/8396)
* Qiao, Liang, Zaisheng Li, Zhanzhan Cheng, Peng Zhang, Shiliang Pu, Yi Niu, Wenqi Ren, Wenming Tan, and Fei Wu. "Lgpma: Complicated table structure recognition with local and global pyramid mask alignment." In International Conference on Document Analysis and Recognition, pp. 99-114. Springer, Cham, 2021. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86549-8_7)
* Xing, H., Gao, F., Long, R., Bu, J., Zheng, Q., Li, L., ... & Yu, Z. (2023). LORE: Logical Location Regression Network for Table Structure Recognition. arXiv preprint arXiv:2303.03730. [Paper Link](https://arxiv.org/abs/2303.03730)
* Liu, Hao, Xin Li, Bing Liu, Deqiang Jiang, Yinsong Liu, and Bo Ren. "Neural Collaborative Graph Machines for Table Structure Recognition." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 4533-4542. 2022.[Paper Link](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_Neural_Collaborative_Graph_Machines_for_Table_Structure_Recognition_CVPR_2022_paper.html)
* Liu, Hao, Xin Li, Bing Liu, Deqiang Jiang, Yinsong Liu, and Bo Ren. "Neural Collaborative Graph Machines for Table Structure Recognition." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 4533-4542. 2022.[Paper Link](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_Neural_Collaborative_Graph_Machines_for_Table_Structure_Recognition_CVPR_2022_paper.html)
* Li, Yibo, Yilun Huang, Ziyi Zhu, Lemeng Pan, Yongshuai Huang, Lin Du, Zhi Tang, and Liangcai Gao. "Rethinking table structure recognition using sequence labeling methods." In International Conference on Document Analysis and Recognition, pp. 541-553. Springer, Cham, 2021.[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86331-9_35)
* Ajij, Md, Sanjoy Pratihar, Diptendu Sinha Roy, and Thomas Hanne. "Robust detection of Tables in documents using scores from Table cell cores." SN Computer Science 3, no. 2 (2022): 1-19.[Paper Link]( https://link.springer.com/article/10.1007/s42979-022-01041-z)
* Ma, Chixiang, Weihong Lin, Lei Sun, and Qiang Huo. "Robust Table Detection and Structure Recognition from Heterogeneous Document Images." Pattern Recognition 133 (2023): 109006. [Paper Link](https://www.sciencedirect.com/science/article/abs/pii/S0031320322004861)
* Koci, Elvis, Maik Thiele, Oscar Romero, and Wolfgang Lehner. "A genetic-based search for adaptive table recognition in spreadsheets." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 1274-1279. IEEE, 2019. [Paper Link](https://ieeexplore.ieee.org/abstract/document/8978200/)
* Zhang, Zhenrong, Jianshu Zhang, Jun Du, and Fengren Wang. "Split, embed and merge: An accurate table structure recognizer." Pattern Recognition 126 (2022): 108565. [Paper Link](https://www.sciencedirect.com/science/article/pii/S0031320322000462)
* Pegu, Bhanupriya, Maneet Singh, Aakash Agarwal, Aniruddha Mitra, and Karamjit Singh. "Table Structure Recognition Using CoDec Encoder-Decoder." In International Conference on Document Analysis and Recognition, pp. 66-80. Springer, Cham, 2021. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86159-9_5)
* Xiao, Bin, Murat Simsek, Burak Kantarci, and Ala Abu Alkheir. "Table Structure Recognition with Conditional Attention." arXiv preprint arXiv:2203.03819 (2022). [Paper Link](https://arxiv.org/abs/2203.03819)
* Nassar, Ahmed, Nikolaos Livathinos, Maksym Lysak, and Peter Staar. "TableFormer: Table Structure Understanding with Transformers." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 4614-4623. 2022.
[Paper Link](https://openaccess.thecvf.com/content/CVPR2022/html/Nassar_TableFormer_Table_Structure_Understanding_With_Transformers_CVPR_2022_paper.html), [Home Page Link](https://github.com/IBM/SynthTabNet).
* Xue, Wenyuan, Baosheng Yu, Wen Wang, Dacheng Tao, and Qingyong Li. "Tgrnet: A table graph reconstruction network for table structure recognition." In Proceedings of the IEEE/CVF International Conference on Computer Vision, pp. 1295-1304. 2021.  [Paper Link](https://openaccess.thecvf.com/content/ICCV2021/html/Xue_TGRNet_A_Table_Graph_Reconstruction_Network_for_Table_Structure_Recognition_ICCV_2021_paper.html)
* Huang, Yilun, Qinqin Yan, Yibo Li, Yifan Chen, Xiong Wang, Liangcai Gao, and Zhi Tang. "A YOLO-based table detection method." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 813-818. IEEE, 2019. [Paper Link](https://ieeexplore.ieee.org/abstract/document/8978047)
* Li, Xiao-Hui, Fei Yin, Xu-Yao Zhang, and Cheng-Lin Liu. "Adaptive scaling for archival table structure recognition." In International Conference on Document Analysis and Recognition, pp. 80-95. Springer, Cham, 2021.[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86549-8_6)
* Li, Huichao, Lingze Zeng, Weiyu Zhang, Jianing Zhang, Ju Fan, and Meihui Zhang. "A Two-Phase Approach for Recognizing Tables with Complex Structures." In International Conference on Database Systems for Advanced Applications, pp. 587-595. Springer, Cham, 2022. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-031-00123-9_47)
* Ichikawa, Koji. "Image-Based Relation Classification Approach for Table Structure Recognition." In International Conference on Document Analysis and Recognition, pp. 632-647. Springer, Cham, 2021.[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86331-9_41)
* Gemelli, Andrea, Emanuele Vivoli, and Simone Marinai. "Graph neural networks and representation embedding for table extraction in PDF documents." arXiv preprint arXiv:2208.11203 (2022). [Paper Link](https://arxiv.org/abs/2208.11203)
* Ma, Chixiang, Weihong Lin, Lei Sun, and Qiang Huo. "Robust Table Detection and Structure Recognition from Heterogeneous Document Images." Pattern Recognition 133 (2023): 109006. [Paper Link](https://www.sciencedirect.com/science/article/abs/pii/S0031320322004861)

### Data-Centric Methods
* Liu, Hao, Xin Li, Bing Liu, Deqiang Jiang, Yinsong Liu, and Bo Ren. "Neural Collaborative Graph Machines for Table Structure Recognition." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 4533-4542. 2022.[Paper Link](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_Neural_Collaborative_Graph_Machines_for_Table_Structure_Recognition_CVPR_2022_paper.html)
* Pegu, Bhanupriya, Maneet Singh, Aakash Agarwal, Aniruddha Mitra, and Karamjit Singh. "Table Structure Recognition Using CoDec Encoder-Decoder." In International Conference on Document Analysis and Recognition, pp. 66-80. Springer, Cham, 2021. [Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86159-9_5)
* Xiao, Bin, Murat Simsek, Burak Kantarci, and Ala Abu Alkheir. "Table Structure Recognition with Conditional Attention." arXiv preprint arXiv:2203.03819 (2022). [Paper Link](https://arxiv.org/abs/2203.03819)
* Smock, Brandon, Rohith Pesala, and Robin Abraham. "Aligning benchmark datasets for table structure recognition." arXiv preprint arXiv:2303.00716 (2023). [Paper Link](https://arxiv.org/abs/2303.00716)
* Li, Xiao-Hui, Fei Yin, Xu-Yao Zhang, and Cheng-Lin Liu. "Adaptive scaling for archival table structure recognition." In International Conference on Document Analysis and Recognition, pp. 80-95. Springer, Cham, 2021.[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86549-8_6)
* Kwon, Hyebin, Joungbin An, Dongwoo Lee, and Won-Yong Shin. "DATa: Domain Adaptation-aided deep Table detection using visual–lexical representations." Knowledge-Based Systems (2022): 109946.  [Paper Link](https://doi.org/10.1016/j.knosys.2022.109946)
* Naik, Shivam, Khurram Azeem Hashmi, Alain Pagani, Marcus Liwicki, Didier Stricker, and Muhammad Zeshan Afzal. "Investigating Attention Mechanism for Page Object Detection in Document Images." Applied Sciences 12, no. 15 (2022): 7486. [Paper Link](https://www.mdpi.com/2076-3417/12/15/7486)
* Mikhailov, Andrey, and Alexey Shigarov. "Page Layout Analysis for Refining Table Extraction from PDF Documents." In 2021 Ivannikov Ispras Open Conference (ISPRAS), pp. 114-119. IEEE, 2021. [Paper Link](https://ieeexplore.ieee.org/document/9708625)
* Khan, Umar, Sohaib Zahid, Muhammad Asad Ali, Adnan Ul-Hasan, and Faisal Shafait. "TabAug: data driven augmentation for enhanced table structure recognition." In International Conference on Document Analysis and Recognition, pp. 585-601. Springer, Cham, 2021.[Paper Link](https://link.springer.com/chapter/10.1007/978-3-030-86331-9_38)
* Jain, Arushi, Shubham Paliwal, Monika Sharma, and Lovekesh Vig. "TSR-DSAW: Table Structure Recognition via Deep Spatial Association of Words." arXiv preprint arXiv:2203.06873 (2022). [Paper Link](https://arxiv.org/abs/2203.06873)

### Specific Problem 
#### Noisy problem
* Zhou, Mengxi, and Rajiv Ramnath. "A Structure-Focused Deep Learning Approach for Table Recognition from Document Images." In 2022 IEEE 46th Annual Computers, Software, and Applications Conference (COMPSAC), pp. 593-601. IEEE, 2022. [Paper Link](https://ieeexplore.ieee.org/document/9842521)
* Zucker, Arthur, Younes Belkada, Hanh Vu, and Van Nam Nguyen. "ClusTi: Clustering method for table structure recognition in scanned images." Mobile Networks and Applications 26, no. 4 (2021): 1765-1776. [Paper Link](https://link.springer.com/article/10.1007/s11036-021-01759-9#article-info)
#### Forgetting problem
* Minouei, Mohammad, Khurram Azeem Hashmi, Mohammad Reza Soheili, Muhammad Zeshan Afzal, and Didier Stricker. "Continual Learning for Table Detection in Document Images." Applied Sciences 12, no. 18 (2022): 8969.  [Paper Link](https://www.mdpi.com/2076-3417/12/18/8969)
#### Embedding problem
* Namysł, M., Esser, A.M., Behnke, S. et al. Flexible Hybrid Table Recognition and Semantic Interpretation System. SN COMPUT. SCI. 4, 246 (2023). [Paper Link](https://doi.org/10.1007/s42979-022-01659-z)
#### Distorted problem
*  Ma, Chixiang, Weihong Lin, Lei Sun, and Qiang Huo. "Robust Table Detection and Structure Recognition from Heterogeneous Document Images." Pattern Recognition 133 (2023): 109006. [Paper Link](https://www.sciencedirect.com/science/article/abs/pii/S0031320322004861)



