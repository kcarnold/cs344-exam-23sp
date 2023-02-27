Let 'images.shape' be 'torch.Size[(16, 3, 224, 224)]. When we run the following code, what change will be made to the images?

```python
images[:, 0] = 0.0
```
a. the images become black and white (grayscale)
b. the batch size becomes 0
c. the images only show green and blue color channels
d. a part of the images is blacked out