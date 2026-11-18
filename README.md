### Open source: Google's torch_tpu (PyTorch on TPU)

* Fixed float32 accuracy in `gelu` (exact CDF via `erfc`) — [commit](https://github.com/google-pytorch/torch_tpu/commit/4b8921a7a6a2971c19e61cc063dca77d708d9723)
* Fixed `elu`/`celu` forward lowering for small negative inputs — [commit](https://github.com/google-pytorch/torch_tpu/commit/4d7b0d2a605c77ddcb3082b69791710bd8082c06)
* Found a rounding bug in `round(decimals)` and `fake_quantize`, confirmed by the maintainers — [issue #6712](https://github.com/google-pytorch/torch_tpu/issues/6712), fix in review in [#6758](https://github.com/google-pytorch/torch_tpu/pull/6758)
