# UnSupervised Anomaly Detection for Multivariate Time Series

I utilized this architecture during my internship at NASA's Jet Propulsion Laboratory to perform certain anomaly detection tasks for the Deep Space Network. Since the the majority of the changes made were done with respect to particular data sets that we were using, most of them have been removed, and the model is only slightly modified. In addition, a few basic techniques were implemented in the latent space exploration file to determine the key number of variables and thus a potentially effective dimension of the latent space for the model. I figured that despite the fact that I can not upload our custom and more advanced architecture that was built off of this model, sharing it as a staple method for anomaly detection in mutlivariate data is still a good idea. If you would like to run it out of the box, you can use the classic [SWat dataset], and everything should be configured to work immediately. I highly recommend reading the paper (citation below) for further details so you understand the benefits of the dual adversarially trained autoencoder architecture, and know what hyperparameters you can play with to see immediate and logical changes. 

Click on [SWat dataset] to find info on the data that can be used to run this model immediately. 

## Citation

Here is the citation for the original paper and the creators of the model architecture:

    Audibert, J., Michiardi, P., Guyard, F., Marti, S., Zuluaga, M. A. (2020).
    USAD : UnSupervised Anomaly Detection on multivariate time series.
    Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining, August 23-27, 2020

## Requirements
 * PyTorch 1.6.0
 * CUDA 10.1 (to allow use of GPU, not compulsory)


## Copyright and licensing

The authors ask that the LICENSE be present in the Github repositories if the code is used, so it can be viewed above as "LICENSE". 

[SWaT dataset]: https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/#swat
[USAD : UnSupervised Anomaly Detection on multivariate time series]: https://dl.acm.org/doi/pdf/10.1145/3394486.3403392

