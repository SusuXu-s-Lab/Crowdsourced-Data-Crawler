# Crowdsourced Data Crawler

This repo is an automatic data crawling pipeline that automatically scrapes data from multiple sources. This project mainly serve to the Project [Hierarchical Earthquake Casualty Information Retrieval](https://github.com/SusuXu-s-Lab/Hierarchical-Earthquake-Casualty-Information-Retrieval/) and is detailed illustrateD in the paper [Near-real-time Earthquake-induced Fatality Estimation using Crowdsourced Data and Large-Language Models](https://arxiv.org/abs/2312.03755)

## Repository Structure

- `/Waze_retrival`: Contains the source code for data retrival from Waze.
- `/News_retrival`: Contains the source code for data retrival from NewsAPI and GDELT.
- `/TikTok`: Contains the source code notebook for data retrival from TikTok.

## Instructions

Detailed instructions for each tool and script are stored in separate folders. Please refer to the specific folder for comprehensive guidelines on setup, usage, and customization options.

## Getting Started

To get started, pease follow commands below:

```bash
git clone https://github.com/c-steve-wang/Social-Media-Data-Retrival.git
cd Social-Media-Data-Retrival
pip install --upgrade pip
pip install -r requirements.txt
```

*Before start to use the code, make sure you have replace the sample url in 'area_url.txt' and 'newsapi-automation.py'.*

## ToDo
- [x] Include a new method to crawl Twitter data (Original method is dead after April, 2023).
- [x] Implement crawler on more dataset. 
- [x] Modify the paper accordingly.

## Citation
We kindly request that you cite our paper if you find our code beneficial. Your acknowledgment is greatly appreciated.
```
@article{wang2023near,
  title={Near-real-time earthquake-induced fatality estimation using crowdsourced data and large-language models},
  author={Wang, Chenguang and Engler, Davis and Li, Xuechun and Hou, James and Wald, David J and Jaiswal, Kishor and Xu, Susu},
  journal={arXiv preprint arXiv:2312.03755},
  year={2023}
}

@inproceedings{hou2022near,
  title={Near-Real-Time Seismic Human Fatality Information Retrieval from Social Media with Few-Shot Large-Language Models},
  author={Hou, James and Xu, Susu},
  booktitle={Proceedings of the 20th ACM Conference on Embedded Networked Sensor Systems},
  pages={1141--1147},
  year={2022}
}
```


## Contact
Please feel free to email sxu83[AT]jh[DOT]edu or chenguang[DOT]wang[AT]stonybrook[DOT]edu for any questions or feedback



