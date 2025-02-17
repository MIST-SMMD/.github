# MIST-SMMD:A Spatio-Temporal Information Extraction Method Based on Multimodal Social Media Data
### [Preprint](https://www.preprints.org/manuscript/202305.1205/v2) | [Paper](https://www.mdpi.com/2220-9964/12/9/368)
<br/>

>A Spatial Information Extraction Method Based on Multi-Modal Social Media Data: A Case Study on Urban Inundation
>
>[Yilong Wu](https://github.com/uyoin),  [Yingjie Chen](https://github.com/FalleNSakura2002),[Rongyu Zhang](https://github.com/hz157), [Zhenfei Cui](http://geo.fjnu.edu.cn/main.htm), [Xinyi Liu](http://geo.fjnu.edu.cn/main.htm), [Jiayi Zhang](http://geo.fjnu.edu.cn/main.htm), [Meizhen Wang](http://dky.njnu.edu.cn/info/1213/3986.htm), [Yong Wu](http://geo.fjnu.edu.cn/3e/21/c4964a81441/page.htm)<sup>*</sup>  

Discussions about the paper are welcomed in the [discussion panel](https://github.com/discussions).

## Introduction

MIST-SMMD an innovative spatiotemporal information extraction method, which extracts the spatiotemporal information of events from multimodal data on Weibo at coarse- and fine-grained hierarchical levels and serves as a beneficial supplement to existing urban event monitoring methods.The MIST-SMMD process is comprised of three steps:

![Main Processes]([https://raw.githubusercontent.com/MIST-SMMD/.github/refs/heads/main/profile/img/mainprocess.png))

- ### Step One:
  Crawling and Preprocessing of social media data.
- ### Step Two:
  Coarse-grained extraction of spatiotemporal information.
- ### Step Three:
  Fine-grained extraction of spatial information.

To learn more about the details of the model, read the [paper](https://www.mdpi.com/journal/ijgi)

## Run MIST-SMMD

In the organization repository, we provide detailed code on the coarse-grained extraction and fine-grained extraction methods respectively, please visit the repository address for more details

### Codes
- [Coarse-grained](https://github.com/MIST-SMMD/Coarse-grained)
- [Fine-grained](https://github.com/MIST-SMMD/Fine-grained)

### Online Demo
Want to run MIST-SMMD with custom image pairs without configuring your own GPU environment? Try the Colab demo:
- Coarse-grained  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KQjqZSgTuCoWj6k4e2gpgLt1XBp37EXj?usp=sharing)
- Fine-grained  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BO1gBlShIJn0E0LILbBlghXcaQ85N5XQ?usp=sharing)

### Notes
This model is based on the [LoFTR](https://github.com/zju3dv/LoFTR) and [DETR](https://github.com/facebookresearch/detr) models for secondary development, if you want to know more about feature matching or Segment, please visit the source code.

## Privacy Data Collection Statement
Welcome to use our open-source software. This software is designed for crawling publicly available social media text and images to support users in relevant research and analysis. Before using this software, please carefully read and understand the following privacy data collection statement.
### Data Source
This software retrieves text and image information from publicly accessible APIs or web resources on social media platforms. We strictly adhere to laws and regulations and do not breach any privacy settings or use inappropriate methods to obtain data.
### Disclaimer
The data obtained using this software is public information. However, when using this data, you should comply with relevant laws, regulations, and the usage policies of social media platforms. This software is solely a data retrieval tool and is not liable for any legal disputes, privacy breaches, or similar issues arising from your use of the data.
### Data Purpose
You should use the data obtained through this software for lawful and compliant purposes, such as academic research, data analysis, and public sentiment monitoring. Data must not be used for illegal or privacy-infringing activities, including but not limited to harassment, abuse, or fraud.
### Data Storage
You should securely manage the data obtained from this software to prevent data leaks, misuse, and other such incidents. If you use the data for research or sharing, ensure sensitive personal information is appropriately anonymized to protect privacy rights.
### Non-Disclosure of Data
You are prohibited from publicly posting, displaying, or sharing the data obtained through this software, especially if it contains others' private information. You may share analysis results, summaries, or conclusions, but not the original data
### Compliance Review
When using this software to obtain data, you should review and adhere to applicable laws, regulations, and social media platform policies. Any violations will be your sole responsibility.      
### 
Please use this software with caution, respect laws and regulations, and honor others' privacy. If you have any questions or suggestions, please contact us.

