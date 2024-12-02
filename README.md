# 1 Architecture
![Architecture](https://github.com/FOne2019/KambaAD/blob/main/figures/Architecture.png)
# 2 Result

**2.01** Overall performance comparison of KambaAD and baseline models across four real-world
multivariate datasets: SMD, MSL, SMAP, and PSM. Models are ranked from lowest to highest
performance. Precision (P), Recall (R), and F1-score (F1) are reported in percentages (%). The best
performance in each metric is highlighted in bold, and the second-best is underlined. A dash (-)
indicates that the model’s result is missing for the specific dataset.

![figure01](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure01.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223640&Signature=iUC1rvUrXyUEsLyHOs2bVttJCaI%3D)

**2.02** Multi-metric performance comparison of KambaAD, DCdetector, and AnomalyTrans-
former on the NIPS dataset. Aff-P and Aff-R denote the precision and recall for the affiliation
metric. R A R (Range AUC ROC) and R A P (Range AUC PR) represent scores based on label
transformation under the ROC and PR curves, respectively. V ROC and V RR correspond to the
volumes under the ROC and PR curve surfaces. All results are reported in percentages (%). The
best performance in each metric is highlighted in bold, and the second-best is underlined.

![figure02](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure02.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223669&Signature=VtY3v40HF2onhzv9r6IFChSwFmI%3D)

**2.03** Performance comparison between KAN (point) and the proposed KambaAD model (KAN
window) across eight real-world multivariate datasets. Precision (P), Recall (R), and F1-score (F1)
are reported in percentages (%). The best results are highlighted in bold.

![figure03](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure03.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223697&Signature=fSfmSjODQm/9yBGLdsSMhP9ibYw%3D)

**2.04** Performance comparison between the Encoder-only, Reconstruction-only, and KambaAD
across eight real-world multivariate datasets. Precision (P), Recall (R), and F1-score (F1) are re-
ported in percentages (%). The best results are highlighted in bold, and the second-best results are
underlined.

![figure04](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure04.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223780&Signature=mv5LfTXJyQ70s5c6E/J79ICDkZk%3D)

**2.05** Performance comparison between KambaAD and five ablation study models across eight
real-world multivariate datasets. Only the comparison results of the F1 score are presented. The best
results are highlighted in bold, and the second-best results are underlined.

![figure05](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure05.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223831&Signature=uw6OlYmqg%2Bj9WwWpNaDHOIzfQk0%3D)

**2.06** Parameter sensitivity studies of main hyper-parameters in KambaAD

![figure06](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure06.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223855&Signature=kNtTVkSqummf79EJ7Br//zXLWmU%3D)

**2.07** Performance comparison between channel-independent (CI) and channel-dependent (CD)
reconstruction methods across eight real-world multivariate datasets. Precision (P), Recall (R), and
F1-score (F1) are reported in percentages (%). The best results are highlighted in bold.

![figure07](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure07.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223885&Signature=KjXpD1PoAJUV%2BYuMGcCIQLAxKWg%3D)

**2.08** The presented figure illustrates the reconstruction of features 4, 12, 16, and 23 in a data
sample from PSM following the extraction of three crucial components in KambaAD, along with the
identification of anomalous points based on their reconstructed values using an optimal threshold.

![figure08](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure08.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223914&Signature=m/CXn9T/5Iaz0ApFILYnvVNIMAQ%3D)

**2.09** Dataset Statistics.

![figure09](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure09.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223943&Signature=WQRINQcZ3xfDPvlTP4V1MycZhxc%3D)

**2.10** The common hyperparameter settings used for training the model across all datasets.

![figure10](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure10.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223968&Signature=8c/4UJys%2BuQpBmoRqfVSDDTs8nQ%3D)

**2.11**The dataset-specific hyperparameter settings used for training the model on different
datasets.

![figure11](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure11.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764223992&Signature=VGgr3seLY1NAvI69BOlFOTd/Ja0%3D)

**2.12** Performance comparison of three models with different component orders: KAN-
MAMBA-attention, Attention-MAMBA-KAN, and KambaAD (KAN-attention-MAMBA) across
eight real-world multivariate datasets. Precision (P), Recall (R), and F1-score (F1) are reported in
percentages (%). The best results are highlighted in bold, and the second-best results are underlined.

![figure12](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure12.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764224018&Signature=%2Ba0pRQZkTJJ%2BcFRnrLfPMc2lJ2U%3D)

**2.13** Comparison of anomaly scores from KambaAD, DCdetector, and AnomalyTransformer
on the same data segment. The upper panel shows time series features with anomalies in red, while
the lower panel presents the models’ anomaly scores, also highlighting detected anomalies in red.

![figure13](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure13.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764224036&Signature=qaL0MQIhRNAcB8yay3Zs2fzNsEU%3D)

**2.14** Performance comparison between the Encoder-only, Reconstruction-only, and KambaAD
models across eight real-world multivariate datasets, with the model sizes kept approximately equiv-
alent. Precision (P), Recall (R), and F1-score (F1) are reported in percentages (%). The best results
are highlighted in bold, and the second-best results are underlined.

![figure14](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure14.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764224062&Signature=N7I9Klf1wBR5PKbwdpld0pMYEwM%3D)

**2.15** Comprehensive Computational Efficiency Analysis of KambaAD, AnomalyTransformer,
and DCdetector: A Comparative Study across MSL, SMAP, SMD, and PSM Datasets. Metrics
include Training Time (seconds), GPU Expend (MB), Memory Expend (MB), Model Size (MB),
and Parameter Count (millions).

![figure15](https://ywz-images.obs.cn-east-3.myhuaweicloud.com:443/XXX/figure/figure15.png?AccessKeyId=8QRQPURASOW5WE8BRAYS&Expires=1764224087&Signature=17zY68VVCGp%2Bv10GONHALEt%2BtdM%3D)

# 3 development environment
    python==3.12.5
    torch==2.2.1+cu118
    torchaudio==2.2.1+cu118
    torchinfo==1.8.0
    numpy==1.26.4
    matplotlib==3.9.2
    causal-conv1d1.2.0.post1
    mamba-ssm==1.2.0
    pandas2.2.3
    
Other components can be installed directly with pip. At the same time, you can parameter the requirements.txt file in the code, which is directly exported from the open environment.

# 4 Dataset

The data set access link is [Dataset](https://e-share.obs-website.cn-north-1.myhuaweicloud.com?token=FWC+GEMtnXh1EjYPQ0OuDoVTNY8luS8UEU1merfk3ANSy0qCpVNVPIXKZSaUGLbXaQNBmIfE1JWHgAMcwiceuchE9DDcjpHrP3QJvho4UsHFC8BCxDe4XJQz9J4+CgFJnyQLZAWhMeoG+Gh6gbFvVB7MqsyK4p5Jwt1Zup3Lu6dQP12W3c0nJek5QfeXoM2qj5xhBvAlYZHFJelnJF72ttb72fGWRy/Poi8Ex4qCaE+m7ggUi19ogtIDsBQpQ4c3+wIVjQRVTVFvmluhKMGDDfieUz+wAaYpWgHakTSQZKlloiRjG11Cs6VDem6FW7I9Y0CoI6+UX1RekfJTz/X68DzNFRcr1+azp4PPaf3IMG8G/cY6ncda61vovRX2EBJViPIOTfOHw4KThybRMkuzvz/GzGTlaHAEt/9d64hlCKetRVyLVbck5VSushL3Xa0C+onjeOI4tD0bGhqRfWs7JktuK+YAJDplJ+CNo4VA+ku8JoC0jeymSe0UOql8Z9ooCrbgZRbIW5PCvyYs+BkbUf7sKXFIQeiN3d+f017X8KA=), The extraction code is 123456。

Under datasource/anomaly, there are two directories: sources and processed. sources is the original data downloaded from the official website, processed is the data after processing, and the code for processing the data is in the src/data_provider/data_process.py file of the source code.

If it's just for training and testing, you can download only the data in the processed directory, and if you need to check the data processing, you can download the raw data in sources.

# 5 Model training parameter
Model training parameters are saved in [Parameter](https://e-share.obs-website.cn-north-1.myhuaweicloud.com?token=FWC+GEMtnXh1EjYPQ0OuDoVTNY8luS8UEU1merfk3ANSy0qCpVNVPIXKZSaUGLbXaQNBmIfE1JWHgAMcwiceuchE9DDcjpHrP3QJvho4UsHFC8BCxDe4XJQz9J4+CgFJnyQLZAWhMeoG+Gh6gbFvVB7MqsyK4p5Jwt1Zup3Lu6dQP12W3c0nJek5QfeXoM2qj5xhBvAlYZHFJelnJF72ttb72fGWRy/Poi8Ex4qCaE+m7ggUi19ogtIDsBQpQ4c3+wIVjQRVTVFvmluhKMGDDfieUz+wAaYpWgHakTSQZKlloiRjG11Cs6VDem6FW7I9Y0CoI6+UX1RekfJTz/X68DzNFRcr1+azp4PPaf3IMG8G/cY6ncda61vovRX2EBJViPIOTfOHw4KThybRMkuzvz/GzGTlaHAEt/9d64hlCKetRVyLVbck5VSushL3Xa0C+onjeOI4tD0bGhqRfWs7JktuK+YAJDplJ+CNo4VA+ku8JoC0jeymSe0UOql8Z9ooCrbgZRbIW5PCvyYs+BkbUf7sKXFIQeiN3d+f017X8KA=)，The extraction code is 123456。

The output directory contains checkpoints and results. The checkpoints contain model parameters, and the results contain random numbers selected during training, but the results vary depending on the GPU random number.

# 6 Deployment procedure
## 6.1 Deploy the environment according to Section 3
## 6.2 Download the data according to sections 4 and 5 and copy it to the project directory
## 6.3 run run.py directly