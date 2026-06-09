# Raw HDFS Log Data

This folder is intended to contain the original HDFS log data used to generate the processed datasets utilized throughout this research project.

Dataset Source:
https://www.kaggle.com/datasets/platform934/hdfs-log-dataset

Original LogHub Repository:
https://github.com/logpai/loghub

Raw File:

* HDFS.log

The original HDFS.log file is approximately 1.58 GB and is not stored in this repository due to GitHub file size limitations.

Dataset Description:

HDFS (Hadoop Distributed File System) is a distributed file storage system designed to run on commodity hardware. The HDFS_v1 dataset was generated in a private cloud environment using benchmark workloads and manually labeled through handcrafted rules to identify anomalous behavior.

The raw log file contains system-generated events produced during HDFS operations and serves as the source from which the processed datasets were derived.

Researchers wishing to reproduce the preprocessing pipeline should download the original HDFS.log file from the dataset source listed above.

Citation:

Wei Xu, Ling Huang, Armando Fox, David Patterson, Michael Jordan. Detecting Large-Scale System Problems by Mining Console Logs. Proceedings of the 22nd ACM Symposium on Operating Systems Principles (SOSP), 2009.

Jieming Zhu, Shilin He, Pinjia He, Jinyang Liu, Michael R. Lyu. LogHub: A Large Collection of System Log Datasets for AI-driven Log Analytics. IEEE International Symposium on Software Reliability Engineering (ISSRE), 2023.
