... is to correctly identify the systems that are under threat of cryptojacking. You can find the dataset and the problem statement here:

           https://www.kaggle.com/datasets/keshanijayasinghe/cryptojacking-attack-timeseries-dataset
Solution:

1. The approach was identifying the columns that captured statistically irregular behaviour of certain records in the dataset, and flagging those records. Records with certain number of flags were classified as problematic. Next evaluated how this analysis fared over the actual threats. 

2. A second approach was of identifying the relevant variables with high correlation with threat, and performing a K Means on only these variables. 
