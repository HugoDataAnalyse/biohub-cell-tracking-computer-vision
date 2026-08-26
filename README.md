Overview
This repository contains the complete documentation, code, and workflow used for spatio-temporal cell tracking. The approach is optimized for high-accuracy volumetric tracking, robust cell division handling, and missing-frame interpolation.

Key Features
End-to-End Workflow: Volumetric preprocessing, multi-GPU parallel inference shards, and graph post-processing.

Ensemble & Consensus Strategy: Dual-seed consensus with adaptive edge and detection weighting to stabilize predictions.

Geometric Refinement & Gap Closing: Advanced post-processing techniques to bridge missing frames, filter short tracks, and geometrically adjust cell divisions.

Architecture
3D UNet: For precise volumetric cell detection and segmentation.

Node-Transformer: To model long-range spatio-temporal dependencies between cell nodes across frames.

Integer Linear Programming (ILP): Global graph resolution enforcing strict biological and physical tracking constraints.
