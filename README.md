# 0-MMS: Zero-Shot Multi-Motion Segmentation With A Monocular Event Camera

**PRGFlow** by <a href="http://prg.cs.umd.edu"><i>Perception & Robotics Group</i></a> at the Department of Computer Science, <a href="https://umd.edu/">University of Maryland- College Park</a>.

### Dataset

The dataset is extension of [MOD dataset](https://arxiv.org/pdf/1906.02919.pdf). Please follow instructions for accessing dataset in ROS and Python [here](https://github.com/prgumd/EVDodgeNet/wiki) 

![0-MMS: Zero-Shot Multi-Motion Segmentation With A Monocular Event Camera](http://prg.cs.umd.edu/research/0-MMS_files/Banner.png)

### Abstract

Segmentation of moving objects in dynamic scenes is a key process in scene understanding for navigation tasks. Classical cameras suffer from motion blur in such scenarios rendering them effete. On the contrary, event cameras, because of their high temporal resolution and lack of motion blur, are tailor-made for this problem. We present an approach for monocular multi-motion segmentation, which combines bottom-up feature tracking and top-down motion compensation into a unified pipeline, which is the first of its kind to our knowledge. Using the events within a time-interval, our method segments the scene into multiple motions by splitting and merging. 

We further speed up our method by using the concept of motion propagation and cluster keyslices. The approach was successfully evaluated on both challenging real-world and synthetic scenarios from the EV-IMO, EED, and MOD datasets and outperformed the state-of-the-art detection rate by 12%, achieving a new state-of-the-art average detection rate of 81.06%, 94.2% and 82.35% on the aforementioned datasets. To enable further research and systematic evaluation of multi-motion segmentation, we present and open-source a new dataset/benchmark called MOD++, which includes challenging sequences and extensive data stratification in-terms of camera and object motion, velocity magnitudes, direction, and rotational speeds.



- [Project Page](https://prg.cs.umd.edu/0-MMS)
- [Paper](https://prg.cs.umd.edu/research/0-MMS_files/0-MMS.pdf)
- [arXiv Preprint](https://arxiv.org/pdf/2006.06158.pdf)


## License:
Copyright (c) 2020 Perception and Robotics Group (PRG)
