Machine Learning Scientist at Xelpmoc Design and Tech. I build Document AI, computer vision and multimodal systems, from VLM fine-tuning to distributed inference.

[paritkansal.in](https://paritkansal.in) · [LinkedIn](https://linkedin.com/in/paritkansal)

### Work

* **FigureIQ**: AI accounting automation. VLM extraction and an AI-Judge verification layer, integrated with QuickBooks Online.
* **Document understanding (Firstsource)**: DONUT extraction checked by a fine-tuned Gemma-3-4B judge; 98% field-level accuracy on 100K+ insurance documents a month.
* **Real-time video analytics (McDonald's Hyderabad)**: 325 concurrent RTSP streams across 25 stores; YOLO, ViT + LoRA, InsightFace and XCLIP.
* **Web lead scoring (ASBL)**: 85 behavioral features over 8M+ sessions, XGBoost with clustering, served by FastAPI with SHAP explanations.

### Open source: google-pytorch/torch_tpu (PyTorch on TPU)

* Fixed float32 accuracy in `gelu` (exact CDF via `erfc`) — [commit](https://github.com/google-pytorch/torch_tpu/commit/4b8921a7a6a2971c19e61cc063dca77d708d9723)
* Fixed `elu`/`celu` forward lowering for small negative inputs — [commit](https://github.com/google-pytorch/torch_tpu/commit/4d7b0d2a605c77ddcb3082b69791710bd8082c06)
* Found a rounding bug in `round(decimals)` and `fake_quantize`, confirmed by the maintainers — [issue #6712](https://github.com/google-pytorch/torch_tpu/issues/6712), fix in review in [#6758](https://github.com/google-pytorch/torch_tpu/pull/6758)
