# Code for the proposed model: GC-EdCastX

This model effectively integrates temporal features and background field information to achieve global mesoscale eddy forecasting.

<img src="figure/GC-EdCastX.jpg" alt="model archtecture" style="zoom:80%;" />


## The hyperparameters of our model
1. input_len: The length of historical observations 
2. output_len: The length of future value
3. num_id: number of temporal features
4. input_size: 3 (It represents the dimensions after concatenating the original time series with the two temporal embeddings, set to 3.)
5. back_size: The hidden dimension of the background field encoder
6. hiden_size: 
7. num_layer,
8. vit_layer
9. dropout
10. muti_head,
11. num_samp,
12. IF_node,
13. IF_REVIN
