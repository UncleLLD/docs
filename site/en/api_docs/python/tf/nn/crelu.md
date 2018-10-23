

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->
# tf.nn.crelu

### `tf.nn.crelu`

``` python
crelu(
    features,
    name=None
)
```



Defined in [`tensorflow/python/ops/nn_ops.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.1/tensorflow/python/ops/nn_ops.py).

See the guide: [Neural Network > Activation Functions](../../../../api_guides/python/nn#Activation_Functions)

Computes Concatenated ReLU.

Concatenates a ReLU which selects only the positive part of the activation
with a ReLU which selects only the *negative* part of the activation.
Note that as a result this non-linearity doubles the depth of the activations.
Source: https://arxiv.org/abs/1603.05201

#### Args:

* <b>`features`</b>: A `Tensor` with type `float`, `double`, `int32`, `int64`, `uint8`,
    `int16`, or `int8`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

  A `Tensor` with the same type as `features`.