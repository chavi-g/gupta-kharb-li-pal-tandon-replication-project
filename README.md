# Cloud Detection Algorithm Replication Project

The purpose of this project is to reproduce key claims from a research paper for testing the reproducbility concepts.

## Contributors

- [Ankita Pal](https://github.com/ankitapal189) [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0001-8411-968X)
- [Chavi Gupta](https://github.com/chavi-g) [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0003-3884-8456)
- [Kirti Kharb](https://github.com/KirtiKharb) [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-5066-8549)
- [Ankit Tandon](https://github.com/ankittandon) [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0001-6319-7670)
- [Yunhong Li](https://github.com/mabelli)  [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-0249-3975)

## Contents

The purpose of this project is to reproduce the cloud detection algorithm proposed by Mohajerani et al’s paper. The paper proposes an end-to-end cloud detection algorithm using Fully Convolutional Networks and claims to outperforms the state-of-the-art method over a benchmark dataset by 8.7% in Jaccard Index. We would like to check the workability and efficiency of this algorithm ideally using R. 

Paper:
Mohajerani, Sorour, and Parvaneh Saeedi. “Cloud-Net: An End-To-End Cloud Detection Algorithm for Landsat 8 Imagery.” IGARSS 2019 - 2019 IEEE International Geoscience and Remote Sensing Symposium, 2019, doi:10.1109/igarss.2019.8898776.


## Data
The links to download the dataset have been well documented in the repository provided with the code [here](https://github.com/SorourMo/38-Cloud-A-Cloud-Segmentation-Dataset/blob/master/README.md). The README.md file explains the structure of the training and test datasets. The data has also been hosted in Kaggle and is available [here](https://www.kaggle.com/sorour/38cloud-cloud-segmentation-in-satellite-images).

## Dependencies
- Windows 10, CentOS Linux release 7.5.1804
- R 3.5.3
- R Markdown 2.1
- tensorflow 2.0.0
- keras 2.2.5.0
- magick 2.3
- satellite 1.0.2

