# Awesome Bird's Eye View Perception
This is a repository for Bird's Eye View Perception, including 3D object detection, segmentation, online-mapping and occupancy prediction.

## News
```
- 2023.05.09: An initial version of recent papers or projects.
- 2023.05.12: Adding paper for 3D object detection.
```

## Contents

## Papers
- [Survey](#survey)
- [3D Object Detection](#3d-object-detection) 
  - [Radar Lidar](#radar-lidar)
  - [Radar Camera](#radar-camera)
  - [Lidar Camera](#lidar-camera)
  - [Lidar](#lidar)
  - [Monocular](#monocular)
  - [Multiple Camera](#multiple-camera)
- [BEV Segmentation](#bev-segmentation)
  - [Lidar Camera](#lidar-camera)
  - [Monocular](#monocular)
  - [Multiple Camera](#multiple-camera)
- [Perception Prediction Planning](#perception-prediction-planning)
- [Mapping](#mapping)
- [Occupancy Prediction](#occupancy-prediction)
- [Other](#other)

### Survey
- Vision-Centric BEV Perception: A Survey (Arxiv 2022)[[Paper]](https://arxiv.org/abs/2208.02797) [[Github]](https://github.com/4DVLab/Vision-Centric-BEV-Perception)
- Delving into the Devils of Bird’s-eye-viewPerception: A Review, Evaluation and Recipe (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2209.05324) [[Github]](https://github.com/OpenDriveLab/BEVPerception-Survey-Recipe)
### 3D Object Detection
#### Radar Lidar
- RaLiBEV: Radar and LiDAR BEV Fusion Learning for Anchor Box Free Object Detection System (Arxiv) [[Paper]](https://arxiv.org/pdf/2211.06108.pdf)
#### Radar Camera
- CRAFT: Camera-Radar 3D Object Detectionwith Spatio-Contextual Fusion Transformer (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2209.06535.pdf)
- RadSegNet: A Reliable Approach to Radar Camera Fusion (Arxiv 2022) [[paper]](https://arxiv.org/pdf/2208.03849.pdf)
- Bridging the View Disparity of Radar and Camera Features for Multi-modal Fusion 3D Object Detection (IEEE TIV 2023) [[Paper]](https://arxiv.org/pdf/2208.12079.pdf)
#### Lidar Camera
- Semantic bevfusion: rethink lidar-camera fusion in unified bird’s-eye view representation for 3d object detection (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.04675.pdf)
- Sparse Dense Fusion for 3D Object Detection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2304.04179.pdf)
- EA-BEV: Edge-aware Bird' s-Eye-View Projector for 3D Object Detection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.17895.pdf) [[Github]](https://github.com/hht1996ok/EA-BEV)
- MSMDFusion: Fusing LiDAR and Camera at Multiple Scales with Multi-Depth Seeds for 3D Object Detection (CVPR 2023) [[paper]](https://arxiv.org/pdf/2209.03102.pdf) [[Github]](https://github.com/SxJyJay/MSMDFusion)
#### Lidar
- MGTANet: Encoding Sequential LiDAR Points Using Long Short-Term Motion-Guided Temporal Attention for 3D Object Detection (AAAI 2023)[[paper]](https://arxiv.org/pdf/2212.00442.pdf)[[Github]](https://github.com/HYjhkoh/MGTANet)
#### Monocular
- Learning  2D  to  3D  Lifting  for  Object  Detection  in  3Dfor  Autonomous  Vehicles (IROS 2019) [[Paper]](https://arxiv.org/abs/1904.08494) [[Project Page](https://www.nec-labs.com/research/media-analytics/projects/learning-2d-to-3d-lifting-for-object-detection-in-3d-for-autonomous-vehicles/)
- Orthographic Feature Transform for Monocular 3D Object Detection (BMVC 2019) [[Paper]](http://mi.eng.cam.ac.uk/~cipolla/publications/inproceedings/2019-BMVC-Orthographic-Feature-Transform.pdf) [[Github]](https://github.com/tom-roddick/oft)
- BEV-MODNet: Monocular Camera-based Bird's Eye View Moving Object Detection for Autonomous Driving (ITSC 2021) [[Paper]](https://arxiv.org/abs/2107.04937) [[Project Page]](https://sites.google.com/view/bev-modnet)
- Categorical Depth Distribution Network for Monocular 3D Object Detection (CVPR 2021) [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Reading_Categorical_Depth_Distribution_Network_for_Monocular_3D_Object_Detection_CVPR_2021_paper.pdf) [[Github]](https://github.com/TRAILab/CaDDN)
- PersDet: Monocular 3D Detection in Perspective Bird’s-Eye-View (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2208.09394.pdf)
- Time3D: End-to-End Joint Monocular 3D Object Detection and Tracking for Autonomous Driving (CVPR 2022) [[Paper]](https://arxiv.org/pdf/2205.14882.pdf)
- Monocular 3D Object Detection with Depth from Motion (ECCV 2022) [[paper]](https://arxiv.org/pdf/2207.12988.pdf)[[Github]](https://github.com/Tai-Wang/Depth-from-Motion)
#### Multiple Camera
- Object DGCNN: 3D Object Detection using Dynamic Graphs (NIPS 2021) [[Paper]](https://arxiv.org/pdf/2110.06923.pdf)[[Github]](https://github.com/WangYueFt/detr3d)
- BEVDet: High-Performance Multi-Camera 3D Object Detection in Bird-Eye-View (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2112.11790) [[Github]](https://github.com/HuangJunJie2017/BEVDet)
- DETR3D：3D Object Detection from Multi-view Image via 3D-to-2D Queries (CORL 2021) [[Paper]](https://arxiv.org/abs/2110.06922) [[Github]](https://github.com/WangYueFt/detr3d)
- BEVFusion: A Simple and Robust LiDAR-Camera Fusion Framework (NeurIPS 2022) [[Paper]](https://arxiv.org/abs/2205.13790)[[Github]](https://github.com/ADLab-AutoDrive/BEVFusion)
- Unifying Voxel-based Representation withTransformer for 3D Object Detectio (NeurIPS 2022) [[paper]](https://arxiv.org/pdf/2206.00630.pdf)[[Github]](https://github.com/dvlab-research/UVTR)
- Polar Parametrization for Vision-based Surround-View 3D Detection (arxiv 2022) [[Paper]](https://arxiv.org/abs/2206.10965) [[Github]](https://github.com/hustvl/PolarDETR)
- SRCN3D: Sparse R-CNN 3D Surround-View Camera Object Detection andTracking for Autonomous Driving  (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2206.14451) [[Github]](https://github.com/synsin0/SRCN3D)
- BEVDet4D: Exploit Temporal Cues in Multi-camera 3D Object Detection (Arxuv 2022) [[Paper]](https://arxiv.org/pdf/2203.17054.pdf) [[Github]](https://github.com/HuangJunJie2017/BEVDet)
- BEVStereo: Enhancing Depth Estimation in Multi-view 3D Object Detection with Dynamic Temporal Stere (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2209.10248)[[Github]](https://github.com/Megvii-BaseDetection/BEVStereo)
- MV-FCOS3D++: Multi-View Camera-Only 4D Object Detection with Pretrained Monocular Backbones (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2207.12716.pdf) [[Github]](https://github.com/Tai-Wang/Depth-from-Motion)
- Focal-PETR: Embracing Foreground for Efficient Multi-Camera 3D Object （Arxiv）[[Paper]](https://arxiv.org/pdf/2212.05505.pdf)
- DETR4D: Direct Multi-View 3D Object Detection with Sparse Attention (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.07849.pdf)
- SemanticBEVFusion: Rethink LiDAR-Camera Fusion in Unified Bird's-Eye View Representation for 3D Object Detectio (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.04675.pdf)
- BEV-SAN: Accurate BEV 3D Object Detection via Slice Attention Networks (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.04675.pdf)
- STS: Surround-view Temporal Stereo for Multi-view 3D Detection (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2208.10145)
- BEV-LGKD: A Unified LiDAR-Guided Knowledge Distillation Framework for BEV 3D Object Detection (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.00623.pdf)
- Multi-Camera Calibration Free BEV Representation for 3D Object Detection (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2210.17252.pdf)
- AutoAlign: Pixel-Instance Feature Aggregationfor Multi-Modal 3D Object Detection (IJCAI 2022) [[Paper]](https://www.ijcai.org/proceedings/2022/0116.pdf) 
- Graph-DETR3D: Rethinking Overlapping Regions for Multi-View 3D Object Detection (ACM MM 2022) [[paper]](https://github.com/zehuichen123/Graph-DETR3D)[[Github]](https://github.com/zehuichen123/Graph-DETR3D)
- ORA3D: Overlap Region Aware Multi-view 3D Object Detection (BMVC 2022) [[Paper]](https://arxiv.org/pdf/2207.00865.pdf) [[Project Page]](https://kuai-lab.github.io/bmvc2022ora3d/)
- AutoAlignV2: Deformable Feature Aggregation for DynamicMulti-Modal 3D Object Detection (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680616.pdf)[[Github]](https://github.com/zehuichen123/AutoAlignV2)
- CenterFormer: Center-based Transformer for 3D Object Detection (ECCV 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980487.pdf)[[Github]](https://github.com/TuSimple/centerformer)
- SpatialDETR: Robust Scalable Transformer-Based 3D Object Detection from Multi-View Camera Images with Global Cross-Sensor Attention (ECCV 2022) [[Paper]]([[https://markus-enzweiler.de/downloads/publications/ECCV2022-spatial_detr.pdf](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990226.pdf)](https://arxiv.org/pdf/2211.14710.pdf))[[Github]](https://github.com/cgtuebingen/SpatialDETR)
- Position Embedding Transformation for Multi-View 3D Object Detection (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870523.pdf) [[Github]](https://github.com/megvii-research/PETR)
- BEVDepth: Acquisition of Reliable Depth forMulti-view 3D Object Detection (AAAI 2023) [[Paper]](https://arxiv.org/abs/2206.10092) [[Github]](https://github.com/Megvii-BaseDetection/BEVDepth)
- PolarFormer: Multi-camera 3D Object Detectionwith Polar Transformers (AAAI 2023) [[Paper]](https://arxiv.org/abs/2206.15398)[[Github]](https://github.com/fudan-zvg/PolarFormer)
- A Simple Baseline for Multi-Camera 3D Object Detection (AAAI 2023) [[Paper]](https://arxiv.org/pdf/2208.10035.pdf)[[Github]](https://github.com/zhangyp15/SimMOD)
- Cross Modal Transformer via Coordinates Encoding for 3D Object Dectection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2301.01283.pdf) [[Github]](https://github.com/junjie18/CMT)
- Sparse4D: Multi-view 3D Object Detection with Sparse Spatial-Temporal Fusion (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2211.10581.pdf) [[Github]](https://github.com/linxuewu/Sparse4D)
- BEVSimDet: Simulated Multi-modal Distillation in Bird's-Eye View for Multi-view 3D Object Detection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.16818.pdf)[[Github]](https://github.com/ViTAE-Transformer/BEVSimDet)
- BEVStereo++: Accurate Depth Estimation in Multi-view 3D Object Detection via Dynamic Temporal Stereo (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2304.04185.pdf) 
- BSH-Det3D: Improving 3D Object Detection with BEV Shape Heatmap (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.02000.pdf) [[Github]](https://github.com/mystorm16/BSH-Det3D)
- DORT: Modeling Dynamic Objects in Recurrent for Multi-Camera 3D Object Detection and Tracking (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.16628.pdf) [[Github]](https://github.com/SmartBot-PJLab/DORT)
- Geometric-aware Pretraining for Vision-centric 3D Object Detection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2304.03105.pdf) [[Github]](https://github.com/OpenDriveLab/BEVPerception-Survey-Recipe)
- Exploring Object-Centric Temporal Modeling for Efficient Multi-View 3D Object Detection (Arfxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.11926.pdf) [[Github]](https://github.com/exiawsh/StreamPETR)
- Exploring Recurrent Long-term Temporal Fusion for Multi-view 3D Perception (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.05970.pdf)
- OA-BEV: Bringing Object Awareness to Bird's-Eye-View Representation for Multi-Camera 3D Object Detection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2301.05711.pdf) 
- Temporal Enhanced Training of Multi-view 3D Object Detector via Historical Object Prediction (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2304.00967.pdf)
- VIMI: Vehicle-Infrastructure Multi-view Intermediate Fusion for Camera-based 3D Object Detection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.10975.pdf)
- Object as Query: Equipping Any 2D Object Detector with 3D Detection Ability (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2301.02364.pdf)
- VoxelFormer: Bird’s-Eye-View Feature Generation based on Dual-view Attention for Multi-view 3D Object Detection (Arxiv 2023) [[Paper]](https://github.com/Lizhuoling/VoxelFormer-public) [[Github]](https://arxiv.org/pdf/2304.01054.pdf)
- TiG-BEV: Multi-view BEV 3D Object Detection via Target Inner-Geometry Learning (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2212.13979.pdf) [[Github]](https://github.com/ADLab3Ds/TiG-BEV)
- CrossDTR:  Cross-view  and  Depth-guided  Transformersfor  3D  Object  Detection (ICRA 2023) [[Paper]](https://arxiv.org/pdf/2209.13507.pdf)[[Github]](https://github.com/sty61010/CrossDTR)
- SOLOFusion: Time Will Tell: New Outlooks and A Baseline for Temporal Multi-View 3D Object Detection (ICLR 2023) [[paper]](https://arxiv.org/abs/2210.02443)[[Github]](https://github.com/Divadi/SOLOFusion)
- BEVDistill: Cross-Modal BEV Distillation for Multi-View 3D Object Detection (ICLR 2023) [[Paper]](https://openreview.net/pdf?id=-2zfgNS917)[[Github]](https://github.com/zehuichen123/BEVDistill)
- UniDistill: A Universal Cross-Modality Knowledge Distillation Framework for 3D Object Detection in Bird's-Eye View (CVPR 2023)[[Paper]](https://arxiv.org/pdf/2303.15083.pdf)[[Github]](https://github.com/megvii-research/CVPR2023-UniDistill)
- Understanding the Robustness of 3D Object Detection with Bird's-Eye-View Representations in Autonomous Driving (CVPR 2023) [[Paper]](https://arxiv.org/pdf/2303.17297.pdf) 
- Uni3D: A Unified Baseline for Multi-dataset 3D Object Detection (CVPR 2023) [[Paper]](https://arxiv.org/pdf/2303.06880.pdf) [[Github]](https://github.com/PJLab-ADG/3DTrans)
- Aedet: Azimuth-invariant multi-view 3d object detection (CVPR 2023) [[Paper]](https://arxiv.org/pdf/2211.12501.pdf) [[Github]](https://github.com/fcjian/AeDet) [[Project]](https://fcjian.github.io/aedet/)
- BEVHeight: A Robust Framework for Vision-based Roadside 3D Object Detection (CVPR 2023) [[Paper]](https://arxiv.org/pdf/2303.08498.pdf) [[Github]](https://github.com/ADLab-AutoDrive/BEVHeight)
- CAPE: Camera View Position Embedding for Multi-View 3D Object Detection (CVPR 2023) [[Paper]](https://arxiv.org/pdf/2303.10209.pdf) [[Github]](https://github.com/kaixinbear/CAPE)
-  FrustumFormer: Adaptive Instance-aware Resampling for Multi-view 3D Detection (CVPR 2023) [[Paper]](https://arxiv.org/pdf/2301.04467.pdf) [[Github]](https://github.com/robertwyq/frustum)
### BEV Segmentation
#### Lidar Camera
- PETRv2: A Unified Framework for 3D Perception from Multi-Camera Images (Axxiv 2023) [[Paper]](https://arxiv.org/pdf/2206.01256.pdf) [[Github]](https://github.com/megvii-research/PETR)
- X-Align: Cross-Modal Cross-View Alignment for Bird’s-Eye-View Segmentation (WACV 2023) [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Borse_X-Align_Cross-Modal_Cross-View_Alignment_for_Birds-Eye-View_Segmentation_WACV_2023_paper.pdf) 
- BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird's-Eye View Representation (ICRA 2023) [[Paper]](https://arxiv.org/pdf/2205.13542.pdf) [[Github]](https://github.com/mit-han-lab/bevfusion) [[Project]](https://bevfusion.mit.edu/)
#### Monocular
- Predicting Semantic Map Representations from Imagesusing Pyramid Occupancy Networks (CVPR 2020) [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Roddick_Predicting_Semantic_Map_Representations_From_Images_Using_Pyramid_Occupancy_Networks_CVPR_2020_paper.pdf) [[Github]](https://github.com/tom-roddick/mono-semantic-maps)
- Projecting Your View Attentively: Monocular Road Scene Layout Estimation viaCross-view Transformation (CVPR 2021) [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Projecting_Your_View_Attentively_Monocular_Road_Scene_Layout_Estimation_via_CVPR_2021_paper.pdf) [[Github]](https://github.com/JonDoe-297/cross-view)
- Bird's-Eye-View Panoptic Segmentation Using Monocular Frontal View Images (IEEE RA-L 2022) [[Paper]](https://arxiv.org/pdf/2108.03227.pdf) [[Github]](https://github.com/robot-learning-freiburg/PanopticBEV) [[Project]](http://panoptic-bev.cs.uni-freiburg.de/)
- Understanding Bird's-Eye View of Road Semantics using an Onboard Camera (ICRA 2022) [[Paper]](https://arxiv.org/pdf/2012.03040.pdf) [[Github]](https://github.com/ybarancan/BEV_feat_stitch)
- Translating Images into Maps (ICRA 2022) [[Paper]](https://arxiv.org/pdf/2110.00966.pdf) [[Github]](https://github.com/avishkarsaha/translating-images-into-maps)
- BEVSegFormer: Bird’s Eye View Semantic Segmentation From ArbitraryCamera Rigs (WACV 2023) [[Paper]](https://openaccess.thecvf.com/content/WACV2023/papers/Peng_BEVSegFormer_Birds_Eye_View_Semantic_Segmentation_From_Arbitrary_Camera_Rigs_WACV_2023_paper.pdf)
- DiffBEV: Conditional Diffusion Model for Bird's Eye View Perception (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2303.08333.pdf) [[Github]](https://github.com/JiayuZou2020/DiffBEV)
- GitNet: Geometric Prior-based Transformation for Birds-Eye-View Segmentation (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136610390.pdf)
- HFT: Lifting Perspective Representations via Hybrid Feature Transformation (ICRA 2023) [[Paper]](https://arxiv.org/pdf/2204.05068.pdf) [[Github]](https://github.com/JiayuZou2020/HFT)
- SkyEye: Self-Supervised Bird's-Eye-View Semantic Mapping Using Monocular Frontal View Images (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2302.04233.pdf)
#### Multiple Camera
- Cross-view Transformers for real-time Map-view Semantic Segmentation (CVPR 2022) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Cross-View_Transformers_for_Real-Time_Map-View_Semantic_Segmentation_CVPR_2022_paper.pdf) [[Github]](https://github.com/bradyz/cross_view_transformers)
- Scene Representation in Bird’s-Eye View from Surrounding Cameras withTransformers (CVPR@ 2022) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022W/WAD/papers/Zhao_Scene_Representation_in_Birds-Eye_View_From_Surrounding_Cameras_With_Transformers_CVPRW_2022_paper.pdf)
- M2BEV: Multi-Camera Joint 3D Detection and Segmentation with Unified Birds-Eye View Representation (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2204.05088.pdf) [[Project]](https://nvlabs.github.io/M2BEV/)
- BEVerse: Unified Perception and Prediction in Birds-Eye-View for Vision-Centric Autonomous Driving (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2205.09743.pdf) [[Github]](https://github.com/zhangyp15/BEVerse)
- Efficient and Robust 2D-to-BEV Representation Learning via Geometry-guided Kernel Transformer (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2206.04584.pdf) [[Github]](https://github.com/hustvl/GKT)
- A Simple Baseline for BEV Perception Without LiDAR (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2206.07959.pdf) [[Github]](https://github.com/aharley/simple_bev) [[Project Page]](https://simple-bev.github.io/)
- UniFusion: Unified Multi-view Fusion Transformer for Spatial-Temporal Representation in Bird's-Eye-View (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2207.08536.pdf) [[Github](https://github.com/cfzd/UniFusion)
- Estimation  of  Appearance  and  Occupancy  Information  in  Bird’s  EyeView  from  Surround  Monocular  Images (Arxiv 2022) [[paper]](https://arxiv.org/pdf/2211.04557.pdf) [[Project]](https://uditsinghparihar.github.io/APP_OCC/)
- LaRa: Latents and Rays for Multi-CameraBird’s-Eye-View Semantic Segmentation (CORL 2022) [[Paper]](https://proceedings.mlr.press/v205/bartoccioni23a/bartoccioni23a.pdf)) [[Github]](https://github.com/valeoai/LaRa)
- CoBEVT: Cooperative Bird’s Eye View Semantic Segmentation with Sparse Transformers (CORL 2022) [[Paper]](https://arxiv.org/pdf/2207.02202.pdf) [[Github]](https://github.com/DerrickXuNu/CoBEVT)
- Vision-based Uneven BEV Representation Learningwith Polar Rasterization and Surface Estimation (CORL 2022) [[Paper]](https://arxiv.org/pdf/2207.01878.pdf) [[Github]](https://github.com/SuperZ-Liu/PolarBEV)
- BEVFormer: a Cutting-edge Baseline for Camera-based Detection (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136690001.pdf) [[Github]](https://github.com/fundamentalvision/BEVFormer)
- JPerceiver: Joint Perception Network for Depth, Pose and Layout Estimation in Driving Scenes (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980692.pdf) [[Github]](https://github.com/sunnyHelen/JPerceiver)
- Learning Ego 3D Representation as Ray Tracing (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136860126.pdf) [[Github]](https://github.com/fudan-zvg/Ego3RT)
- Fast-BEV: Towards Real-time On-vehicle Bird's-Eye View Perception (NIPS 2022 Workshop) [[Paper]](https://arxiv.org/pdf/2301.07870.pdf) or [[Paper]](https://arxiv.org/pdf/2301.12511.pdf) [[Github]](https://github.com/Sense-GVT/Fast-BEV)
- BEVFormer v2: Adapting Modern Image Backbones toBird’s-Eye-View Recognition via Perspective Supervision (CVPR 2023) [[Paper]](https://arxiv.org/pdf/2211.10439.pdf)
- MatrixVT: Efficient Multi-Camera to BEV Transformation for 3D Perception (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2211.10593.pdf) [[Github]](https://github.com/ZRandomize/MatrixVT)

### Perception Prediction Planning
- FIERY: Future Instance Prediction in Bird’s-Eye View from Surround Monocular Cameras (ICCV 2021) [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_FIERY_Future_Instance_Prediction_in_Birds-Eye_View_From_Surround_Monocular_ICCV_2021_paper.pdf) [[Github]](https://github.com/wayveai/fiery) [[Project]](https://anthonyhu.github.io/fiery)
- ST-P3: End-to-end Vision-based AutonomousDriving via Spatial-Temporal Feature Learning (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980522.pdf) [[Github]](https://github.com/OpenPerceptionX/ST-P3)
- StretchBEV: Stretching Future InstancePrediction Spatially and Temporally (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980436.pdf) [[Github]](https://github.com/kaanakan/stretchbev) [[Projet]](https://kuis-ai.github.io/stretchbev/)
### Mapping
### Occupancy Prediction 
### Other
- Semantic MapNet: Building Allocentric Semantic Maps and Representations from Egocentric Views (AAAI 2021) [[Paper]](https://arxiv.org/pdf/2010.01191.pdf) [[Github]](https://github.com/vincentcartillier/Semantic-MapNet) [[Project]](https://vincentcartillier.github.io/smnet.html) 
