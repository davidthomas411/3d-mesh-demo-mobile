# 3d-mesh-demo-mobile

In-browser mesh tracking (InstantHMR + MHR via onnxruntime-web). No server needed.

## Atlas anatomy (experimental)

Tick **Anatomy** to overlay 114 TotalSegmentator structures (`atlas/`, about 2 MB, loaded on demand) that
follow the live body mesh (`anatomy/anatomy.js`): bones are rigid, the spine is a kinematic chain, ribs ride on
their vertebrae, and soft tissue is skinned between the chain frames (details in the companion repo's README). The atlas is built in the companion repo
`3d-mesh-demo-webcam` (`anatomy/atlas_build.py`) and shipped here as a copy.

**Atlas-based illustrative anatomy. Not patient-specific. Not for clinical use.** Source: public
TotalSegmentator dataset v2.0.1 subject `s1159` (CC BY 4.0, Wasserthal et al., Radiology: AI 2023).
Model files are under the SAM License; read it before redistributing.
