You can treat the first model for locating dog eyes as a pre-trained model and alter to create the new model to determine if both cat eyes are visible.

First remove the last layer (the "head") and replace it with a new head that only returns a single output (whether there are two eyes). For the first couple of epochs only train that head: leave all the other weights unchanged. Then unfreeze the rest of the model (the "body") and train it as well for some more epochs.

This reuses the weights found by the first model, so even before training the body should (hopefully) give outputs that are more relevant to the problem than they would be if the weights were randomly generated.