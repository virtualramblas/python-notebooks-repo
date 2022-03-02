# Fast Frame Interpolation with FLAVR
[FLAVR](https://tarun005.github.io/FLAVR/) is a fast, flow-free frame interpolation method capable of single shot multi-frame prediction. It uses a customized encoder decoder architecture with spatio-temporal convolutions and channel gating to capture and interpolate complex motion trajectories between frames to generate realistic high frame rate videos.  
  
![FLAVR Model's Architecture.](https://github.com/tarun005/FLAVR/blob/main/figures/arch_dia.png)  
  
This repo hosts a notebook to apply 2x slow-motion filtering using the official [PyTorch](https://pytorch.org/) FLAVR implementation on your own videos.   