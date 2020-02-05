# Rubric points (WIP)

This document gathers information about all the rubric points met for this project.

## Data Buffer

| Point                          | Files                              | Lines          |
|--------------------------------|------------------------------------|----------------|
| MP.1 Data Buffer Optimization  | [ring_buffer.h], [ring_buffer.cpp] | -              |

## Keypoints

| Point                   | Files               | Lines        |
|-------------------------|---------------------|--------------|
| MP.2 Keypoint Detection | [matching_2d.cpp]   | 67, 101, 152 |
| MP.3 Keypoint Removal   | [camera_fusion.cpp] | 69           |

## Descriptors

| Point                          | Files             | Lines        |
|--------------------------------|-------------------|--------------|
| MP.4 Keypoint Descriptors      | [matching_2d.cpp] | 43           |
| MP.5 Descriptor Matching       | [matching_2d.cpp] | 7            |
| MP.6 Descriptor Distance Ratio | [matching_2d.cpp] | 33           |     

## Performance

### MP.7 Performance Evaluation 1

- **Harris**

| Image            | Number of keypoints | Distribution |
|------------------|---------------------|--------------|
| `0000000000.png` | 53                  | Fair         |
| `0000000001.png` | 63                  | Fair         |
| `0000000002.png` | 64                  | Fair         |
| `0000000003.png` | 73                  | Fair         |
| `0000000004.png` | 87                  | Fair         |
| `0000000005.png` | 76                  | Fair         |
| `0000000006.png` | 69                  | Fair         |
| `0000000007.png` | 111                 | Fair         |
| `0000000008.png` | 84                  | Fair         |
| `0000000009.png` | 68                  | Fair         |

- **Shi Tomasi**

| Image            | Number of keypoints | Distribution |
|------------------|---------------------|--------------|
| `0000000000.png` |
| `0000000001.png` |
| `0000000002.png` |
| `0000000003.png` |
| `0000000004.png` |
| `0000000005.png` |
| `0000000006.png` |
| `0000000007.png` |
| `0000000008.png` |
| `0000000009.png` |

- **FAST**

| Image            | Number of keypoints | Distribution |
|------------------|---------------------|--------------|
| `0000000000.png` |
| `0000000001.png` |
| `0000000002.png` |
| `0000000003.png` |
| `0000000004.png` |
| `0000000005.png` |
| `0000000006.png` |
| `0000000007.png` |
| `0000000008.png` |
| `0000000009.png` |

- **BRISK**

| Image            | Number of keypoints | Distribution |
|------------------|---------------------|--------------|
| `0000000000.png` |
| `0000000001.png` |
| `0000000002.png` |
| `0000000003.png` |
| `0000000004.png` |
| `0000000005.png` |
| `0000000006.png` |
| `0000000007.png` |
| `0000000008.png` |
| `0000000009.png` |

- **ORB**

| Image            | Number of keypoints | Distribution |
|------------------|---------------------|--------------|
| `0000000000.png` |
| `0000000001.png` |
| `0000000002.png` |
| `0000000003.png` |
| `0000000004.png` |
| `0000000005.png` |
| `0000000006.png` |
| `0000000007.png` |
| `0000000008.png` |
| `0000000009.png` |

- **AKAZE**

| Image            | Number of keypoints | Distribution |
|------------------|---------------------|--------------|
| `0000000000.png` |
| `0000000001.png` |
| `0000000002.png` |
| `0000000003.png` |
| `0000000004.png` |
| `0000000005.png` |
| `0000000006.png` |
| `0000000007.png` |
| `0000000008.png` |
| `0000000009.png` |

- **SIFT**

| Image            | Number of keypoints | Distribution |
|------------------|---------------------|--------------|
| `0000000000.png` |
| `0000000001.png` |
| `0000000002.png` |
| `0000000003.png` |
| `0000000004.png` |
| `0000000005.png` |
| `0000000006.png` |
| `0000000007.png` |
| `0000000008.png` |
| `0000000009.png` |

### MP.8 Performance Evaluation 2

| Detector      | Descriptor   | Number of matches |
|---------------|--------------|-------------------|
| `BRISK`       | `BRIEF`      |
| `BRISK`       | `BRISK`      |
| `BRISK`       | `FREAK`      |
| `BRISK`       | `ORB`        |
| `AKAZE`       | `BRIEF`      |
| `AKAZE`       | `AKAZE`      |  
| `AKAZE`       | `BRISK`      |
| `AKAZE`       | `FREAK`      |
| `AKAZE`       | `ORB`        |
| `FAST`        | `BRIEF`      |
| `FAST`        | `ORB`        | 
| `SHITOMASI`   | `BRIEF`      | 
| `SHITOMASI`   | `ORB`        |
| `FAST`        | `BRISK`      |
| `FAST`        | `FREAK`      |
| `SHITOMASI`   | `FREAK`      | 
| `SHITOMASI`   | `BRISK`      |
| `ORB`         | `ORB`        |
| `ORB`         | `BRISK`      |
| `SIFT`        | `BRIEF`      |
| `SIFT`        | `FREAK`      |
| `ORB`         | `BRIEF`      |  
| `ORB`         | `FREAK`      |
| `HARRIS`      | `ORB`        |
| `HARRIS`      | `BRIEF`      |
| `HARRIS`      | `BRISK`      |
| `HARRIS`      | `FREAK`      |

### MP.9 Performance Evaluation 3

| Detector      | Descriptor   | Average processing time |
|---------------|--------------|-------------------------|
| `BRISK`       | `BRIEF`      |
| `BRISK`       | `BRISK`      |
| `BRISK`       | `FREAK`      |
| `BRISK`       | `ORB`        |
| `AKAZE`       | `BRIEF`      |
| `AKAZE`       | `AKAZE`      |  
| `AKAZE`       | `BRISK`      |
| `AKAZE`       | `FREAK`      |
| `AKAZE`       | `ORB`        |
| `FAST`        | `BRIEF`      |
| `FAST`        | `ORB`        | 
| `SHITOMASI`   | `BRIEF`      | 
| `SHITOMASI`   | `ORB`        |
| `FAST`        | `BRISK`      |
| `FAST`        | `FREAK`      |
| `SHITOMASI`   | `FREAK`      | 
| `SHITOMASI`   | `BRISK`      |
| `ORB`         | `ORB`        |
| `ORB`         | `BRISK`      |
| `SIFT`        | `BRIEF`      |
| `SIFT`        | `FREAK`      |
| `ORB`         | `BRIEF`      |  
| `ORB`         | `FREAK`      |
| `HARRIS`      | `ORB`        |
| `HARRIS`      | `BRIEF`      |
| `HARRIS`      | `BRISK`      |
| `HARRIS`      | `FREAK`      |

[matching_2d.cpp]: src/matching_2d.cpp
[camera_fusion.cpp]: src/camera_fusion.cpp
