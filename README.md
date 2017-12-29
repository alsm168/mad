# Online and Linear-Time Attention by Enforcing Monotonic Alignments

#### *NOTE* - A reference implementation of the monotonic attention mechanism is now built into TensorFlow in the `tf.contrib.seq2seq` module.  See [here](https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/monotonic_attention) for documentation.

This repository contains an example implementation of the monotonic alignment decoder proposed in ["Online and Linear-Time Attention by Enforcing Monotonic Alignments"](https://arxiv.org/abs/1704.00784), by Colin Raffel, Minh-Thang Luong, Peter J. Liu, Ron J. Weiss, and Douglas Eck (arXiv:1704.00784).

It also contains (in the `benchmark` folder) the synthetic benchmark used to compare the speed of the monotonic attention mechanism and standard softmax-based attention.
