# Human Activity Recognition
---
#### MEng Final Year Project
#### Imperial College London
#### Department of Electrical and Electronic Engineering 2016-2020
---
##### ABSTRACT

Understanding  accurate information on human’s behaviours is one of the most important tasks in machine intelligence. Human Activity Recognition that aims to understand human activities from a video is a challenging task due to various problems including background, camera motion and dataset variations. This project concerns the research and design of deep learning model that identifies the user’s activity from its input video. Various methods of Human Activity Recognition on the UCF-101 dataset are exploited. This report proposes a CNN based architecture with three streams which allow the model to exploit the dataset under different settings. The three pathway are differentiated in frame rates. The single pathway, operates at single frame rate captures spatial information, the slow pathway operates at low frame rates captures the spatial information and the fast pathway operates at high frame rates that captures fine temporal information along with bidirectional LSTM. By experimenting various algorithms, it is observed that the proposed model achieves state-of-art performance for human action detection task. This algorithms can be embedded in software and hardware packages for real-life applications.

##### REQUIREMENTS
The project requires around 120GB of free space and GPU for training purposes. If using Imperial HPC services, Section 9 shows how to run a job.
The python dependencies can be found in requirements.txt
To install the libraries, 

```
pip install -r requirements.txt
```
