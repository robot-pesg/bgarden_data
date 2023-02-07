# BotanicGarden Dataset
## A high-quality and large-scale robot navigation dataset in challenging natural environments

## Authors: 
Yuanzhi Liu, Yujia Fu, Minghui Qin, Yufeng Xu, Baoxin Xu, et al.

## Abstract: 
The rapid developments of mobile robotics and autonomous navigation over the years are largely empowered by public datasets for testing and upgradation, such as SLAM and localization tasks. Impressive demos and benchmark results have arisen, indicating the establishment of a mature technical framework. However, from the real-world deployments point of view, there are still critical defects of robustness in challenging environments, especially in large-scale, GNSS-denied, textural-monotonous, and unstructured scenarios. To meet the urgent validation demands in such scope, we build a novel challenging robot navigation dataset in a large botanic garden of more than 48000m2. Comprehensive sensors are employed, including high-res/rate stereo Gray&RGB cameras, rotational and forward 3D LiDARs, and low-cost and industrial-grade IMUs, all of which are well calibrated and hardware-synchronized to nanoseconds accuracy. An all-terrain wheeled robot is configured to mount the sensor suite and providing odometry data. A total of 32 long and short sequences of 2.3 million images are collected, covering scenes of thick woods, riversides, narrow paths, bridges, and grasslands that rarely appeared in previous resources. Excitedly, both highly-accurate ego-motions and 3D map ground truth are provided, along with fine-annotated vision semantics. Our goal is to contribute a high-quality dataset to advance robot navigation and sensor fusion research to a higher level.

<div align="center">
<img src="./pics/bev_map/bev_whole.png" alt="photo" width="48%" />
<img src="./pics/robot_pics/1.jpg" alt="photo" width="48%" />
</div>

<div align="center">
<img src="./pics/photo_pairs/cam/c_01.png" alt="photo" width="18%" />
<img src="./pics/photo_pairs/cam/c_02.png" alt="photo" width="18%" />
<img src="./pics/photo_pairs/cam/c_03.png" alt="photo" width="18%" />
<img src="./pics/photo_pairs/cam/c_04.png" alt="photo" width="18%" />
<img src="./pics/photo_pairs/cam/c_05.png" alt="photo" width="18%" />
<img src="./pics/photo_pairs/map/m_01.jpg" alt="photo" width="18%" />
<img src="./pics/photo_pairs/map/m_02.jpg" alt="photo" width="18%" />
<img src="./pics/photo_pairs/map/m_03.jpg" alt="photo" width="18%" />
<img src="./pics/photo_pairs/map/m_04.jpg" alt="photo" width="18%" />
<img src="./pics/photo_pairs/map/m_05.jpg" alt="photo" width="18%" />
</div>

## Time Synchronization

<div align="left">
<img src="./pics/pulse_sync.png" alt="photo" width="60%" />
</div>

<!-- ## Ground Truth Map -->

<!-- <div align="center">
<img src="./pics/leica_workphoto.png" alt="photo" width="80%" />
</div> -->

## Semantic Dense Annotations
All data are provided in LabelMe format and support future reproducing. It is expected that these data can strengthen the abili- ties of robust motion estimation and semantic map paintings.
<div align="center">
<img src="./gifs/semantics/1_JPEG_960×600.gif" alt="video" width="48%" />
<img src="./gifs/semantics/1_SegmentationVisualization_960×600.gif" alt="video" width="48%" />
</div>
