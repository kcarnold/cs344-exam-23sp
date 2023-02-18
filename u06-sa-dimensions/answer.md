* After layer 1: `[784]` ➡️ `[60]`
* After layer 2: `[60]` ➡️ `[30]`
* After layer 3: `[30]` ➡️ `[10]`

The input will be a Tensor with 784 items. Once it goes through the first linear layer, it will become a Tensor with 60 items, since the `out_features` of the first layer is 60. Similarly, after going through layer 2, the tensor will go through a linear transformation and its shape will be `[30]`, because the `out_features` of layer 2 is 30. The final outcome of the last layer will be a Tensor of shape `[10]`, since the `out_features` of the last layer is 10.
