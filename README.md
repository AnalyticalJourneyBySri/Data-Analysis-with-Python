# Data Analysis in Python Projects Repository
      Welcome to the Data Analysis in Python Projects repository! This repository contains a collection of projects completed as part of the IBM Data Analysis in Python course. Each project is designed to reinforce and apply the concepts learned throughout the course, providing hands-on experience in analyzing and visualizing data using Python. Throughout the course, I have acquired essential skills in handling datasets, extracting meaningful insights, and employing machine learning techniques for predictive analysis.

## Laptop Price Estimator: A Machine Learning Approach

**Problem statement**: In the era of ever-evolving technology, consumers are presented with a myriad of choices when it comes to purchasing laptops. The diverse range of specifications, features, and brands makes the decision-making process challenging. To simplify this process and empower consumers with informed choices, the goal is to develop a predictive model that can accurately estimate the price of a laptop based on its various attributes. 

**Dataset**: we would be using the dataset which is a filtered and modified version of the [Laptop Price Prediction using specifications](https://www.kaggle.com/datasets/arnabchaki/laptop-price-prediction?resource=download) containing information about various laptops available in the market. The dataset includes features such as "Manufacturer", "Category", "Screen", "GPU", "OS", "CPU_core",
"Screen_Size_inch", "CPU_frequency", "RAM_GB", "Storage_GB_SSD", "Weight_kg" and "Price". The target variable is the price of the laptop, which serves as the basis for prediction. Below are tables representing various features and their corresponding assigned numerical values. These mappings are designed to facilitate data representation and analysis within the context of the project.

Category: The category to which the laptop belongs: This parameter is mapped to numerical values in the following way:
| Category    | Assigned Value |
| ----------- | -------------- |
| Gaming      | 1              |
| Netbook     | 2              |
| Notebook    | 3              |
| Ultrabook   | 4              |
| Workstation | 5              |

GPU: The manufacturer of the GPU. This parameter is mapped to numerical values in the following way:
| GPU    | Assigned Value |
| ------ | -------------- |
| AMD    | 1              |
| Intel  | 2              |
| NVidia | 3              |

OS The operating system type (Windows or Linux): This parameter is mapped to numerical values in the following way:
| OS      | Assigned Value |
| ------- | -------------- |
| Windows | 1              |
| Linux   | 2              |

CPU_core: The type of processor used in the laptop: This parameter is mapped to numerical values in the following way:
| CPU Core           | Assigned Value |
| ------------------ | -------------- |
| Intel Pentium i3   | 3              |
| Intel Pentium i5   | 5              |
| Intel Pentium i7   | 7              |
