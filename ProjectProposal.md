# AI-Based Visual Recognition and Adaptive Object Interaction for a Robotic Hand
## Motivation of project (*INCOMPLETE, can be more professional, too broad.*)
The development of a robotic vision and manipulation system is a valuable project because of the increasing importance of automation, precision, and adaptability in modern industries. Robots are widely used in manufacturing, logistics, healthcare, and other fields, but enabling them to accurately perceive their surroundings and interact with objects remains a significant challenge. By integrating camera-based vision with robotic control, a robot can obtain information about an object's appearance, position, and spatial characteristics, allowing it to perform tasks more accurately and efficiently.

This project provides an opportunity to explore how visual perception can be integrated with robotic manipulation to address practical challenges, such as grasping objects of different shapes, detecting object positions, and adapting to changes in the environment. If tactile sensing is also incorporated, the system could potentially gain additional information about physical contact, improving its ability to handle delicate or irregularly shaped objects.

Overall, this project is valuable because it combines computer vision, robotics, and intelligent control in a practical engineering application. The knowledge gained through its development could contribute to more reliable and adaptable robotic systems while providing hands-on experience in sensor selection, image processing, system integration, and performance evaluation.
## Scope (*INCOMPLETE, make a specific, very precise explanation of the project*)
Machine vision using AI object recognition selects a patter for the hand to grasp the object

## Methods 
1. Software:
    + Mathlab (tentative)
    + python (tentative)
    + GitHub
    + VLM-YOLOE [^6] (tentative)
2. Hardware:
    + Robotic hand
    + Raspberry Pi HQ camera
3. Methodology (tentative) 
    + Large language model 
    + Inverse reinforcement learning
    + Imitation learning [^3]
    + Deep reinforced learning (used by some papers)
    + Deep deterministic policy gradient algorithm (used by some papers, according to  Wang, J. Wang, K. Li (2026)[^1] is the best method)
    + A table- and geometry-constrained gesture-aware pose generation method (TGGP)[^2]
    + Inverse kinematics solver for a robotic hand [^5] (seems antique)
4. Books:
    + Intro to robotics, 3rd edition. Craig.
    + Robotic toolbox for python, peter corke 
## Expected results (*INCOMPLETE, needs to be related to the scope*)
An eye-hand coordinated system that allows a robotic hand to firmly grasp different shapes of objects, without damaging it.  
## Further research
A skin for the robotic hand to sense the force applied, provide friction to enhance grip for different object surface properties. [^4]  
Robotic wrist or arm to increment the degrees of freedom of the robotic hand, thus making it more versatile. 
## Further investigation
https://www.researchgate.net/publication/389590395_Geometry-Aware_3D_Hand-Object_Pose_Estimation_Under_Occlusion_via_Hierarchical_Feature_Decoupling  
https://www.researchgate.net/publication/394014243_Deep_Learning_for_Computer_Vision_Application  
#### References
[^1]: X. Wang, J. Wang, K. Li (2026). EP-DDPG: A deep reinforcement learning framework for visual-tactile fusion in grasping control of humanoid robotic hand. Biomedical Signal Processing and Control.  https://doi.org/10.1016/j.bspc.2026.109897
[^2]: Li, Sheng, Nie, Wang, Zhang, Lu (2027). Lightweight vision-guided pose generation for dexterous-hand grasping in cluttered scenes. Expert Systems with Applications. https://doi.org/10.1016/j.eswa.2026.134811
[^3]: Li, Y., Guo, C., Ren, J., Chen, B., Cheng, C., Zhang, H., & Lu, H. (2025). SoftGrasp: Adaptive grasping for dexterous hand based on multimodal imitation learning. Biomimetic Intelligence and Robotics, 5(2), 100217. https://doi.org/10.1016/j.birob.2025.100217
[^4]: Gerratt, A. P., Sommer, N., Lacour, S. P., & Billard, A. (2014). Stretchable capacitive tactile skin on humanoid robot fingers — First experiments and results. 2014 IEEE-RAS International Conference on Humanoid Robots, 238–245. https://doi.org/10.1109/humanoids.2014.7041366
[^5]: Claret, J.-A., & Suárez, R. (2011). Efficient and practical determination of grasping configurations for anthropomorphic hands. IFAC Proceedings Volumes, 44(1), 14660–14666. https://doi.org/10.3182/20110828-6-it-1002.00711
[^6]: Ao, W., Liu, L., Chen, H., Lin, Z., Han, J., & Ding, G. (2025). YOLOE: Real-time seeing anything (2503.07465v1). arXiv. https://arxiv.org/abs/2503.07465v1

