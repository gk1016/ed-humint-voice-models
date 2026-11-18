# ED HUMINT voice models (mirror)

Pinned copies of the speech models and runtime the ED HUMINT desktop client downloads for its on-device voice layer (Settings > Voice > Download). Mirrored here because the upstream files live under rolling release tags that are republished from time to time, which changed their checksums and broke installs (2026-11-07). The client pins the exact digests in `SHA256SUMS`; nothing here is modified from upstream.

| Asset | Upstream | Licence |
|---|---|---|
| `sherpa-onnx-v1.13.8-win-x64-shared-MD-Release.tar.bz2` | k2-fsa/sherpa-onnx release v1.13.8 | Apache-2.0 |
| `sherpa-onnx-nemo-parakeet-tdt-0.6b-v2-int8.tar.bz2` | k2-fsa/sherpa-onnx `asr-models` (NVIDIA NeMo parakeet-tdt-0.6b-v2, int8 export) | CC-BY-4.0 (NVIDIA) |
| `kokoro-multi-lang-v1_0.tar.bz2` | k2-fsa/sherpa-onnx `tts-models` (hexgrad Kokoro v1.0) | Apache-2.0 |

Attribution: sherpa-onnx by k2-fsa (https://github.com/k2-fsa/sherpa-onnx); Parakeet TDT 0.6B v2 by NVIDIA (https://huggingface.co/nvidia/parakeet-tdt-0.6b-v2); Kokoro by hexgrad (https://huggingface.co/hexgrad/Kokoro-82M). Not affiliated with any of them.
