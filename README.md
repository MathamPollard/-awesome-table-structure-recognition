# A Curated List of Awesome Table Structure Recognition (TSR) Research.  
 This is a curated list of awesome table structure recognition (TSR) research.Including **sota models**, influential papers, popular datasets and open-source **codes**. Continuously updating.
## Popular Datasets
|  Name      | Tables | Data Type | TD |  TSR | TCR |  Year|
|  ----      | ----    | ---- | ---- | ---- | ---- |  ----|
| [ICDAR2013](https://paperswithcode.com/dataset/icdar-2013)                       | 156   | Digital | √ | √ | √ |2013|
| [SciTSR](https://github.com/Academic-Hammer/SciTSR)                              | 15K   | Digital | × | √ | √ |2019|
| [TableBank](https://doc-analysis.github.io/tablebank-page/)                      | 417K  | Digital | √ | × | × |2020|
| [TableBank](https://doc-analysis.github.io/tablebank-page/)                      | 145K  | Digital | × | √ | × |2020|
| [PubTabNet](https://github.com/ibm-aur-nlp/PubTabNet)                            | 1M+   | Digital | × | √ | √ |2020|
| [PubTables-1M](https://github.com/microsoft/table-transformer?tab=readme-ov-file)| 1M+   | Digital | √ | √ | × |2021|
| [FinbTabNet](https://developer.ibm.com/exchanges/data/all/fintabnet/)            | 91596 | Digital | × | √ | √ |2021|
| [WTW](https://github.com/wangwen-whu/WTW-Dataset)                                | 14581 | Both    | × | √ | × |2021|  
| [SynthTabNet](https://github.com/IBM/SynthTabNet)                                | 600K  | Digital | × | √ | √ |2022|
| [TabRecSet](https://github.com/MaxKinny/TabRecSet)                               | 38177 | Both    | √ | √ | √ |2023|
| [iFLYTAB](https://github.com/ZZR8066/SEMv2?tab=readme-ov-file)                   | 12104 | Both    | √ | √ | × |2023|

**TD** means **T**able **D**etection  
**TSR** means **T**able **S**tructure **R**ecognition  
**TCD** means **T**able **C**ontent **R**ecognition  
**Both** means including both digital and physical data 
## SOTA Models 
<table class="tg">
<thead>
  <tr>
    <th class="tg-yi8c">Method Type</th>
    <th class="tg-yi8c">Method Name</th>
    <th class="tg-yi8c">Citation Count</th>
    <th class="tg-yi8c">Year</th>
    <th class="tg-yi8c">Venue</th>
    <th class="tg-z3bf">Open Source</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-mdwb" rowspan="10">Bottom-up</td>
    <td class="tg-mdwb">Res2TIM</td>
    <td class="tg-mdwb">37</td>
    <td class="tg-mdwb">2019</td>
    <td class="tg-mdwb">ICDAR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-mdwb">CascadeTabNet</td>
    <td class="tg-mdwb">182</td>
    <td class="tg-mdwb">2020</td>
    <td class="tg-3wrp">CVPR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-mdwb">TabStruct-Net</td>
    <td class="tg-mdwb">87</td>
    <td class="tg-mdwb">2020</td>
    <td class="tg-3wrp">ECCV</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">LGPMA</td>
    <td class="tg-f8mc">63</td>
    <td class="tg-f8mc">2021</td>
    <td class="tg-eav8">ICDAR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">Cycle-CenterNet</td>
    <td class="tg-f8mc">39</td>
    <td class="tg-f8mc">2021</td>
    <td class="tg-eav8">ICCV</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">TGRNet</td>
    <td class="tg-f8mc">42</td>
    <td class="tg-f8mc">2021</td>
    <td class="tg-f8mc">ICCV</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">FLAG-NET</td>
    <td class="tg-f8mc">30</td>
    <td class="tg-f8mc">2021</td>
    <td class="tg-eav8">MM</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">GTE</td>
    <td class="tg-f8mc">116</td>
    <td class="tg-f8mc">2021</td>
    <td class="tg-eav8">WACV</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">NCGM</td>
    <td class="tg-f8mc">25</td>
    <td class="tg-f8mc">2022</td>
    <td class="tg-f8mc">CVPR</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">LORE</td>
    <td class="tg-f8mc">7</td>
    <td class="tg-f8mc">2023</td>
    <td class="tg-f8mc">AAAI</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc" rowspan="6">Image2Markup</td>
    <td class="tg-f8mc">EDD</td>
    <td class="tg-f8mc">171</td>
    <td class="tg-f8mc">2020</td>
    <td class="tg-f8mc">ECCV</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">TableMaster</td>
    <td class="tg-f8mc">34</td>
    <td class="tg-f8mc">2021</td>
    <td class="tg-eav8">ICDAR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">TableFormer</td>
    <td class="tg-f8mc">41</td>
    <td class="tg-f8mc">2022</td>
    <td class="tg-f8mc">CVPR</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">VAST</td>
    <td class="tg-f8mc">12</td>
    <td class="tg-f8mc">2023</td>
    <td class="tg-f8mc">CVPR</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">UniTable</td>
    <td class="tg-f8mc"></td>
    <td class="tg-f8mc">2024</td>
    <td class="tg-f8mc"></td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">OminParser</td>
    <td class="tg-f8mc"></td>
    <td class="tg-f8mc">2024</td>
    <td class="tg-f8mc">CVPR</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc" rowspan="6">Split-and-Merge Based</td>
    <td class="tg-f8mc">SPLERGE</td>
    <td class="tg-f8mc">91</td>
    <td class="tg-f8mc">2019</td>
    <td class="tg-eav8">ICDAR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">SEM</td>
    <td class="tg-f8mc">40</td>
    <td class="tg-f8mc">2022</td>
    <td class="tg-eav8">PR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">TSRFormer</td>
    <td class="tg-f8mc">20</td>
    <td class="tg-f8mc">2022</td>
    <td class="tg-f8mc">MM</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">RobusTabNet</td>
    <td class="tg-f8mc">32</td>
    <td class="tg-f8mc">2023</td>
    <td class="tg-f8mc">PR</td>
    <td class="tg-f8mc"></td>
  </tr>
  <tr>
    <td class="tg-f8mc">SEMv2</td>
    <td class="tg-f8mc">3</td>
    <td class="tg-f8mc">2024</td>
    <td class="tg-eav8">PR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">TSRFormer-DQ-DETR</td>
    <td class="tg-f8mc"> </td>
    <td class="tg-f8mc">2024</td>
    <td class="tg-eav8">PR</td>
    <td class="tg-f8mc"> </td>
  </tr>
  <tr>
    <td class="tg-f8mc" rowspan="3">Others</td>
    <td class="tg-f8mc">TableNet</td>
    <td class="tg-f8mc">188</td>
    <td class="tg-f8mc">2019</td>
    <td class="tg-f8mc">ICDAR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">DETR</td>
    <td class="tg-f8mc">60</td>
    <td class="tg-f8mc">2022</td>
    <td class="tg-f8mc">CVPR</td>
    <td class="tg-f8mc">√</td>
  </tr>
  <tr>
    <td class="tg-f8mc">TRACE</td>
    <td class="tg-f8mc">3</td>
    <td class="tg-f8mc">2023</td>
    <td class="tg-f8mc">ICDAR</td>
    <td class="tg-f8mc">√</td>
  </tr>
</tbody>
</table>


## Influential Papers  
### CVPR 2024 
 + OMNIPARSER: A Unified Framework for Text Spotting, Key Information Extraction and Table Recognition-[Paper](https://arxiv.org/abs/2403.19128)
### PR 2024 
 + SEMv2: Table Separation Line Detection Based on Conditional Convolution-[Paper](https://www.semanticscholar.org/paper/SEMv2%3A-Table-Separation-Line-Detection-Based-on-Zhang-Hu/c78daabab3666d08d945098bc462f882b78803fd),
    [code](https://github.com/ZZR8066/SEMv2) 
### CVPR 2023  
  + Improving Table Structure Recognition with Visual-Alignment Sequential Coordinate Modeling-[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Improving_Table_Structure_Recognition_With_Visual-Alignment_Sequential_Coordinate_Modeling_CVPR_2023_paper.pdf)
### AAAI 2023  
  + LORE: Logical Location Regression Network for Table Structure Recognition=[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25402/25174)
### PR 2023  
  + Robust Table Detection and Structure Recognition from Heterogeneous Document Images-[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320322004861)
  + Scene table structure recognition with segmentation collaboration and alignment-[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865522003828?via%3Dihub)
### ACL 2023 
 + TableVLM: Multi-modal Pre-training for Table Structure Recognition-[Paper](https://aclanthology.org/2023.acl-long.137/) 
### ICDAR 2023  
  + TRACE: Table Reconstruction Aligned to Corner and Edges-[Paper](https://link.springer.com/chapter/10.1007/978-3-031-41734-4_29)
  + Aligning benchmark datasets for table structure recognition-[Paper](https://link.springer.com/chapter/10.1007/978-3-031-41734-4_23)
  + Optimized Table Tokenization for Table Structure Recognition-[Paper](https://link.springer.com/chapter/10.1007/978-3-031-41679-8_3)
### CVPR 2022
  + Neural Collaborative Graph Machines for Table Structure Recognition-[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Neural_Collaborative_Graph_Machines_for_Table_Structure_Recognition_CVPR_2022_paper.pdf)
  + TableFormer: Table Structure Understanding with Transformers-[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Nassar_TableFormer_Table_Structure_Understanding_With_Transformers_CVPR_2022_paper.pdf)
  + PubTables-1M: Towards comprehensive table extraction from unstructured documents-[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Smock_PubTables-1M_Towards_Comprehensive_Table_Extraction_From_Unstructured_Documents_CVPR_2022_paper.pdf),
    [code](https://github.com/microsoft/table-transformer)
### PR 2022  
  + Split, Embed and Merge: An accurate table structure recognizer-[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320322000462)
### WACV 2022  
  + Visual Understanding of Complex Table Structures from Document Images-[Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Raja_Visual_Understanding_of_Complex_Table_Structures_From_Document_Images_WACV_2022_paper.pdf)
### MM 2022  
  + TSRFormer: Table Structure Recognition with Transformers-[Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548038)
### ICCV 2021  
  + Parsing Table Structures in the Wild-[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Long_Parsing_Table_Structures_in_the_Wild_ICCV_2021_paper.pdf)
  + TGRNet: A Table Graph Reconstruction Network for Table Structure Recognition-[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Xue_TGRNet_A_Table_Graph_Reconstruction_Network_for_Table_Structure_Recognition_ICCV_2021_paper.pdf),
    [code](https://github.com/xuewenyuan/TGRNet)
### WACV 2021  
  + Global Table Extractor (GTE): A Framework for Joint Table Identification and Cell Structure Recognition Using Visual Context-[Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Zheng_Global_Table_Extractor_GTE_A_Framework_for_Joint_Table_Identification_WACV_2021_paper.pdf)
### MM 2021  
  + Show, Read and Reason: Table Structure Recognition with Flexible Context Aggregator-[Paper](https://dl.acm.org/doi/abs/10.1145/3474085.3481534)
### ICDAR 2021  
  + LGPMA: Complicated Table Structure Recognition with Local and Global Pyramid Mask Alignment-[Paper](https://link.springer.com/chapter/10.1007/978-3-030-86549-8_7)
  + PINGAN-VCGROUP’S SOLUTION FOR ICDAR 2021 COMPETITION ON SCIENTIFIC LITERATURE PARSING TASK B:TABLE RECOGNITION TO HTML-[Paper](https://www.semanticscholar.org/paper/PingAn-VCGroup%27s-Solution-for-ICDAR-2021-on-Table-He-Qi/754087ddb922b22873c20b3b4eec3272898326d9),
    [code](https://github.com/JiaquanYe/TableMASTER-mmocr)
  + TabLeX: A Benchmark Dataset for Structure and Content Information Extraction from Scientific Tables-[Paper](https://link.springer.com/chapter/10.1007/978-3-030-86331-9_36)
### CVPRW 2020  
  + CascadeTabNet: An approach for end to end table detection and structure recognition from image-based documents-[Paper](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w34/Prasad_CascadeTabNet_An_Approach_for_End_to_End_Table_Detection_and_CVPRW_2020_paper.pdf),
    [code](https://github.com/DevashishPrasad/CascadeTabNet)
### ECCV 2020  
  + Image-based table recognition: data, model, and evaluation-[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660562.pdf)
  + Table Structure Recognition using Top-Down and Bottom-Up Cues-[Paper](https://link.springer.com/chapter/10.1007/978-3-030-58604-1_5)
### LERC 2020  
  + TableBank: Table Benchmark for Image-based Table Detection and Recognition-[Paper](https://aclanthology.org/2020.lrec-1.236/)
### ICDAR 2019  
  + Challenges in end-to-end neural scientific table recognition-[Paper](https://ieeexplore.ieee.org/document/8978078)
  + Deep Splitting and Merging for Table Structure Decomposition-[Paper](https://ieeexplore.ieee.org/document/8977975)
  + DeepTabStR: Deep Learning based Table Structure Recognition-[Paper](https://ieeexplore.ieee.org/document/8978137)
  + Rethinking Table Recognition using Graph Neural Networks-[Paper](https://www.computer.org/csdl/proceedings-article/icdar/2019/301400a142/1h81qHhrzaM)
  + ReS2TIM: Reconstruct Syntactic Structures from Table Images-[Paper](https://ieeexplore.ieee.org/document/8978027)
  + TableNet: Deep Learning model for end-to-end Table detection and Tabular data extraction from Scanned Document Images-[Paper](https://www.computer.org/csdl/proceedings-article/icdar/2019/301400a128/1h81vwkHTwY),[code](https://github.com/AmanSavaria1402/TableNet),[model](https://drive.google.com/file/d/11cl-QP5xsYmuM-IwCtc1psMH14bb7kFx/view)
## Others  
#### 2024
 + UniTable: Towards a Unified Framework for Table Structure Recognition via Self-Supervised Pretraining-[Paper](https://arxiv.org/abs/2403.04822) 
#### 2023
  + A large-scale dataset for end-to-end table recognition in the wild-[Paper](https://www.nature.com/articles/s41597-023-01985-8),[code](https://github.com/MaxKinny/TabRecSet)
#### 2021  
  + Multi-Type-TD-TSR -- Extracting Tables from Document Images using a Multi-stage Pipeline for Table Detection and Table Structure Recognition: from OCR to Structured Table Representations-[Paper](https://link.springer.com/chapter/10.1007/978-3-030-87626-5_8),
    [code](https://github.com/Psarpei/Multi-Type-TD-TSR)
## Surveys 
 + **[ICDAR 2023]** A Study on Reproducibility and Replicability of Table Structure Recognition Methods-[Paper](https://link.springer.com/chapter/10.1007/978-3-031-41679-8_1)
 + Deep Learning for Table Detection and Structure Recognition: A Survey-[Paper](https://dl.acm.org/doi/abs/10.1145/3657281)
## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=MathamPollard/awesome-table-structure-recognition&type=Date)](https://star-history.com/#MathamPollard/awesome-table-structure-recognition&Date)

