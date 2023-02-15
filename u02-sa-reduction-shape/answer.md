We're summing the numbers in axis 1, so axis 1 goes away. Axis 1 was the second number in `shape`, i.e., `3`. So `result.shape` is `torch.Size([9, 224, 224])`.

Note: it's fine to not include the `torch.Size()` part.
