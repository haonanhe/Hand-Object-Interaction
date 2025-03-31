# Hand-Object-Interaction
Collections of  papers and codes of hand-object interaction (HOI). 

* [HOI Dataset](#hoi-dataset)
* [Dexterous Dataset](#dexterous-dataset)
* [Hand Motion Reconstruction](#hand-motion-reconstruction)
* [Hand Motion Prior](#hand-motion-prior)
* [Hand Motion Refinement](#hand-motion-refinement)
* [Reconstruct Hand Object from RGB Images Videos](#reconstruct-hand-object-from-rgb-images-videos)
* [Reconstruct Hand Object from RGB-D Images Videos](#reconstruct-hand-object-from-rgb-d-images-videos)
* [Hand Object Motion Synthesis](#hand-object-motion-synthesis)
* [Generate HOI Images Videos](#generate-hoi-images-videos)
* [HOI Augmentation](#hoi-augmentation)
* [HOI Reenactment](#hoi-reenactment)
* [HOI Prediction](#hoi-prediction)
* [Human to Robotics](#human-to-robotics)


## HOI Dataset
1. Freihand: A dataset for markerless capture of hand pose and shape from single rgb images. [ICCV 2019] [[Paper]](https://arxiv.org/pdf/1909.04349) [[Code]](https://github.com/lmb-freiburg/freihand) [[Project Page]](https://lmb.informatik.uni-freiburg.de/projects/freihand/)
2. Learning Joint Reconstruction of Hands and Manipulated Objects. [CVPR 2019] [[Paper]](https://arxiv.org/pdf/1904.05767) [[Code]](https://github.com/hassony2/obman_train) [[Project Page]](https://hassony2.github.io/obman)
3. HOnnotate: A method for 3D Annotation of Hand and Object Poses. [CVPR 2020] [[Paper]](https://arxiv.org/pdf/1907.01481) [[Code]](https://github.com/shreyashampali/HOnnotate?tab=readme-ov-file) [[Project Page]](https://www.tugraz.at/institute/icg/research/team-lepetit/research-projects/hand-object-3d-pose-annotation/)
4. GanHand: Predicting Human Grasp Affordances in Multi-Object Scenes. [CVPR 2020 Oral] [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Corona_GanHand_Predicting_Human_Grasp_Affordances_in_Multi-Object_Scenes_CVPR_2020_paper.pdf) [[Code]](https://github.com/enriccorona/GanHand) [[Project Page]](http://www.iri.upc.edu/people/ecorona/ganhand/)
5. ContactPose: A Dataset of Grasps with Object Contact and Hand Pose. [ECCV 2020] [[Paper]](https://arxiv.org/pdf/2007.09545) [[Code]](https://github.com/facebookresearch/ContactPose) [[Project Page]](https://contactpose.cc.gatech.edu/)
6. GRAB: A Dataset of Whole-Body Human Grasping of Objects. [ECCV 2020] [[Paper]](https://arxiv.org/pdf/2008.11200) [[Code]](https://github.com/otaheri/GRAB) [[Project Page]](https://grab.is.tue.mpg.de/)
7. DexYCB: A Benchmark for Capturing Hand Grasping of Objects. [CVPR 2021] [[Paper]](https://arxiv.org/pdf/2104.04631) [[Code]](https://github.com/NVlabs/dex-ycb-toolkit) [[Project Page]](https://dex-ycb.github.io/)
8. HOI4D: A 4D Egocentric Dataset for Category-Level Human-Object Interaction. [CVPR 2022] [[Paper]](https://hoi4d.github.io/HOI4D_cvpr2022.pdf) [[Code]](https://github.com/leolyliu/HOI4D-Instructions) [[Project Page]](https://hoi4d.github.io/)
9. OakInk: A Large-scale Knowledge Repository for Understanding Hand-Object Interaction. [CVPR 2022] [[Paper]](https://arxiv.org/abs/2203.15709) [[Code]](https://github.com/oakink/OakInk) [[Project Page]](httpshttps://oakink.net///hoi4d.github.io/)
10. ARCTIC: A dataset for dexterous bimanual hand object manipulation. [ECCV 2024] [[Paper]](https://download.is.tue.mpg.de/arctic/arctic_april_24.pdf) [[Code]](https://github.com/zc-alexfan/arctic) [[Project Page]](https://arctic.is.tue.mpg.de/)
11. InterCap: Joint Markerless 3D Tracking of Humans and Objects in Interaction. [IJCV 2024] [[Project Page]](https://intercap.is.tue.mpg.de/)
12. ContactArt: Learning 3D Interaction Priors for Category-level Articulated Object and Hand Poses Estimation. [3DV 2024 Oral] [[Paper]](https://arxiv.org/pdf/2305.01618) [[Project Page]](https://zehaozhu.github.io/ContactArt/)
13. GraspXL: Generating Grasping Motions for Diverse Objects at Scale. [ECCV 2024] [[Paper]](https://arxiv.org/pdf/2403.19649) [[Code]](https://github.com/zdchan/GraspXL) [[Project Page]](https://eth-ait.github.io/graspxl/)
14. SemGrasp: Semantic Grasp Generation via Language Aligned Discretization. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2404.03590) [[Project Page]](https://kailinli.github.io/SemGrasp/)
15. TACO: Benchmarking Generalizable Bimanual Tool-ACtion-Object Understanding. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2401.08399) [[Code]](https://github.com/leolyliu/TACO-Instructions) [[Project Page]](https://taco2024.github.io/)
16. Introducing hot3d: An egocentric dataset for 3d hand and object tracking. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2411.19167) [[Code]](https://github.com/facebookresearch/hot3d) [[Project Page]](https://facebookresearch.github.io/hot3d/)
17. GigaHands: A Massive Annotated Dataset of Bimanual Hand Activities. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2412.04244)

## Dexterous Dataset
1. DexGraspNet: A Large-Scale Robotic Dexterous Grasp Dataset for General Objects Based on Simulation. [ICRA 2023] [[Paper]](https://arxiv.org/pdf/2210.02697) [[Code]](https://github.com/PKU-EPIC/DexGraspNet) [[Project Page]](https://pku-epic.github.io/DexGraspNet/)
2. RealDex: Towards Human-like Grasping for Robotic Dexterous Hand. [IJCAI 2024] [[Paper]](https://arxiv.org/pdf/2402.13853) [[Code]](https://github.com/4DVLab/RealDex) [[Project Page]](https://4dvlab.github.io/RealDex_page/)

## Hand Motion Reconstruction
1. End-to-End Human Pose and Mesh Reconstruction with Transformers. [CVPR 2021] [[Paper]](https://arxiv.org/pdf/2012.09760) [[Code]](https://github.com/microsoft/MeshTransformer?tab=readme-ov-file)
2. HaMeR: Hand Mesh Recovery. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2312.05251) [[Code]](https://github.com/geopavlakos/hamer) [[Project Page]](https://geopavlakos.github.io/hamer/)
3. WiLoR: End-to-end 3D hand localization and reconstruction in-the-wild. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2409.12259) [[Code]](https://github.com/rolpotamias/WiLoR) [[Project Page]](https://rolpotamias.github.io/WiLoR/)
4. Dyn-HaMR: Recovering 4D Interacting Hand Motion from a Dynamic Camera. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2412.12861) [[Code]](https://github.com/ZhengdiYu/Dyn-HaMR) [[Project Page]](https://dyn-hamr.github.io/)
5. HaWoR: World-Space Hand Motion Reconstruction from Egocentric Videos. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2501.02973) [[Code]](https://github.com/ThunderVVV/HaWoR) [[Project Page]](https://hawor-project.github.io/)

## Hand Motion Prior
1. HMP: Hand Motion Priors for Pose and Shape Estimation from Video. [WACV 2024] [[Paper]](https://openaccess.thecvf.com/content/WACV2024/papers/Duran_HMP_Hand_Motion_Priors_for_Pose_and_Shape_Estimation_From_WACV_2024_paper.pdf) [[Code]](https://github.com/enesduran/HMP) [[Project Page]](https://hmp.is.tue.mpg.de/)

## Hand Motion Refinement
1. TOCH: Spatio-Temporal Object-to-Hand Correspondence for Motion Refinement. [ECCV 2022] [[Paper]](https://virtualhumans.mpi-inf.mpg.de/papers/zhou22toch/toch.pdf) [[Code]](https://github.com/kzhou23/toch) [[Project Page]](https://virtualhumans.mpi-inf.mpg.de/toch/)
2. GeneOH Diffusion: Towards Generalizable Hand-Object Interaction Denoising via Denoising Diffusion. [ICLR 2024] [[Paper]](https://arxiv.org/pdf/2402.14810) [[Code]](https://github.com/Meowuu7/GeneOH-Diffusion) [[Project Page]](https://meowuu7.github.io/GeneOH-Diffusion/)
3. Physics-aware Hand-object Interaction Denoising. [CVPR 2024] [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Luo_Physics-Aware_Hand-Object_Interaction_Denoising_CVPR_2024_paper.pdf)

## Reconstruct Hand Object from RGB Images Videos
1. What's in your hands? 3D Reconstruction of Generic Objects in Hands. [CVPR 2022] [[Paper]](https://arxiv.org/pdf/2204.07153) [[Code]](https://github.com/JudyYe/ihoi) [[Project Page]](https://judyye.github.io/ihoi/)
2. AlignSDF: Pose-Aligned Signed Distance Fields for Hand-Object Reconstruction. [ECCV 2022] [[Paper]](https://arxiv.org/pdf/2207.12909) [[Code]](https://github.com/zerchen/AlignSDF) [[Project Page]](https://zerchen.github.io/projects/alignsdf.html)
3. Reconstructing Hand-Held Objects from Monocular Video. [Siggraph Asia 2022 Conference Track] [[Paper]](https://arxiv.org/pdf/2211.16835) [[Code]](https://github.com/dihuangdh/HHOR) [[Project Page]](https://dihuangdh.github.io/hhor/)
4. Diffusion-Guided Reconstruction of Everyday Hand-Object Interaction Clips. [ICCV 2023 Oral] [[Paper]](https://arxiv.org/pdf/2309.05663) [[Code]](https://github.com/JudyYe/diffhoi_v2) [[Project Page]](https://judyye.github.io/diffhoi-www/)
5. gSDF: Geometry-Driven Signed Distance Functions for 3D Hand-Object Reconstruction. [CVPR 2023] [[Paper]](https://arxiv.org/pdf/2304.11970) [[Code]](https://github.com/zerchen/gSDF) [[Project Page]](https://zerchen.github.io/projects/gsdf.html)
6. HOLD: Category-agnostic 3D Reconstruction of Interacting Hands and Objects from Video. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2311.18448) [[Code]](https://github.com/zc-alexfan/hold) [[Project Page]](https://zc-alexfan.github.io/hold)
7. MOHO: Learning Single-view Hand-held Object Reconstruction with Multi-view Occlusion-Aware Supervision. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2310.11696) [[Code]](https://github.com/ZhangCYG/MOHO)
8. NCRF: Neural Contact Radiance Fields for Free-Viewpoint Rendering of Hand-Object Interaction. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2402.05532)
9. EasyHOI: Unleashing the Power of Large Models for Reconstructing Hand-Object Interactions in the Wild. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2411.14280) [[Code]](https://github.com/lym29/EasyHOI) [[Project Page]](https://lym29.github.io/EasyHOI-page/)

## Reconstruct Hand Object from RGB-D Images Videos
1. Single Depth View Based Real-Time Reconstruction of Hand-Object Interactions. [ACM Transactions on Graphics (TOG) 2021] [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3451341) 
2. Physical Interaction: Reconstructing Hand-object Interactions with Physics. [SIGGRAPH Asia 2022 Conference] [[Paper]](https://arxiv.org/pdf/2209.10833) [[Code]](https://github.com/hu-hy17/PhysInteraction)
3. BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects. [CVPR 2023] [[Paper]](https://arxiv.org/pdf/2303.14158) [[Code]](https://github.com/NVlabs/BundleSDF) [[Project Page]](https://bundlesdf.github.io/)

## Hand Object Motion Synthesis
1. Hand-Object Contact Consistency Reasoning for Human Grasps Generation. [ICCV 2021] [[Paper]](https://arxiv.org/pdf/2104.03304) [[Code]](https://github.com/hwjiang1510/GraspTTA) [[Project Page]](https://hwjiang1510.github.io/GraspTTA/)
2. D-Grasp: Physically Plausible Dynamic Grasp Synthesis for Hand-Object Interactions. [CVPR 2022] [[Paper]](https://arxiv.org/pdf/2112.03028) [[Code]](https://github.com/christsa/dgrasp) [[Project Page]](https://eth-ait.github.io/d-grasp/)
3. CAMS: CAnonicalized Manipulation Spaces for Category-Level Functional Hand-Object Manipulation Synthesis. [CVPR 2023] [[Paper]](https://arxiv.org/pdf/2303.15469) [[Code]](https://github.com/cams-hoi/CAMS) [[Project Page]](https://cams-hoi.github.io/)
4. SynH2R: Synthesizing Hand-Object Motions for Learning Human-to-Robot Handovers. [arxiv 2023] [[Paper]](https://arxiv.org/pdf/2311.05599)
5. Physically Plausible Full-Body Hand-Object Interaction Synthesis. [arxiv 2023] [[Paper]](https://arxiv.org/pdf/2309.07907)
6. IMoS: Intent-Driven Full-Body Motion Synthesis for Human-Object Interactions. [EUROGRAPHICS 2023] [[Paper]](https://arxiv.org/pdf/2212.07555) [[Code]](https://github.com/anindita127/IMoS) [[Project Page]](https://vcai.mpi-inf.mpg.de/projects/IMoS/)
7. MACS: Mass Conditioned 3D Hand and Object Motion Synthesis. [3DV 2024] [[Paper]](https://arxiv.org/pdf/2312.14929) [[Project Page] ](https://vcai.mpi-inf.mpg.de/projects/MACS/)
8. FürElise: Capturing and Physically Synthesizing Hand Motions of Piano Performance. [SIGGRAPH Asia 2024] [[Paper]](https://arxiv.org/pdf/2410.05791) [[Project Page]](https://for-elise.github.io/)
9. DiffH2O: Diffusion-Based Synthesis of Hand-Object Interactions from Textual Descriptions. [SIGGRAPH Asia 2024] [[Paper]](https://arxiv.org/pdf/2403.17827) [[Project Page]](https://diffh2o.github.io/)
10. Controllable Human-Object Interaction Synthesis. [ECCV 2024 Oral] [[Paper]](https://arxiv.org/pdf/2312.03913) [[Code] ](https://github.com/lijiaman/chois_release) [[Project Page]](https://lijiaman.github.io/projects/chois/)
11. UGG: Unified Generative Grasping. [ECCV 2024] [[Paper]](https://arxiv.org/pdf/2311.16917) [[Code]](https://github.com/Jiaxin-Lu/ugg) [[Project Page]](https://jiaxin-lu.github.io/ugg/)
12. GRIP: Generating Interaction Poses Using Spatial Cues and Latent Consistency. [3DV 2024] [[Paper]](https://arxiv.org/pdf/2308.11617) [[Code]](https://github.com/otaheri/GRIP) [[Project Page]](https://grip.is.tue.mpg.de/)
13. GEARS: Local Geometry-aware Hand-object Interaction Synthesis. [CVPR 2024] [[Paper]](https://virtualhumans.mpi-inf.mpg.de/papers/zhou24gears/gears.pdf) [[Code]](https://github.com/kzhou23/gears) [[Project Page]](https://virtualhumans.mpi-inf.mpg.de/gears/)
14. G-HOP: Generative Hand-Object Prior for Interaction Reconstruction and Grasp Synthesis. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2404.12383) [[Code]](https://github.com/JudyYe/ghop) [[Project Page]](https://judyye.github.io/ghop-www/)
15. ArtiGrasp: Physically Plausible Synthesis of Bi-Manual Dexterous Grasping and Articulation. [3DV 2024] [[Paper]](https://arxiv.org/pdf/2309.03891) [[Code]](https://github.com/zdchan/artigrasp) [[Project Page]](https://eth-ait.github.io/artigrasp/)
16. GraspXL: Generating Grasping Motions for Diverse Objects at Scale. [ECCV 2024] [[Paper]](https://arxiv.org/pdf/2403.19649) [[Code]](https://github.com/zdchan/GraspXL) [[Project Page]](https://eth-ait.github.io/graspxl/)
17. Omnigrasp: Grasping Diverse Objects with Simulated Humanoids. [NeurIPS 2024] [[Paper]](https://arxiv.org/pdf/2407.11385) [[Code]](https://github.com/ZhengyiLuo/Omnigrasp) [[Project Page]](https://www.zhengyiluo.com/Omnigrasp-Site/)
18. Text2HOI: Text-guided 3D Motion Generation for Hand-Object Interaction. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2404.00562v2) [[Code] ](https://github.com/JunukCha/Text2HOI) [[Project Page]](https://junukcha.github.io/project/text2hoi/)
19. Task-Oriented Human-Object Interactions Generation with Implicit Neural Representations. [WACV 2024] [[Paper]](https://arxiv.org/pdf/2303.13129)
20. Human-Object Interaction from Human-Level Instructions. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2406.17840)
21. SemGrasp: Semantic Grasp Generation via Language Aligned Discretization. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2404.03590) [[Project Page]](https://kailinli.github.io/SemGrasp/)
22. ManiDext: Hand-Object Manipulation Synthesis via Continuous Correspondence Embeddings and Residual-Guided Diffusion. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2409.09300) [[Project Page]](https://jiajunzhang16.github.io/manidext/)
   
## Generate HOI Images Videos
1. Affordance Diffusion: Synthesizing Hand-Object Interactions. [CVPR 2023] [[Paper]](https://arxiv.org/pdf/2303.12538) [[Code]](https://github.com/NVlabs/affordance_diffusion) [[Project Page]](https://judyye.github.io/affordiffusion-www/)
2. HOIDiffusion: Generating Realistic 3D Hand-Object Interaction Data. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2403.12011) [[Code]](https://github.com/Mq-Zhang1/HOIDiffusion) [[Project Page]](https://mq-zhang1.github.io/HOIDiffusion/)
3. ManiVideo: Generating Hand-Object Manipulation Video with Dexterous and Generalizable Grasping. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2412.16212)
4. TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2503.11423)

## HOI Augmentation
1. HOGSA: Bimanual Hand-Object Interaction Understanding with 3D Gaussian Splatting Based Data Augmentation. [arxiv 2025] [[Paper]](https://arxiv.org/pdf/2501.02845)

## HOI Reenactment
1. HOI-Swap: Swapping Objects in Videos with Hand-Object Interaction Awareness. [NeurIPS 2024] [[Paper]](https://arxiv.org/pdf/2406.07754) [[Code]](https://github.com/zihuixue/HOISwap) [[Project Page]](https://vision.cs.utexas.edu/projects/HOI-Swap/)
2. Re-HOLD: Video Hand Object Interaction Reenactment via adaptive Layout-instructed Diffusion Model. [CVPR 2025] [[Paper]](https://arxiv.org/pdf/2503.16942) [[Project Page]](https://fyycs.github.io/Re-HOLD/)

## HOI Prediction
1. HandsOnVLM: Vision-Language Models for Hand-Object Interaction Prediction. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2412.13187) [[Code]](https://github.com/Kami-code/HandsOnVLM-release) [[Project Page]](https://www.chenbao.tech/handsonvlm/)

## Human to Robotics
1. Human-to-Robot Imitation in the Wild. [RSS 2022] [[Paper]](https://arxiv.org/pdf/2207.09450) [[Project Page]](https://human2robot.github.io/)
2. MimicPlay: Long-Horizon Imitation Learning by Watching Human Play. [CoRL 2023] [[Paper]](https://arxiv.org/pdf/2302.12422) [[Code]](https://github.com/j96w/MimicPlay) [[Project Page]](https://mimic-play.github.io/)
3. Object-Centric Dexterous Manipulation from Human Motion Data. [CVPR 2024] [[Paper]](https://arxiv.org/pdf/2411.04005) [[Code]](https://github.com/cypypccpy/ObjDexEnvs) [[Project Page]](https://cypypccpy.github.io/obj-dex.github.io/)
4. OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation. [CoRL 2024] [[Paper]](https://arxiv.org/pdf/2410.11792) [[Project Page]](https://ut-austin-rpl.github.io/OKAMI/)
5. Bridging the Human to Robot Dexterity Gap through Object-Oriented Rewards. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2410.23289) [[Code]](https://github.com/irmakguzey/object-rewards/tree/main) [[Project Page]](https://object-rewards.github.io/)
6. VLM See, Robot Do: Human Demo Video to Robot Action Plan via Vision Language Model. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2410.08792) [[Code]](https://github.com/ai4ce/SeeDo) [[Project Page]](https://ai4ce.github.io/SeeDo/)
7. ORION: Vision-based Manipulation from Single Human Video with Open-World Object Graphs. [arxiv 2024] [[Paper]](https://arxiv.org/pdf/2405.20321) [[Project Page]](https://ut-austin-rpl.github.io/ORION-release/)
8. Hand-Object Interaction Pretraining from Videos. [ICRA 2025] [[Paper]](https://hgaurav2k.github.io/hop/web_assets/manuscript.pdf) [[Code]](https://github.com/hgaurav2k/hop) [[Project Page]](https://hgaurav2k.github.io/hop/)
9. Humanoid Policy ∼ Human Policy. [arxiv 2025] [[Paper]](https://arxiv.org/pdf/2503.13441) [[Code]](https://github.com/RogerQi/human-policy) [[Project Page]](https://human-as-robot.github.io/)
10. Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization. [arxiv 2025] [[Paper]](https://arxiv.org/pdf/2502.20382) [[Project Page]](https://lujieyang.github.io/physicsgen/)
11. EgoMimic: Scaling Imitation Learning via Egocentric Video. [arxiv 2025] [[Paper]](https://arxiv.org/pdf/2410.24221) [[Code]](https://github.com/SimarKareer/EgoMimic) [[Project Page]](https://egomimic.github.io/)

[arxiv 2025] [Paper] [Code] [Project Page]
