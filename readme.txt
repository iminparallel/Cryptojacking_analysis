The target of this article is to correctly identify the systems that are under the threat of cryptojacking. You can find the dataset, and the problem statement here:

           https://www.kaggle.com/datasets/keshanijayasinghe/cryptojacking-attack-timeseries-dataset
Solution:

The approach was identifying the columns that captured statistically irregular behaviour of certain records in the dataset, and flagging those records. Records with certain number of flags were classified as problematic. Next we evaluated how our analysis fared over the actual threats. 
