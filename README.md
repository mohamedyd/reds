# REDS: Estimating the Performance of Error Detection Strategies Based on Dirtiness Profiles
Datasets usually suffer from various data quality problems or data errors. At the same time, there are various error detection strategies to detect different kinds of data errors. To effectively detect the data errors, the user has to deploy and test multiple error detection strategies. However, evaluating each error detection strategy on the new dataset requires tedious human evaluation efforts. Therefore, estimating the performance of each strategy upfront is desirable for a more effective strategy selection. Previous approaches estimate the effectiveness of an error detection strategy by evaluating the output on a data sample. This project implements a new approach to estimate the performance of error detection strategies. The intuition is that error detection strategies will perform similarly on similarly dirty datasets. Therefore, we introduce the novel concept of dirtiness profiles, which make datasets comparable with respect to their dirtiness. 


## Installation
This project is implemented on top of [abstraction layer](https://github.com/BigDaMa/abstraction-layer).


## Content
### datasets
This folder contains input datasets.

### tools
This folder contains the underlying data cleaning tools.

### results
This folder contains outputted results.

### dataset.py
This file contains the implementation of the dataset class.

### data_cleaning_tool.py
This file contains the implementation of the data cleaning tool class.

### reds.py
This file contains the implementation of the main application.