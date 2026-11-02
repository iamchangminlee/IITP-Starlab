# Generating Hyper-Realistic to Extremely-Stylized Face Avatar with Varied Speech Speed and Context-based Emotional Expression

**Visual Media Lab, KAIST**

Research publications and key technologies from the **IITP Starlab** project.

## Key Technologies

### 1. Photorealistic 3D Human Facial Model Generation from a Single Image

**SSIM ↑: 0.875 → 0.887** · [GitHub](https://github.com/HyeonhoNa/Image2Face3d)

- Mapped a single facial image into a standardized latent space to generate an initial 3D human face.
- Enhanced fine-grained facial details by estimating pixel-wise 3D spatial positions from the mapped representation.

### 2. Animatable Gaussian Splatting–Based Photorealistic 3D Human Face Reconstruction from Video

**SSIM ↑: 0.930 → 0.935** · [GitHub](https://github.com/HyeonhoNa/Image2Face3d)

- Designed an initialization method for Gaussian Splatting by fitting and refining a template mesh on captured facial video.
- Separated facial and background regions, extracted key facial features, and reconstructed photorealistic 3D faces using Gaussian Splatting.

### 3. Real-Time 3D Facial Motion Capture via Expression and Pose Tracking from Video

**LMD ↓: 1.275 → 1.167** · [GitHub](https://github.com/KAIST-VML/IITP-starlab)

- Developed video-based head pose estimation for single-subject sequences.
- Implemented real-time 3D facial motion capture from preprocessed video input.

### 4. Dataset Construction of Text-Guided 3D Facial Expression Animation

**Frames ↑: 75,000 → 80,000** · [GitHub](https://github.com/LiyCg/natural-language-based-3d-facial-animation-generation/tree/main)

- Rendered captured motion-range data to build single-view animation data across various 3D face models.
- Created paired datasets by matching each rendered animation frame with its corresponding textual expression instruction.

## Publications

| Paper | Venue / Year | Technical Focus | Repository |
| --- | --- | --- | --- |
| **Neural Face Skinning for Mesh-agnostic Facial Expression Cloning** | Eurographics 2025 / [Computer Graphics Forum (CGF)](https://doi.org/10.1111/cgf.70009) | Transfer facial expressions across meshes with different shapes and structures using learned skinning weights. | [NFS](https://github.com/chacorp/NFS) |
| **FFaceNeRF: Few-shot Face Editing in Neural Radiance Fields** | [CVPR 2025](https://kwanyun.github.io/FFaceNeRF_page/) | Edit facial features in neural radiance fields using a small number of examples. | [FFaceNeRF](https://github.com/kwanyun/FFaceNeRF) |
| **StyleMM: Stylized 3D Morphable Face Model via Text-Driven Aligned Image Translation** | Pacific Graphics 2025 (Journal Track) / [Computer Graphics Forum (CGF)](https://doi.org/10.1111/cgf.70234) | Generate aligned stylized face images. The linked repository provides the EAS module of StyleMM. | [EAS](https://github.com/kwanyun/EAS) |
| **Deep-Learning-Based Facial Retargeting Using Local Patches** | Eurographics 2025 / [Computer Graphics Forum (CGF), 2025](https://doi.org/10.1111/cgf.15263) | Transfer facial performance from video to stylized 3D characters through local patch processing. | [DFL](https://github.com/LiyCg/DFL) |
| **StyleID: A Perception-Aware Dataset and Metric for Stylization-Agnostic Facial Identity Recognition** | SIGGRAPH 2026 (Journal Track) / [ACM Transactions on Graphics (TOG)](https://doi.org/10.1145/3811360) | Measure facial identity similarity across visual styles using stylization-robust embeddings. | [StyleID](https://github.com/kwanyun/StyleID) |
| **AnyTalk: Speech Animation for Arbitrary Characters Leveraging a Video Generation Model** | [IEEE Transactions on Visualization and Computer Graphics (TVCG), 2026](https://doi.org/10.1109/TVCG.2026.3725254) | Animate characters from speech. The linked repository provides character-specific fine-tuning and temporal inference. | [AnyTalk_CsF](https://github.com/kwanyun/AnyTalk_CsF) |
