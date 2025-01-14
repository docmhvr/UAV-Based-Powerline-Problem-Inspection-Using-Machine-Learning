# CMPE-295: UAV-Based Powerline Problem Inspection and Classification using Machine Learning Approaches


**Objective:**

As per the statistics provided by the U.S. Department of Energy, transmission system in the United States is made up of roughly 160,000 miles of high voltage transmission lines. To guarantee uninterrupted power delivery and grid stability, regular maintenance and monitoring of power line damages are essential. Traditionally power companies use manual inspection which requires a human operator to physically go to the location and check for anomalies. This method may cause a delay in response to the anomalies as it may not be efficient in covering vast areas and is considered to be expensive. 

In this project, we propose a Machine Learning approach to eliminate the need for manual inspection by the use of UAV. It helps in preventing any human error and due to its GPS functionality, the UAV enables precise tracking of power line faults. We used Machine Learning algorithms (YOLOv8 an dother versions) to train the system for power-line faults detection and classification. At the end of this project, we designed a user interface where users can upload the data and using this input, the trained machine learning models carry out the subsequent tasks, such as detecting the power line components (transmission tower, conductor, or insulator plate), identifying the faults by further classifying the faults into its subclasses (broken wires, missing insulator plates, vegetation on powerlines, etc.,) and report details of the detected anomalies in components on the user interface. 

## Research reference

You can find the related Research work published in IEEE, full text avaliable on researchgate here, 

[Research Paper](https://www.researchgate.net/publication/381461493_UAV-Based_Powerline_Problem_Inspection_and_Classification_using_Machine_Learning_Approaches)

## Hugging Face
The dataset used for this research is made open-sourced on Hugging Face for further research contributions. You can find the dataset in Hugging Face Hub here,

[HuggingFace Dataset](https://huggingface.co/datasets/docmhvr/powerline-components-and-faults)

**!Note:** 

The project is part of San Jose State University's Computer Engineering course: CMPE 295 - worked under the guidance of professor Dr. Jerry Gao. We are in the process of publishing a journal paper as an extension to this research paper using Hybrid approaches.
