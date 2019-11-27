# awesome-point-cloud-registration
A curated list of papers about point cloud registration inspired by [awesome point cloud analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis)

You will be very welcome to make PR and contribute!! :smile:


<h3> Keywords </h3>

__`lf.`__: local features for registration &emsp; | &emsp;
__`est.`__: direct estimation &emsp; | &emsp;
__`dat.`__: datasets &emsp; | &emsp; 

__`opt.`__: optimization &emsp; | &emsp; 
__`oth.`__: other, including outlier rejection

<h3> Statistics <h3> 
 
:fire: code is available & stars >= 100 &emsp;|&emsp; :star: citation >= 50

--- 

## - 2016

- [[CGF](https://dl.acm.org/citation.cfm?id=2600305)] Sparse Iterative Closest Point. [[code](https://github.com/OpenGP/sparseicp)] [`est.` `opt.`] :fire: :star: 

- [[IJRR](https://hal.archives-ouvertes.fr/hal-01143454/document)] Challenging data sets for point cloud registration algorithms. [[code](https://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration)] [`dat.`] :star:


## 2016
## 2017
- [[CVPR](https://arxiv.org/pdf/1603.08182.pdf)] 3DMatch: Learning Local Geometric Descriptors from RGB-D Reconstructions. [[code](https://github.com/andyzeng/3dmatch-toolbox)] [`lf.` `dat.`] :fire: :star:

- [[CVPR](https://zpascal.net/cvpr2017/Elbaz_3D_Point_Cloud_CVPR_2017_paper.pdf)] 3D Point Cloud Registration for Localization using a Deep Neural Network Auto-Encoder. [[code](https://github.com/gilbaz/LORAX)] [`est.`]

- [[ICCV](https://arxiv.org/pdf/1709.05056.pdf)] Learning Compact Geometric Features. [[code](https://github.com/marckhoury/CGF)] [`est.` `dat.`]

## 2018
- [[ECCV](https://eccv2018.org/openaccess/content_ECCV_2018/papers/Zi_Jian_Yew_3DFeat-Net_Weakly_Supervised_ECCV_2018_paper.pdf)] 3DFeat-Net: Weakly Supervised Local 3D Features for Point Cloud Registration [[code](https://github.com/yewzijian/3DFeatNet)] [`lf.`]

- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Tolga_Birdal_PPF-FoldNet_Unsupervised_Learning_ECCV_2018_paper.pdf)] PPF-FoldNet: Unsupervised Learning of Rotation Invariant 3D Local Descriptors [`lf.`]

- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_PPFNet_Global_Context_CVPR_2018_paper.pdf)] PPFNet: Global Context Aware Local Features for Robust 3D Point Matching [`lf.`]

- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Georgakis_End-to-End_Learning_of_CVPR_2018_paper.pdf)] End-to-end learning of keypoint detector and descriptor for pose invariant 3D matching [`lf.`]

- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Vongkulbhisal_Inverse_Composition_Discriminative_CVPR_2018_paper.pdf)] Inverse Composition Discriminative Optimization for Point Cloud Registration [`opt.`]


## 2019
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Aoki_PointNetLK_Robust__Efficient_Point_Cloud_Registration_Using_PointNet_CVPR_2019_paper.pdf)] PointNetLK: Robust & Efficient Point Cloud Registration using PointNet. [[code](https://github.com/hmgoforth/PointNetLK)] [`est.`] :fire:

- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ding_DeepMapping_Unsupervised_Map_Estimation_From_Multiple_Point_Clouds_CVPR_2019_paper.pdf)] DeepMapping: Unsupervised Map Estimation From Multiple Point Clouds. [[code](https://github.com/ai4ce/DeepMapping)] [`est.` `opt.`] :fire:

- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gojcic_The_Perfect_Match_3D_Point_Cloud_Matching_With_Smoothed_Densities_CVPR_2019_paper.pdf)] The Perfect Match: 3D Point Cloud Matching with Smoothed Densities [[code](https://github.com/zgojcic/3DSmoothNet)] [`lf.`]

- [[CVPR](https://songshiyu01.github.io/pdf/L3Net_W.Lu_Y.Zhou_S.Song_CVPR2019.pdf)] L3 -Net: Towards Learning based LiDAR Localization for Autonomous Driving [`lf.` `est.`]

- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Le_SDRSAC_SemidefiniteBased_Randomized_Approach_for_Robust_Point_Cloud_Registration_Without_CVPR_2019_paper.pdf)] SDRSAC: Semidefinite-Based Randomized Approach for Robust Point Cloud Registration without Correspondences [[code](https://github.com/intellhave/SDRSAC)] [ `est.` `opt.`]

- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Deng_3D_Local_Features_for_Direct_Pairwise_Registration_CVPR_2019_paper.pdf)] 3D Local Features for Direct Pairwise Registration [`lf.` `est.`]

- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_3D_Point_Capsule_Networks_CVPR_2019_paper.pdf)] 3D Point Capsule Networks [[code](https://github.com/yongheng1991/3D-point-capsule-networks)] [`lf.`] :fire:

- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Melzi_GFrames_Gradient-Based_Local_Reference_Frame_for_3D_Shape_Matching_CVPR_2019_paper.pdf)] GFrames: Gradient-Based Local Reference Frame
for 3D Shape Matching [`oth.`]

- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gao_FilterReg_Robust_and_Efficient_Probabilistic_Point-Set_Registration_Using_Gaussian_Filter_CVPR_2019_paper.pdf)] FilterReg: Robust and Efficient Probabilistic Point-Set Registration using Gaussian Filter and Twist Parameterization [[code](https://bitbucket.org/gaowei19951004/poser/src/master/)]  [`opt.` `oth.`]

- [[ICCV](https://songshiyu01.github.io/publication/iccv2019_registration/)] DeepVCP: An End-to-End Deep Neural Network for Point Cloud Registration [`est.` `lf.`]

- [[ICCV](https://arxiv.org/abs/1904.00229)] Deep Closest Point: Learning Representations for Point Cloud Registration [[code](https://github.com/WangYueFt/dcp)] [`est.`]

- [[ICCV](https://arxiv.org/pdf/1905.03304.pdf)] USIP: Unsupervised Stable Interest Point Detection from 3D Point Clouds. [[code](https://github.com/lijx10/USIP)] [`lf.`]

- [[ICCV](https://arxiv.org/pdf/1909.06887.pdf)] Learning an Effective Equivariant 3D Descriptor Without Supervision. [`lf.`]

- [[ICCV](https://node1.chrischoy.org/data/publications/fcgf/fcgf.pdf)] Fully Convolutional Geometric Features. [[code](https://github.com/chrischoy/FCGF)][`lf.`]

- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8793857)] Robust low-overlap 3-D point cloud registration for outlier rejection [`est.` `opt.` `oth.`]

- [[ICRA](https://ieeexplore.ieee.org/abstract/document/8793516)] CELLO-3D: Estimating the Covariance of ICP in the Real World [`est.` `opt.` `oth.`]

- [[NeurIPS](https://github.com/weiweisun2018/awesome-point-clouds-registration)] PRNet: Self-Supervised Learning for Partial-to-Partial Registration [`est.`]

- [[TOG](https://gfx.cs.princeton.edu/pubs/Rusinkiewicz_2019_ASO/symm_icp.pdf)] A Symmetric Objective Function for ICP [`est.` `opt.`]

- [[ARXIV](https://arxiv.org/pdf/1904.01701.pdf)] 3DRegNet: A Deep Neural Network for 3D Point Registration [`est.`]

- [[ARXIV](https://arxiv.org/pdf/1910.10328.pdf)] Iterative Matching Point [`est.`]

- [[ARXIV](https://arxiv.org/pdf/1908.07906.pdf)] PCRNet: Point Cloud Registration Network using PointNet Encoding [[code](https://github.com/vinits5/pcrnet)] [`est.`]


