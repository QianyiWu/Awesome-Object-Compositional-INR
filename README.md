# Awesome Object Compositional Implicit Neural Representation (INR) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)

This repo contains a curative list of *object-compositional* modeling by implicit neural representation.

## Motivation of this collection

Our inspiration was sparked by the rapidly growing trend of implicit neural representations (INR), such as NeRF, which have displayed remarkable capabilities in scene representation. Given that our environment comprises diverse objects, it raises an intriguing question: How can we comprehensively represent the basic constituents of a scene, the objects, while also promoting compositional capacity? Thus, our project involves gathering research papers that provide possible solutions to this problem, and we've labeled this collection as 'Object-Compositional Implicit Neural Representation'.

#### 🔆 This project is still ongoing, pull requests are welcomed!!

If you have any suggestions (missing papers, new papers or typos), please feel free to edit and pull a request. Just letting me know the title of papers can also be a big contribution to me. You can do this by opening issues.

#### ⭐️ If you find this repo useful, welcome to star it.

## Papers

### Learning from a single scene

- Learning Object-Compositional Neural Radiance Field for Editable Scene Rendering. **(ICCV 2021)** [Paper](https://arxiv.org/pdf/2109.01847.pdf) | [Project Page](https://zju3dv.github.io/object_nerf/) | [Code](https://github.com/zju3dv/object_nerf)
- In-Place Scene Labelling and Understanding with Implicit Scene Representation. **(ICCV 2021)** [Paper](https://arxiv.org/abs/2103.15875) | [Project Page](https://shuaifengzhi.com/Semantic-NeRF/) | [Code](https://github.com/Harry-Zhi/semantic_nerf)
- Object-compositional Neural Implicit Surfaces. **(ECCV 2022)** [Paper](https://arxiv.org/abs/2207.09686) | [Project Page](https://wuqianyi.top/objectsdf/) | [Code](https://github.com/QianyiWu/objsdf)
- Neural Feature Fusion Fields (N3F): 3D Distillation of Self-Supervised 2D Image Representations **(3DV 2022)** [Paper](https://arxiv.org/abs/2209.03494) | [Project Page](https://www.robots.ox.ac.uk/~vadim/n3f/) | [Code](https://github.com/dichotomies/N3F)
- Decomposing nerf for editing via feature field distillation. **(NeurIPS 2022)** [Paper](https://arxiv.org/abs/2205.15585) | [Project Page](https://pfnet-research.github.io/distilled-feature-fields/) | [Code](https://github.com/pfnet-research/distilled-feature-fields)
- Object Scene Representation Transformer. **(NeurIPS 2022)** [Paper](https://arxiv.org/abs/2206.06922) | [Project Page](https://osrt-paper.github.io/) | [Code](https://github.com/stelzner/osrt)
- Unsupervised Discovery of Object Radiance Fields. **(ICLR 2022)** [Paper](https://arxiv.org/abs/2107.07905.pdf) | [Project Page](https://kovenyu.com/uorf/) | [Code](https://github.com/KovenYu/uORF)
- Feature-realistic neural fusion for real-time, open set scene understanding. **(ICRA 2023)** [Paper](https://arxiv.org/abs/2210.03043) | [Project Page](https://makezur.github.io/FeatureRealisticFusion/)
- Dm-nerf: 3d scene geometry decomposition and manipulation from 2d images. **(ICLR 2023)** [Paper](https://arxiv.org/abs/2208.07227) | [Code](https://github.com/vLAR-group/DM-NeRF)
- NeRF-SOS: Any-View Self-supervised Object Segmentation on Complex Scenes. **(ICLR 2023)** [Paper](https://arxiv.org/abs/2209.08776) | [Project Page](https://zhiwenfan.github.io/NeRF-SOS/) | [Code](https://github.com/VITA-Group/NeRF-SOS)
- vMAP: Vectorised Object Mapping for Neural Field SLAM. **(CVPR 2023)** [Paper](https://arxiv.org/abs/2302.01838) | [Project Page](https://kxhit.github.io/vMAP) | [Code](https://github.com/kxhit/vMAP)
- Nerflets: Local Radiance Fields for Efficient Structure-Aware 3D Scene Representation from 2D Supervision. **(CVPR 2023)** [Paper](https://arxiv.org/abs/2303.03361) | [Project Page](https://jetd1.github.io/nerflets-web/?utm_source=tldrai)
- Panoptic lifting for 3d scene understanding with neural fields. **(CVPR 2023)** [Paper](https://arxiv.org/abs/2212.09802) | [Project Page](https://nihalsid.github.io/panoptic-lifting/) | [Code](https://github.com/nihalsid/panoptic-lifting)
- Panoptic Compositional Feature Field for Editable Scene Rendering With Network-Inferred Labels via Metric Learning. **(CVPR 2023)** [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Cheng_Panoptic_Compositional_Feature_Field_for_Editable_Scene_Rendering_With_Network-Inferred_CVPR_2023_paper.pdf)
- Automated 3D Object Discovery and Reconstruction. **(CVPR 2023)** [Paper](https://arxiv.org/abs/2305.08810) | [Project Page](https://zju3dv.github.io/autorecon/) | [Code](https://github.com/zju3dv/AutoRecon)
- Rico: Regularizing the unobservable for indoor compositional reconstruction. **(ICCV 2023)** [Paper](https://arxiv.org/abs/2303.08605)
- AssetField: Assets Mining and Reconfiguration in Ground Feature Plane Representation. **(ICCV 2023)** [Paper](https://city-super.github.io/assetfield/img/main.pdf) | [Project Page](https://city-super.github.io/assetfield/)

### Learning from dynamic scene

- Neural scene graphs for dynamic scenes. **(CVPR 2021)** [Paper](https://arxiv.org/abs/2011.10379) | [Project Page](http://light.princeton.edu/neural-scene-graphs) | [Code](https://github.com/princeton-computational-imaging/neural-scene-graphs)
- NeuralDiff: Segmenting 3D objects that move in egocentric videos. **(3DV 2021)** [Paper](https://www.robots.ox.ac.uk/~vgg/publications/2021/Tschernezki21/tschernezki21.pdf) | [Project Page](https://www.robots.ox.ac.uk/~vadim/neuraldiff/) | [Code](https://github.com/dichotomies/NeuralDiff)
- Panoptic Neural Fields: A Semantic Object-Aware Neural Scene Representation. **(CVPR 2022)** [Paper](https://arxiv.org/abs/2205.04334) | [Project Page](https://abhijitkundu.info/projects/pnf/)
- D2nerf: self-supervised decoupling of dynamic and static objects from a monocular video. **(NeurIPS 2022)** [Paper](https://arxiv.org/abs/2205.15838) | [Project Page](https://d2nerf.github.io/) | [Code](https://github.com/ChikaYan/d2nerf)
- SAVi++: Towards End-to-End Object-Centric Learning from Real-World Videos. **(NeurIPS 2022)** [Paper](https://arxiv.org/abs/2206.07764) | [Project Page](https://slot-attention-video.github.io/savi++/) | [Code](https://github.com/google-research/slot-attention-video/)
- Conditional Object-Centric Learning from Video. **(NeurIPS 2022)** [Paper](https://arxiv.org/abs/2111.12594) | [Project Page](https://slot-attention-video.github.io/) | [Code](https://github.com/google-research/slot-attention-video/)
- NeRFPlayer: A Streamable Dynamic Scene Representation with Decomposed Neural Radiance Fields. **(TVCG 2023)**[Paper](https://arxiv.org/abs/2210.15947) | [Project Page](https://lsongx.github.io/projects/nerfplayer.html) | [Code](https://github.com/nerfstudio-project/nerfstudio)

### Generation

- GIRAFFE: Representing Scenes as Compositional Generative Neural Feature Fields. **(CVPR 2021)** [Paper](https://www.cvlibs.net/publications/Niemeyer2021CVPR.pdf) | [Project Page](https://m-niemeyer.github.io/project-pages/giraffe/index.html) | [Code](https://github.com/autonomousvision/giraffe)
- Unconstrained scene generation with locally conditioned radiance fields. **(ICCV 2021)** [Paper](https://arxiv.org/abs/2104.00670) | [Project Page](https://apple.github.io/ml-gsn/) | [Code](https://github.com/apple/ml-gsn)
- Object-centric neural scene rendering. [Paper](https://arxiv.org/abs/2012.08503) | [Project Page](https://shellguo.com/osf/)
- Unsupervised Discovery of Object Radiance Fields. **(ICLR 2022)** [Paper](https://arxiv.org/abs/2107.07905) | [Project Page](https://kovenyu.com/uorf/) | [Code](https://github.com/KovenYu/uORF)
- Unsupervised Discovery and Composition of Object Light Fields. **(TMLR 2023)** [Paper](https://arxiv.org/abs/2205.03923) | [Project Page](https://cameronosmith.github.io/colf/) | [Code](https://github.com/cameronosmith/COLF)
- DisCoScene: Spatially Disentangled Generative Radiance Fields for Controllable 3D-aware Scene Synthesis. **(CVPR 2023)** [Paper](https://arxiv.org/abs/2212.11984) | [Project Page](https://snap-research.github.io/discoscene/) | [Code](https://github.com/snap-research/discoscene)
- UrbanGIRAFFE: Representing Urban Scenes as Compositional Generative Neural Feature Fields [Paper](https://arxiv.org/abs/2303.14167) | [Project Page](https://lv3d.github.io/urbanGIRAFFE/)
- CompoNeRF: Text-guided Multi-object Compositional NeRF with Editable 3D Scene Layout [Paper](https://arxiv.org/abs/2303.13843)
- Set-the-Scene: Global-Local Training for Generating Controllable NeRF Scenes [Paper](https://arxiv.org/abs/2303.13450)| [Project Page](https://danacohen95.github.io/Set-the-Scene/) | [Code](https://github.com/DanaCohen95/Set-the-Scene)
- Compositional 3D Scene Generation using Locally Conditioned Diffusion [Paper](https://arxiv.org/abs/2303.12218) | [Project Page](https://ryanpo.com/comp3d/)
- CC3D: Layout-Conditioned Generation of Compositional 3D Scenes **(ICCV 2023)** [Paper](https://arxiv.org/abs/2303.12074) | [Project Page](https://sherwinbahmani.github.io/cc3d/) | [Code](https://github.com/sherwinbahmani/cc3d)
- NCHO : Unsupervised Learning for Neural 3D Composition of Humans and Objects **(ICCV 2023)** [Paper](https://arxiv.org/abs/2305.14345) | [Project Page](https://taeksuu.github.io/ncho/)

## Related Repository.

To capture or understand the surrounding world from an object-compositional perspective, there are some other awesome collections that could help you dive into this area.

- [Awesome-object-SLAM](https://github.com/520xyxyzq/awesome-object-SLAM)
- [Awesome-Implicit-NeRF-Robics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)
