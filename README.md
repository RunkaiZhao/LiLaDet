## Advancements in 3D Lane Detection Using LiDAR Point Clouds: From Data Collection to Model Development (ICRA 2024)

## Abstract
Advanced Driver-Assistance Systems (ADAS) have successfully
integrated learning-based techniques into vehicle
perception and decision-making. However, their application
in 3D lane detection for effective driving environment
perception is hindered by the lack of comprehensive LiDAR
datasets. The sparse nature of LiDAR point cloud data
prevents an efficient manual annotation process. To solve
this problem, we present LiSV-3DLane, a large-scale 3D lane
dataset that comprises 20k frames of surround-view LiDAR
point clouds with enriched semantic annotation. Unlike
existing datasets confined to a frontal perspective,
LiSV-3DLane provides a full 360-degree spatial panorama
around the ego vehicle, capturing complex lane patterns in
both urban and highway environments. We leverage the
geometric traits of lane lines and the intrinsic spatial
attributes of LiDAR data to design a simple yet effective
automatic annotation pipeline for generating finer lane
labels. To propel future research, we propose a novel
LiDAR-based 3D lane detection model, LiLaDet, incorporating
the spatial geometry learning of the LiDAR point cloud into
Bird’s Eye View (BEV) based lane identification.
Experimental results indicate that LiLaDet outperforms
existing camera- and LiDAR-based approaches in the 3D lane
detection task on the K-Lane dataset and our LiSV-3DLane.
