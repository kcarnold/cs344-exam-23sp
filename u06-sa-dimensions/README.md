Suppose we have a model defined like so: 
```
model = nn.Sequential(
  nn.Linear(in_features=784, out_features=60),
  nn.ReLU(),
  nn.Linear(in_features=60, out_features=30),
  nn.ReLU(),
  nn.Linear(in_features=30, out_features=10),
)
```

How does the shape of the input tensor change after each of the layers (layer 1, layer2, and layer 3), if we were to input a tensor of `torch.Size([784])`? 
