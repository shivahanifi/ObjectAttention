# A pipeline for estimating human attention toward objects with on-board cameras on the iCub humanoid robot
This is the official repository of the paper titled "A pipeline for estimating human attention toward objects with on-board cameras on the iCub humanoid robot".

![pipeline_humanattention_revised](https://github.com/user-attachments/assets/42e6035f-7760-41c2-8b8a-a18d67974000)

## Abstract
This research report introduces a learning system designed to detect the object that humans are gazing at, using solely visual feedback. By incorporating face detection, human attention prediction, and online object detection the system enables the robot to perceive and interpret human gaze accurately, thereby facilitating the establishment of joint attention with human partners. Additionally, a novel dataset collected with the humanoid robot iCub is introduced, comprising over 22, 000 images from ten participants gazing at different annotated objects. This dataset serves as a benchmark for human gaze estimation in table-top human-robot interaction (HRI) contexts. In this work, we use it to assess the proposed pipeline’s performance and examine each component’s effectiveness. Furthermore, the developed system is deployed on the iCub, and a supplementary video showcases its functionality. The results demonstrate the potential of the proposed approach as a first step to enhance social awareness and responsiveness in social robotics. This advancement can enhance assistance and support in collaborative scenarios, promoting more efficient human-robot collaborations.

## ObjectAttention dataset
The proposed dataset depicts human-robot interactions in a table-top scenario where the human partner gazes at different objects. The ObjectAttention dataset consists of 250 videos (22, 732 frames), depicting 10 participants in 2 different trials for 5 sessions, gazing at the different objects.

![Screenshot from 2024-10-08 15-36-16](https://github.com/user-attachments/assets/b73ffefc-71c4-42ac-bedd-b96bc011aedb)

## Requirements
The following modules are required for the proposed pipeline. 
### OpenPose
This is the requirement of _Human Attention Estimation_ pathway to detect anatomical key-points. Please follow the instructions provided in the [OpenPose repository](https://github.com/CMU-Perceptual-Computing-Lab/openpose) for proper installation.
### Online object detection
This is the erequirement of _Object Detection_ pathway to detect objects. Please follow the instructions provided in the [Online detection repository](https://github.com/hsp-iit/online-detection) for proper installation.
## Citation
## License
