# ScaleSplat📏
Scalable SfM-free 3D Gaussian Splatting via Memory-Representation Co-design. 

## 🎯 Project Highlights

**ScaleSplat** is a scalable, SfM-free 3D Gaussian Splatting framework designed to overcome the critical challenge of scalable 3D reconstruction under practical hardware constraints. Through a novel **memory–representation co-design**, it enables **a single, unified model** to operate effectively across **sparse-view, dense-view, and large-scale scenarios** on consumer-grade GPUs.


## 📊 Results Comparison

The following figure summarizes the key performance comparisons of ScaleSplat:

![Results Comparison](image/results_comparison.png)

*Figure 1: Relationships among reconstruction quality, end-to-end time, and required input views.*
- **(a-c)** report PSNRs versus end-to-end time under sparse-view, dense-view, and long-sequence large-scale settings, respectively.
- **(d)** reports PSNR versus the number of required input views for long-sequence large-scale scenes.
- Methods that run out of GPU memory are marked as **OOM**.

## 🚧 Code is coming soon!
We are cleaning up the implementation and will release the full training and inference pipeline shortly.
Stay tuned and watch this repository for updates.
