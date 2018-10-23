

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->
# tf.contrib.seq2seq.Helper

### `class tf.contrib.seq2seq.Helper`



Defined in [`tensorflow/contrib/seq2seq/python/ops/helper.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.1/tensorflow/contrib/seq2seq/python/ops/helper.py).

See the guide: [Seq2seq Library (contrib) > Dynamic Decoding](../../../../../api_guides/python/contrib.seq2seq#Dynamic_Decoding)

Helper interface.  Helper instances are used by SamplingDecoder.

## Properties

<h3 id="batch_size"><code>batch_size</code></h3>

Returns a scalar int32 tensor.



## Methods

<h3 id="initialize"><code>initialize</code></h3>

``` python
initialize(name=None)
```

Returns `(initial_finished, initial_inputs)`.

<h3 id="next_inputs"><code>next_inputs</code></h3>

``` python
next_inputs(
    time,
    outputs,
    state,
    sample_ids,
    name=None
)
```

Returns `(finished, next_inputs, next_state)`.

<h3 id="sample"><code>sample</code></h3>

``` python
sample(
    time,
    outputs,
    state,
    name=None
)
```

Returns `sample_ids`.


