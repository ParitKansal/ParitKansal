# Parit Kansal

Machine Learning Scientist at **Xelpmoc Design and Tech** (Hyderabad, India). I build production Document AI, computer vision and multimodal systems, from VLM fine-tuning to distributed inference.

**Currently:** building FigureIQ, an AI-powered accounting automation platform.

## Selected work

* **FigureIQ**: VLM-based extraction of invoices, receipts and bank statements, an AI-Judge layer that checks results against the source image, and a QuickBooks Online integration.
* **Document understanding (Firstsource)**: DONUT extraction validated by a fine-tuned Gemma-3-4B judge; 98% field-level accuracy on 100K+ insurance documents a month.
* **Real-time video analytics (McDonald's Hyderabad)**: 325 concurrent RTSP streams across 25 stores, using YOLO, ViT + LoRA, InsightFace and XCLIP.
* **Web lead scoring (ASBL)**: 85 behavioral features over 8M+ sessions; XGBoost with clustering, served by FastAPI with SHAP explanations.

## Open source

**[google-pytorch/torch_tpu](https://github.com/google-pytorch/torch_tpu)**: PyTorch backend for TPU

* Fixed BatchNorm to update running statistics in training mode — [commit](https://github.com/google-pytorch/torch_tpu/commit/392146d0017188a237efcc07552f3a15361552a1)
* Fixed float32 accuracy in `gelu` (exact CDF via `erfc`) — [commit](https://github.com/google-pytorch/torch_tpu/commit/4b8921a7a6a2971c19e61cc063dca77d708d9723)
* Fixed `elu`/`celu` forward lowering for small negative inputs — [commit](https://github.com/google-pytorch/torch_tpu/commit/4d7b0d2a605c77ddcb3082b69791710bd8082c06)
* Reported a rounding bug in `round(decimals)` and `fake_quantize`, confirmed by the maintainers — [issue #6712](https://github.com/google-pytorch/torch_tpu/issues/6712)

## Tech stack

**ML:** PyTorch, Hugging Face, TensorFlow, scikit-learn, XGBoost, OpenCV, YOLO, LangChain<br>
**Serving and infra:** FastAPI, Docker, Redis, MongoDB, MinIO, Grafana, Loki, Weights & Biases<br>
**Languages:** Python, C++, C

## Contact

[paritkansal.in](https://paritkansal.in) · [LinkedIn](https://linkedin.com/in/paritkansal)
