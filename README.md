# ORB_SLAM3-PythonBindings
A python wrapper for ORB_SLAM3, which can be found at [https://github.com/hello-binit/ORB_SLAM3](https://github.com/hello-binit/ORB_SLAM3).
It has been tested on ubuntu 22.04 and built against Python3.10, although it does not rely on any python3 features.

This repo has been forked from:
 - https://github.com/hello-atharva/ORB_SLAM3-PythonBindings
 - https://github.com/hello-atharva/ORB_SLAM2-PythonBindings
 - https://github.com/jskinn/ORB_SLAM2-PythonBindings

## Installation

Follow [install.sh](https://github.com/hello-binit/ORB_SLAM3/blob/patch-1/INSTALL.md).

## Examples

ORBSLAM3's examples have been re-implemented in python in the examples folder.
Run them with the same parameters as the ORBSLAM examples, i.e.:

```
python3 examples/orbslam_mono_tum.py [PATH_TO_ORBSLAM]/Vocabulary/ORBvoc.txt [PATH_TO_ORBSLAM]/Examples_old/Monocular/TUM2.yaml [PATH_TO_TUM]/rgbd_dataset_freiburg2_pioneer_slam/
```

```
python3 orbslam_mono_kitti.py [PATH_TO_ORBSLAM]/Vocabulary/ORBvoc.txt [PATH_TO_ORBSLAM]/Examples/Monocular/KITTI00-02.yaml [PATH_TO_KITTI]/sequences/00/
```

## License
This code is licensed under the BSD Simplified license, although it requires and links to ORB_SLAM2, which is available under the GPLv3 license

It uses pyboostcvconverter (https://github.com/Algomorph/pyboostcvconverter) by Gregory Kramida under the MIT licence (see pyboostcvconverter-LICENSE).

