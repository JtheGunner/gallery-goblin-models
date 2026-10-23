# gallery-goblin-models

ONNX model files for the AI upscale engines of [gallery-goblin](https://github.com/JtheGunner/gallery-goblin). The files are attached to the releases of this repository; gallery-goblin downloads and verifies them itself (pinned SHA-256), you do not need to fetch them by hand.

## Models

| Release | File | What it is |
| --- | --- | --- |
| `models-v1` | `realesr-general-x4v3.onnx` | ONNX export of Real-ESRGAN `realesr-general-x4v3` (4x), opset 17, dynamic batch, height and width |

## Provenance and license

The weights are `realesr-general-x4v3.pth` from the [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) release v0.2.5.0, converted from PyTorch to ONNX without changes to the weights. Real-ESRGAN is released under the BSD-3-Clause license; see its repository for the license text and copyright notice.
