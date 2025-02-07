<h1 align="center">:fire: FLAME Universe :fire:</h1>

This repository presents a list of publicly available ressources such as code, datasets, and scientific papers for the :fire: [FLAME](https://flame.is.tue.mpg.de/) :fire: 3D head model.
We aim at keeping the list up to date. You are invited to add missing FLAME-based ressources (publications, code repositories, datasets) either in the discussions or in a pull request.

<p>
  <p align="center"> 
  <img src="gifs/collection.png">
  </p>
</p>


<h2 align="center">:fire: FLAME :fire:</h2>

<details>
<summary>Never heard of FLAME?</summary>

<p align="center"> 
<img src="gifs/model_variations.gif">
</p>

FLAME is a lightweight and expressive generic head model learned from over 33,000 of accurately aligned 3D scans. 
FLAME combines a linear identity shape space (trained from head scans of 3800 subjects) with an articulated neck, jaw, and eyeballs, pose-dependent corrective blendshapes, and additional global expression blendshapes. 
For details please see the [scientific publication](https://ps.is.tuebingen.mpg.de/uploads_file/attachment/attachment/400/paper.pdf).
FLAME is publicly available under [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/).

</details>

<h2 align="center">Code</h2>

<details open>
<summary>List of public repositories that use FLAME (alphabetical order).</summary>

- [BFM_to_FLAME](https://github.com/TimoBolkart/BFM_to_FLAME): Conversion from Basel Face Model (BFM) to FLAME.
- [DECA](https://github.com/YadiraF/DECA):  Reconstruction of 3D faces with animatable facial expression detail from a single image.
- [diffusion-rig](https://github.com/adobe-research/diffusion-rig): Personalized model to edit facial expressions, head pose, and lighting in portrait images.
- [EMOCA](https://github.com/radekd91/emoca): Reconstruction of emotional 3D faces from a single image.
- [EMOTE](https://github.com/radekd91/inferno/tree/release/EMOTE/inferno_apps/TalkingHead): Emotional speech-driven 3D face animation.
- [expgan](https://github.com/kakaobrain/expgan): Face image generation with expression control.
- [FaceFormer](https://github.com/EvelynFan/FaceFormer): Speech-driven facial animation of meshes in FLAME mesh topology.
- [FLAME-Blender-Add-on](https://github.com/TimoBolkart/FLAME-Blender-Add-on): FLAME Blender Add-on.
- [flame-fitting](https://github.com/Rubikplayer/flame-fitting): Fitting of FLAME to scans. 
- [FLAME_PyTorch](https://github.com/soubhiksanyal/FLAME_PyTorch): FLAME PyTorch layer.
- [GANHead](https://github.com/wsj-sjtu/GANHead) Animatable neural head avatar.
- [GIF](https://github.com/ParthaEth/GIF): Generating face images with FLAME parameter control. 
- [INSTA](https://github.com/Zielon/INSTA): Volumetric head avatars from videos in less than 10 minutes. 
- [INSTA-pytorch](https://github.com/Zielon/INSTA-pytorch): Volumetric head avatars from videos in less than 10 minutes (PyTorch).
- [learning2listen](https://github.com/evonneng/learning2listen): Modeling interactional communication in dyadic conversations. 
- [MICA](https://github.com/Zielon/MICA): Reconstruction of metrically accurated 3D faces from a single image. 
- [metrical-tracker](https://github.com/Zielon/metrical-tracker): Metrical face tracker for monocular videos.
- [NED](https://github.com/foivospar/NED): Facial expression of emotion manipulation in videos.
- [Next3D](https://github.com/MrTornado24/Next3D): 3D generative model with FLAME parameter control.  
- [neural-head-avatars](https://github.com/philgras/neural-head-avatars): Building a neural head avatar from video sequences. 
- [photometric_optimization](https://github.com/HavenFeng/photometric_optimization): Fitting of FLAME to images using differentiable rendering. 
- [RingNet](https://github.com/soubhiksanyal/RingNet): Reconstruction of 3D faces from a single image. 
- [ROME](https://github.com/SamsungLabs/rome): Creation of personalized avatar from a single image.
- [SAFA](https://github.com/Qiulin-W/SAFA): Animation of face images.
- [Semantify](https://github.com/Omergral/Semantify): Semantic control over 3DMM parameters. 
- [SPECTRE](https://github.com/filby89/spectre): Speech-aware 3D face reconstruction from images.
- [TRUST](https://github.com/HavenFeng/TRUST): Racially unbiased skin tone extimation from images.
- [TF_FLAME](https://github.com/TimoBolkart/TF_FLAME): Fit FLAME to 2D/3D landmarks, FLAME meshes, or sample textured meshes. 
- [video-head-tracker](https://github.com/philgras/video-head-tracker): Track 3D heads in video sequences. 
- [VOCA](https://github.com/TimoBolkart/voca): Speech-driven facial animation of meshes in FLAME mesh topology.

</details>



<h2 align="center">Datasets</h2>

<details open>
<summary>List of datasets with meshes in FLAME topology. </summary>

- [BP4D+](https://github.com/Zielon/MICA/tree/master/datasets): 127 subjects, one neutral expression mesh each. 
- [CoMA dataset](https://coma.is.tue.mpg.de/download.php): 12 subjects, 12 extreme dynamic expressions each.
- [D3DFACS](https://flame.is.tue.mpg.de/download.php): 10 subjects, 519 dynamic expressions in total.
- [FaceWarehouse](http://kunzhou.net/zjugaps/facewarehouse/): 150 subjects, one neutral expression mesh each. 
- [FaMoS](https://tempeh.is.tue.mpg.de/): 95 subjects, 28 dynamic expressions and head poses each, about 600K frames in total.
- [Florence 2D/3D](https://github.com/Zielon/MICA/tree/master/datasets): 53 subjects, one neutral expression mesh each. 
- [FRGC](https://github.com/Zielon/MICA/tree/master/datasets): 531 subjects, one neutral expression mesh each. 
- [LYHM](https://www-users.cs.york.ac.uk/~nep/research/Headspace/): 1216 subjects, one neutral expression mesh each. 
- [Stirling](https://github.com/Zielon/MICA/tree/master/datasets): 133 subjects, one neutral expression mesh each. 
- [VOCASET](https://github.com/TimoBolkart/voca): 12 subjects, 40 speech sequences each with synchronized audio.


</details>



<h2 align="center">Publications</h2>

<details open>
<summary>List of FLAME-based scientific publications.</summary>

#### 2024

- [Towards Realistic Generative 3D Face Models (WACV 2024)](https://arxiv.org/pdf/2304.12483.pdf).

#### 2023

- [HeadCraft: Modeling High-Detail Shape Variations for Animated 3DMMs](https://arxiv.org/pdf/2312.14140.pdf).
- [GaussianAvatars: Photorealistic Head Avatars with Rigged 3D Gaussians](https://arxiv.org/pdf/2312.02069.pdf).
- [GAUSSIAN3DIFF: 3D Gaussian Diffusion for 3D Full Head Synthesis and Editing](https://arxiv.org/pdf/2312.03763.pdf).
- [3DiFACE: Diffusion-based Speech-driven 3D Facial Animation and Editing](https://arxiv.org/pdf/2312.00870.pdf).
- [LaughTalk: Expressive 3D Talking Head Generation with Laughter](https://arxiv.org/pdf/2311.00994.pdf).
- [A Perceptual Shape Loss for Monocular 3D Face Reconstruction (Pacific Graphics 2023)](https://studios.disneyresearch.com/app/uploads/2023/09/A-Perceptual-Shape-Loss-for-Monocular-3D-Face-Reconstruction-Paper.pdf).
- [DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models](https://browse.arxiv.org/pdf/2310.00434.pdf).
- [FLARE: Fast Learning of Animatable and Relightable Mesh Avatars (SIGGRAPH Asia 2023)](https://drive.google.com/file/d/1iiON_x9d2E4erP2n-2A4JQ-piHr5kdQ3/view?pli=1).
- [Emotional Speech-Driven Animation with Content-Emotion Disentanglement (SIGGRAPH Asia 2023)](https://arxiv.org/pdf/2306.08990.pdf).
- [Decaf: Monocular Deformation Capture for Face and Hand Interactions (SIGGRAPH Asia 2023)](https://vcai.mpi-inf.mpg.de/projects/Decaf/static/paper.pdf).
- [Accurate 3D Face Reconstruction with Facial Component Tokens (ICCV 2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_Accurate_3D_Face_Reconstruction_with_Facial_Component_Tokens_ICCV_2023_paper.pdf)
- [Speech4Mesh: Speech-Assisted Monocular 3D Facial Reconstruction for Speech-Driven 3D Facial Animation (ICCV 2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/He_Speech4Mesh_Speech-Assisted_Monocular_3D_Facial_Reconstruction_for_Speech-Driven_3D_Facial_ICCV_2023_paper.pdf).
- [Semantify: Simplifying the Control of 3D Morphable Models using CLIP (ICCV 2023)](https://arxiv.org/pdf/2308.07415.pdf).
- [Imitator: Personalized Speech-driven 3D Facial Animation (ICCV 2023)](https://arxiv.org/pdf/2301.00023.pdf).
- [Articulated 3D Head Avatar Generation using Text-to-Image Diffusion Models](https://arxiv.org/pdf/2307.04859.pdf).
- [Fake It Without Making It: Conditioned Face Generation for Accurate 3D Face](https://arxiv.org/pdf/2307.13639.pdf).
- [SelfTalk: A Self-Supervised Commutative Training Diagram to Comprehend 3D Talking Faces](https://arxiv.org/pdf/2306.10799.pdf).
- [NeRFlame: FLAME-based conditioning of NeRF for 3D face rendering](https://arxiv.org/pdf/2303.06226.pdf).
- [Text2Face: A Multi-Modal 3D Face Model](https://arxiv.org/pdf/2303.02688.pdf).
- [Expressive Speech-driven Facial Animation with controllable emotions](https://arxiv.org/pdf/2301.02008.pdf).
- [ClipFace: Text-guided Editing of Textured 3D Morphable Models (SIGGRAPH 2023)](https://arxiv.org/pdf/2212.01406.pdf).
- [GANHead: Towards Generative Animatable Neural Head Avatars (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_GANHead_Towards_Generative_Animatable_Neural_Head_Avatars_CVPR_2023_paper.pdf).
- [Implicit Neural Head Synthesis via Controllable Local Deformation Fields (CVPR 2023)](https://arxiv.org/pdf/2304.11113.pdf).
- [DiffusionRig: Learning Personalized Priors for Facial Appearance Editing (CVPR 2023)](https://arxiv.org/pdf/2304.06711.pdf).
- [High-Res Facial Appearance Capture from Polarized Smartphone Images (CVPR 2023)](https://arxiv.org/pdf/2212.01160.pdf).
- [Instant Volumetric Head Avatars (CVPR 2023)](https://arxiv.org/pdf/2211.12499.pdf).
- [Learning Personalized High Quality Volumetric Head Avatars (CVPR 2023)](https://arxiv.org/pdf/2304.01436.pdf).
- [Next3D: Generative Neural Texture Rasterization for 3D-Aware Head Avatars (CVPR 2023)](https://arxiv.org/pdf/2211.11208.pdf).
- [PointAvatar: Deformable Point-based Head Avatars from Videos (CVPR 2023)](https://arxiv.org/pdf/2212.08377.pdf).
- [Visual Speech-Aware Perceptual 3D Facial Expression Reconstruction from Videos (CVPR-W 2023)](https://arxiv.org/pdf/2207.11094.pdf).
- [Scaling Neural Face Synthesis to High FPS and Low Latency by Neural Caching (WACV 2023)](https://arxiv.org/pdf/2211.05773.pdf).
  
#### 2022

- [TeleViewDemo: Experience the Future of 3D Teleconferencing (SIGGRAPH Asia 2022)](https://dl.acm.org/doi/fullHtml/10.1145/3550472.3558404).
- [Realistic One-shot Mesh-based Head Avatars (ECCV 2022)](https://arxiv.org/pdf/2206.08343.pdf).
- [Towards Metrical Reconstruction of Human Faces (ECCV 2022)](https://arxiv.org/pdf/2204.06607.pdf).
- [Towards Racially Unbiased Skin Tone Estimation via Scene Disambiguation (ECCV 2022)](https://arxiv.org/pdf/2205.03962.pdf).
- [Generative Neural Articulated Radiance Fields (NeurIPS 2022)](https://arxiv.org/pdf/2206.14314.pdf).
- [EMOCA: Emotion Driven Monocular Face Capture and Animation (CVPR 2022)](https://arxiv.org/pdf/2204.11312.pdf).
- [Generating Diverse 3D Reconstructions from a Single Occluded Face Image (CVPR 2022)](https://arxiv.org/pdf/2112.00879.pdf).
- [I M Avatar: Implicit Morphable Head Avatars from Videos (CVPR 2022)](https://arxiv.org/pdf/2112.07471.pdf).
- [Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion (CVPR 2022)](https://arxiv.org/pdf/2204.08451.pdf).
- [Neural Emotion Director: Speech-preserving semantic control of facial expressions in “in-the-wild” videos (CVPR 2022)](https://arxiv.org/pdf/2112.00585.pdf).
- [Neural head avatars from monocular RGB videos (CVPR 2022)](https://arxiv.org/pdf/2112.01554.pdf).
- [RigNeRF: Fully Controllable Neural 3D Portraits (CVPR 2022)](https://arxiv.org/pdf/2206.06481.pdf).
- [Simulated Adversarial Testing of Face Recognition Models (CVPR 2022)](https://arxiv.org/pdf/2106.04569.pdf).
- [Accurate 3D Hand Pose Estimation for Whole-Body 3D Human Mesh Estimation (CVPR-W 2022)](https://arxiv.org/pdf/2011.11534.pdf).
- [MOST-GAN: 3D Morphable StyleGAN for Disentangled Face Image Manipulation (AAAI 2022)](https://arxiv.org/pdf/2111.01048.pdf).
- [Exp-GAN: 3D-Aware Facial Image Generation with Expression Control (ACCV 2022)](https://openaccess.thecvf.com/content/ACCV2022/papers/Lee_Exp-GAN_3D-Aware_Facial_Image_Generation_with_Expression_Control_ACCV_2022_paper.pdf).

#### 2021

- [Data-Driven 3D Neck Modeling and Animation (TVCG 2021)](http://xufeng.site/publications/2020/Data-Driven%203D%20Neck%20Modeling%20and%20Animation.pdf).
- [MorphGAN: One-Shot Face Synthesis GAN for Detecting Recognition Bias (BMVC 2021)](https://arxiv.org/pdf/2012.05225.pdf).
- [SIDER : Single-Image Neural Optimization for Facial Geometric Detail Recovery (3DV 2021)](https://arxiv.org/pdf/2108.05465.pdf).
- [SAFA: Structure Aware Face Animation (3DV 2021)](https://arxiv.org/pdf/2111.04928.pdf).
- [Learning an Animatable Detailed 3D Face Model from In-The-Wild Images (SIGGRAPH 2021)](https://arxiv.org/pdf/2012.04012.pdf).

#### 2020

- [Monocular Expressive Body Regression through Body-Driven Attention (ECCV 2020)](https://arxiv.org/pdf/2008.09062.pdf).
- [GIF: Generative Interpretable Faces (3DV 2020)](https://arxiv.org/pdf/2009.00149.pdf).

#### 2019

- [Learning to Regress 3D Face Shape and Expression from an Image without 3D Supervision (CVPR 2019)](https://arxiv.org/pdf/1905.06817.pdf).

</details>



