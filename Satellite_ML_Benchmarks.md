
# Models

1. **YOLO**
   - A popular object detection model used in many satellite-based detection tasks, such as ship detection.
   - Versions used: YOLOv3, YOLOv3-tiny for resource-constrained environments.
   - [YOLO GitHub Repository](https://github.com/AlexeyAB/darknet)

2. **U-Net**
   - A deep learning model widely used for segmentation tasks, especially for detecting geographical changes such as wildfires.
   - [U-Net GitHub Repository](https://github.com/zhixuhao/unet)

| Model                        | GANs | Diffusion Models | Transformers | CNNs | Other Components                                              |
|------------------------------|------|------------------|--------------|------|----------------------------------------------------------------|
| **Ref-Diff (Dong et al.)**    | ✘    | ✔                | ✘            | ✔    | Change Priors, Denoising Networks                              |
| **SkySense (Guo et al.)**     | ✘    | ✘                | ✔            | ✔    | Geo-Context Prototype Learning, Contrastive Learning           |
| **CACo (Mall et al.)**        | ✘    | ✘                | ✘            | ✔    | Contrastive Loss (Self-Supervised Learning)                    |
| **SatSynth (Toker et al.)**   | ✘    | ✔                | ✘            | ✔    | U-Net for Diffusion                                            |
| **Changen (Zheng et al.)**    | ✔    | ✘                | ✘            | ✔    | Markov Process, Semantic Change Synthesis                      |
| **GSSL (Ayush et al.)** | ✘ | ✘ | ✘ | ✔ | Geo-location Classification, Temporal Positive Pairs, Contrastive Learning |
| **SeCo (Manas et al.)**       | ✘    | ✘                | ✘            | ✔    | Temporal and Seasonal Contrast, Multi-head Network             |
| **SatMAE (Cong et al.)**      | ✘    | ✘                | ✔            | ✘    | Masked Autoencoder, Temporal and Spectral Encoding             |

