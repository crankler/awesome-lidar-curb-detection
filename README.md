# awesome-lidar-curb-detection [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

The following table consists of many **LiDAR curb / boundary** detection method



### Todolist
- [ ] Translate into English version
- [ ] revise the details that not clearly here
- [ ] add a lidar curb/boundary paper list pkg few days.
- [ ] try to qualitatively contrast the different method
- [ ] try to Quantitative comparison with few paper
  
---
### Compare results
| Method | Link | comment | TODO |
| :------------------: | :-----------------: | :-----------------: |:-----------------: |
| **道路线分割** | [fastseg](https://github.com/shrijitsingh99/fastseg) | 教程输出不同的beam线条 | 测试 |
| **Ring+高度＋曲率** | [CurbDetector](https://github.com/DrGabor/CurbDetector) |matlab代码，比较了三个方法．还是ring的方法好 |测试
| **高度+水平+曲率** | [LidarRoadBoundaryDetection](https://github.com/wangguojun2018/LidarRoadBoundaryDetection) | 开源代码.好! | 测试 |
| **高度+水平+曲率** | [lidar_based_lane_detection_projects](https://github.com/eriche2016/lidar_based_lane_detection_projects) | python版本,测试感觉不错,同上 | 测试 |
| **高度+水平+曲率** | [MATLAB-Curb Detection in 3-D Lidar Point Cloud](https://ww2.mathworks.cn/help/lidar/ug/curb-detection-in-lidar-point-cloud.html) | matlab2022版本,同上 | 测试 |
| 高度差+距离差 | [curb_detection](https://github.com/linyliny/curb_detection) | 开源常见方法,基本同上 | 测试 |
| 高度差+距离差 | [3D_Lidar_curb_detection](https://github.com/SohaibAl-emara/3D_Lidar_Curb_Detection) | 开源常见方法,选择ring进行判断 | 测试
| 高度差+距离差 | [LiDAR-CURB-DETECTION](https://github.com/bigbigpark/LiDAR-CURB-DETECTION) | ransac分割方法,很近距离的 | 测试 |
| 高度+角度+cell | [Curb segmentation from point cloud](https://github.com/Robator/road_curb_segmentation) | 开源常见方法,一般 | 测试 |
| 高度 | [ground_extarct_in_country_road](https://github.com/lzyplayer/ground_extarct_in_country_road) | 新的地面地图+中心线拟合,没跑出来结果 |测试 | 
| **两次提取** | [fast_curb_detection](https://github.com/hey2525/Road-boundary-edge-curb-detection) | 新颖,方法有待提高 | 测试 |
| **grid+x+z** | [urban_road_filter](https://github.com/jkk-research/urban_road_filter)(两个版本,[英文注释版本](https://github.com/jkk-research/urban_road_filter/tree/refactor))  | 新颖,方法有待提高 | 测试 |
| grid | [lidar-road-segmentation](https://github.com/Garrus007/lidar-road-segmentation) | 效果很差 |测试 | 
| 强度 | [LIDAR_ROAD PACKAGE](https://github.com/yunxdai/Intensity-based_Sidewalk_Segmentation) | 浙大自己写的,效果不好 | 测试 |
| 强度 | [Lane-Detection-from-Point-Cloud](https://github.com/jtpils/Lane-Detection-from-Point-Cloud), [Object-Detection-road-boundary](https://github.com/vatsalpatel2605/Object-Detection-in-Point-Cloud-Pole-lane-marking-road-boundary) | 课程作业,效果不好 | 测试 |
| 强度 |[Lane-Marking-Detection](https://github.com/Lukas-Justen/Lane-Marking-Detection) | 课程作业,效果不好 | 测试 |  
| 强度 | [Lane-detection-pointclouds](https://github.com/ashleetiw/Lane-detection-pointclouds), [MATLAB2022-Lane](https://ww2.mathworks.cn/help/lidar/ug/lane-detection-in-3d-lidar-point-cloud.html)   | matlab开源的python转换,很一般:  [lane-detection笔记](https://github.com/ashleetiw/portfolio/blob/65e59372bc8af9deb25aa8d8c39afb9ddd55eb09/_posts/2021-06-10-lane-detection.markdown)| 测试 |
| 强度 | [lidar_lane_detector](https://github.com/kwh950724/lidar_lane_detector) | 代码太简单,效果很差 | 测试 |    
| 强度 | [lidar_lane_py](https://github.com/hojun-Ch/lidar_lane_py) | python写的,看了感觉判据太简单 | 测试 |  
| 强度 | [lane_detection](https://github.com/hyunbeen99/lane_detection) | 最近测的，强度＋聚类后分左右 | 测试 |  
| 法向量 | [Object-detection-road-boundary](https://github.com/rzou15/Object-detection-in-Point-Cloud-road-boundary) , [RoadBoundaryDetection](https://github.com/dengyanbo/PointCloud_RoadBoundaryDetection)| PCL方法,测试+对比了效果,感觉很差 | 测试 | 
| 图像 | [LidarCurbDetection](https://github.com/michaely1113/LidarCurbDetection), [Smear-Detection](https://github.com/shashank918/Smear-Detection) | 就是canny+hough,感觉调参工作多一点,效果复制一般 | 测试 | 
| 雷达直方图 | [lidar histogram](https://github.com/azurity/lidar-hist) | [-45, 45]还行,全角度就不行 |测试 | 
| 高度差+坡度 | [traversability_estimation](https://github.com/leggedrobotics/traversability_estimation) | ETH的地图方法 |TODO | 
| 高度差+坡度 | [traversability_mapping](https://github.com/TixiaoShan/traversability_mapping) | Tixiao shan的地图方法 |TODO | 
| EM | [curb-detection](https://github.com/jmaye/curb-detection) | 方法感觉很新,12年,之后没人做了 | TODO | 
| 图像地面拟合(三角剖分) | [Road_detection_based_on_lidar](https://github.com/YanMinbit/Road_detection_based_on_lidar) | 测试了,主要是视觉的工作 |TODO | 
| **图像+几何** | [RoadMarkingExtraction](https://github.com/YuePanEdward/RoadMarkingExtraction)| 开源中| TODO | 
