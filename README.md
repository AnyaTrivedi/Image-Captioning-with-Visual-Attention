# Image-Captioning-with-Visual-Attention
Image Captioning using Visual Attention

This model generates a caption for a given image, using the MS COCO Dataset. This model is based on the [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/pdf/1502.03044.pdf) model using [Soft Attention](https://arxiv.org/pdf/1409.0473.pdf).

This Encoder-Decoder based captioning model is described below:
1.  Encoder: InceptionV3 model with a fully connected CNN
2.  Decoder: RNN (GRU) and Soft attention models
