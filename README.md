|                   |[1]    |[1]    |[2]    |[3]      |[4]   |[7]   |[8]    |[9]    |[10]   |
|-------------------|-------|------ |-------|---------|------|------|------ |------ |------ |
|SPLIT BY           |patient|image  |image  |patient  |image |image |image  |patient|patient| 
|OFFICIAL SPLIT     |Yes    |No     |No     |No       |No    |No    |No     |Yes    |Yes    |
|Atelectasis        |0.7003 |0.72   |0.81   |0.772    |0.80  |0.76  |0.853  |0.767  |0.733  |
|Cardiomegaly       |0.8100 |0.81   |0.904  |0.9248   |0.81  |0.91  |0.939  |0.883  |0.858  |
|Effusion           |0.7585 |0.78   |0.859  |0.8638   |0.87  |0.86  |0.903  |0.828  |0.806  |
|Infiltration       |0.6614 |0.61   |0.695  |0.7345   |0.70  |0.69  |0.754  |0.709  |0.675  |
|Mass               |0.6933 |0.71   |0.792  |0.8676   |0.83  |0.78  |0.902  |0.821  |0.727  |
|Nodule             |0.6687 |0.67   |0.717  |0.7802   |0.75  |0.70  |0.828  |0.758  |0.778  |
|Pneumonia          |0.6580 |0.63   |0.713  |0.7680   |0.67  |0.71  |0.774  |0.731  |0.690  |
|Pneumothorax       |0.7993 |0.81   |0.841  |0.8887   |0.87  |0.86  |0.921  |0.846  |0.805  |
|Consolidation      |0.7032 |0.71   |0.788  |0.7901   |0.80  |0.78  |0.842  |0.745  |0.717  |
|Edema              |0.8052 |0.83   |0.882  |0.8878   |0.88  |0.89  |0.924  |0.835  |0.806  |
|Emphysema          |0.8330 |0.81   |0.829  |0.9371   |0.91  |0.90  |0.932  |0.895  |0.842  |
|Fibrosis           |0.7859 |0.77   |0.767  |0.8047   |0.78  |0.76  |0.864  |0.818  |0.757  |
|Pleural Thickening |0.6835 |0.71   |0.765  |0.8062   |0.79  |0.77  |0.837  |0.761  |0.724  |
|Hernia             |0.8717 |0.77   |0.914  |0.9164   |0.77  |0.90  |0.921  |0.896  |0.824  |

Split by image: This repo contains the splits of train, valid and test.

Split by patient: Please be aware that the official splits by patient are only recently available [here](https://nihcc.app.box.com/v/ChestXray-NIHCC)

Please contribute to the following list:

[1] [ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases](https://arxiv.org/abs/1705.02315)

[2] [Learning to diagnose from scratch by exploiting dependencies among labels](https://arxiv.org/abs/1710.10501)

[3] [CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning](https://arxiv.org/abs/1711.05225)

[4] [Thoracic Disease Identification and Localization with Limited Supervision](https://arxiv.org/abs/1711.06373)

[5] [Learning to detect chest radiographs containing lung nodules using visual attention networks](https://arxiv.org/abs/1712.00996)(Private dataset)

[6] [TieNet: Text-Image Embedding Network for Common Thorax Disease Classification and Reporting in Chest X-rays](https://arxiv.org/abs/1801.04334) (different tasks, no improvement on using only images)

[7] [Boosted Cascaded Convnets for Multilabel Classification of Thoracic Diseases in Chest Radiographs](https://arxiv.org/abs/1711.08760)

[8] [Diagnose like a Radiologist: Attention Guided Convolutional Neural Network for Thorax Disease Classification](https://arxiv.org/abs/1801.09927)

[9] [Learning to recognize Abnormalities in Chest X-Rays with Location-Aware Dense Networks](https://arxiv.org/pdf/1803.04565.pdf) (SOTA achived with extra PLCO dataset)

[10] [Weakly Supervised Medical Diagnosis and Localization from Multiple Resolutions](https://arxiv.org/abs/1803.07703) (SOTA without using extra data)
