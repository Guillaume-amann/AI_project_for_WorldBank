# Big Data Analysis on road attributes

The World Bank encourages awareness of traffic and road safety incidents in its future projects. The Road Safety Screening and Appraisal Tool (RSSAT) helps to integrate these concerns into project investment studies, by proposing a quantitative approach to road safety assessment. With a comprehensive list of road attributes, the World Bank analysts can identify investment opportunities in safety enhancement. Deep Learning would allow the efficient processing of large quantities of such data. The objective is to develop AI-based algorithms, leveraging purposefully trained Convolutional Neural Networks (CNN) for fast road attribute extraction from publicly available big data sources. This approach is particularly relevant in LMICs (Low and Middle-Income Countries) as it eliminates the need for costly data purchases or road video recordings. Automating road feature detection would help the World Bank evaluate more projects, thereby increasing opportunities for expansion in LMICs.

This repository is structured as follows:
* **Delivrables**: this directory contains the final report and poster, both in .pdf and .pptx formats
* **Model**: there you can find the RSSAT.py file you can run after downloading the 4 .pt files that serve as "brains" for the AI
* **Training**: this directory's only purpose is to run the command that will launch the training of YoloV8
* **Training_Results**: presents all models' results in a more or less visual manner
* **Webscraping**: this part of the repository ony concerns GoogleStreetView data extraction

## Key performance metrics

![alt text](https://github.com/Guillaume-amann/AI_project_for_WorldBank/blob/main/Traning_Results/trainLayer2/results.png?raw=true)

## Some predictions from Layer 1 - Model 2
![alt text](https://github.com/Guillaume-amann/AI_project_for_WorldBank/blob/main/Traning_Results/trainLayer2/val_batch0_pred.jpg?raw=true)

## Some predictions from Layer 2 - Model 3

![alt text](https://github.com/Guillaume-amann/AI_project_for_WorldBank/blob/main/Traning_Results/trainLayer3/val_batch1_pred.jpg?raw=true)
