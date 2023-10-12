# YLLSOD 
# Dataset Analysis
The dataset consists of a total of 3263 pairs of images, all with a resolution of 384×384. 
As shown in the following figure, the overall distribution of the dataset is depicted by the dual-layered pie chart on the left side. 
The inner layer of the ring represents the proportions of each sub-dataset in the total dataset. 
Specifically, RGBD-385, RGBT-621, RGB-252, VDT-766, VI-789, and LL-450 account for 24%, 14%, 12%, 19%, 8%, and 23% of the total data, respectively. 
The outer layer of the ring represents the proportions of data used for training and testing within each sub-dataset in relation to the total dataset.
On the right side of the following figure, data samples from each sub-dataset are showcased. 
The first and third rows depict low-light RGB images, while the second and fourth rows display the corresponding ground truth annotations.
![data](https://github.com/woshiyll/YLLSOD/assets/56827892/7fd59e7b-9f33-47de-8427-2ac0922f948e)
# Category Analysis
The samples are categorized based on the size of salient objects into BSO (big salient object), SSO (small salient object), and MSO (multiple salient objects). 
The dataset also includes images captured under extreme darkness (ED) conditions and images with uneven illumination (UI).
Additionally, the dataset covers both indoor scenes (IS) and outdoor scenes (OS). 
This dataset serves as a fundamental resource for evaluating the performance of SOD methods in challenging low-light environments.

For specific details on dataset construction, please refer to the readme.

PS：This dataset will soon be made publicly available.
