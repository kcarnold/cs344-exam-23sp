Suppose `images` is a Tensor, and `images.shape` is `torch.Size([9, 3, 224, 224])`. We run:

```python
result = images.mean(axis=1)
```

What is `result.shape`?
