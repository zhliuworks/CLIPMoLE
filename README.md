## CLIPMoLE

**Mixture of Low-rank Experts for Transferable Generated Image Detection**

Paper, code, and pre-trained models will be released soon.

### Introduction

<img src="https://github.com/zhliuworks/CLIPMoLE/blob/master/assets/overview.png" alt="overview"/>

### Results

As in Table 1, our top-performing method (ViT-L/14) has substantial improvements compared to the leading baseline, i.e., UnivFD [6],
achieving +4.07 mAP across all settings and +3.64 mAP across unseen diffusion & autoregressive models (LDM+Glide+Guided+DALL-E).

<img src="https://github.com/zhliuworks/CLIPMoLE/blob/master/assets/generalization_univfd_ap.png" alt="generalization_univfd_ap"/>


### References

[1] Sheng-Yu Wang, Oliver Wang, Richard Zhang, Andrew Owens, and Alexei A. Efros. Cnn-generated images are surprisingly easy to spot... for now. In IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), pages 8692–8701. IEEE, 2020.

[2] Lucy Chai, David Bau, Ser-Nam Lim, and Phillip Isola. What makes fake images detectable? understanding properties that generalize. In European Conference on Computer Vision (ECCV), pages 103–120. Springer, 2020.

[3] Lakshmanan Nataraj, Tajuddin Manhar Mohammed, B. S. Manjunath, Shivkumar Chandrasekaran, Arjuna Flenner, Jawadul H. Bappy, and Amit K. Roy-Chowdhury. Detecting GAN generated fake images using co-occurrence matrices. In Media Watermarking, Security, and Forensics, 2019.

[4] Xu Zhang, Svebor Karaman, and Shih-Fu Chang. Detecting and simulating artifacts in GAN fake images. In IEEE International Workshop on Information Forensics and Security (WIFS), pages 1–6. IEEE, 2019.

[5] Zhendong Wang, Jianmin Bao, Wengang Zhou, Weilun Wang, Hezhen Hu, Hong Chen, and Houqiang Li. DIRE for diffusion-generated image detection. In Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), pages 22445–22455, 2023.

[6] Utkarsh Ojha, Yuheng Li, and Yong Jae Lee. Towards universal fake image detectors that generalize across generative models. In IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), pages 24480–24489. IEEE, 2023.