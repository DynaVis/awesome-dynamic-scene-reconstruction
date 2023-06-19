# Awesome Dynamic Scene Reconstruction [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome dynamic scene reconstruction papers and datasets, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

To contribute to this list, please submit a pull request and edit README.md with a table entry in the following format:<br>
<rawtext>
| [Paper title](paper url) | venue acronym and year | [project](project url) &lt;br> [code](code url) &lt;br> [data](data url) |
</rawtext>

## Papers 
Papers are organised into two categories, "General Scenes" and "Human-centric", with links to paper, project, code and datasets where available.

### General Scenes
|Title|Venue|Links|
|-----| :---:| :---: |
|[DynIBaR Neural Dynamic Image-Based Rendering](https://arxiv.org/abs/2211.11082) | CVPR 2023| [project](https://dynibar.github.io/)<br>[code](https://github.com/google/dynibar)|
|[DynamicStereo: Consistent Dynamic Depth from Stereo Videos](https://arxiv.org/abs/2305.02296) | CVPR 2023 | [project](https://dynamic-stereo.github.io/) <br> [code](https://github.com/facebookresearch/dynamic_stereo)|
|[Temporal Interpolation Is All You Need for Dynamic Neural Radiance Fields](https://arxiv.org/abs/2302.09311)| CVPR 2023 | [project](https://sungheonpark.github.io/tempinterpnerf/) |
|[HexPlane: A Fast Representation for Dynamic Scenes](https://arxiv.org/abs/2301.09632)| CVPR 2023 | [project](https://caoang327.github.io/HexPlane/) <br> [code](https://github.com/Caoang327/HexPlane) |
|[NeRF-DS: Neural Radiance Fields for Dynamic Specular Objects](https://arxiv.org/abs/2303.14435)|CVPR 2023 | [project](https://jokeryan.github.io/projects/nerf-ds/) <br> [code](https://github.com/JokerYan/NeRF-DS) <br> [data](https://github.com/JokerYan/NeRF-DS/releases/tag/v0.1-pre-release) | 
|[Neural 3D Video Synthesis from Multi-view Video](https://arxiv.org/abs/2103.02597)| CVPR 2022 | [project](https://neural-3d-video.github.io/) <br> [data](https://github.com/facebookresearch/Neural_3D_Video) |
|[OcclusionFusion: Occlusion-aware Motion Estimation for Real-time Dynamic 3D Reconstruction](https://arxiv.org/abs/2203.07977) | CVPR 2022 | [project](https://wenbin-lin.github.io/OcclusionFusion/) <br> [code](https://github.com/wenbin-lin/OcclusionFusion/) | 
|[DeepDeform: Learning Non-rigid RGB-D Reconstruction with Semi-supervised Data](https://arxiv.org/abs/1912.04302)| CVPR 2020 | [project](https://niessnerlab.org/projects/bozic2020deepdeform.html) <br> [data](https://github.com/AljazBozic/DeepDeform)|
|[Hybrid Modeling of Non-Rigid Scenes From RGBD Cameras](https://ieeexplore.ieee.org/document/8425011)| TCSVT 2019 | [project](https://cvssp.org/projects/4d/dynamic_rgbd_modelling/) <br> [data](https://cvssp.org/projects/4d/dynamic_rgbd_modelling/) |
|[General Dynamic Scene Reconstruction from Multiple View Video](https://openaccess.thecvf.com/content_iccv_2015/papers/Mustafa_General_Dynamic_Scene_ICCV_2015_paper.pdf)| ICCV 2015 |[project](https://cvssp.org/projects/4DMP/DyRecon/) <br> [data](https://cvssp.org/data/cvssp3d/)|
|[Monocular 3D Reconstruction of Locally Textured Surfaces](https://ieeexplore.ieee.org/document/6186734)| PAMI 2012| [data](https://www.epfl.ch/labs/cvlab/data/data-dsr-index-php/)|
|[3D Reconstruction of Dynamic Scenes with Multiple Handheld Cameras](https://link.springer.com/chapter/10.1007/978-3-642-33709-3_43)| ECCV 2012| - |
|[Multi-view Occlusion Reasoning for Probabilistic Silhouette-Based Dynamic Scene Reconstruction](http://vision.cse.psu.edu/research/3Dreconstruction/relatedWork/papers/GuanAndPollefeys_SilhouetteBased.pdf)| IJCV 2010 | - |

### Human-centric
|Title|Venue|Links|
|-----| :---:| :---: |
|[HumanRF: High-Fidelity Neural Radiance Fields for Humans in Motion](https://arxiv.org/abs/2305.06356)| CVPR 2023 | [project](https://synthesiaresearch.github.io/humanrf/) <br> [code](https://github.com/synthesiaresearch/humanrf) <br> [data](https://www.actors-hq.com/)|
|[Function4D: Real-time Human Volumetric Capture from Very Sparse Consumer RGBD Sensors](https://arxiv.org/abs/2105.01859)| CVPR 2021 | [project](http://www.liuyebin.com/Function4D/Function4D.html) <br> [data](https://github.com/ytrock/THuman2.0-Dataset)|
|[SIZER: A Dataset and Model for Parsing 3D Clothing and Learning Size Sensitive 3D Clothing](https://arxiv.org/abs/2007.11610)| ECCV 2020 | [project](https://virtualhumans.mpi-inf.mpg.de/sizer/) <br> [code](https://github.com/garvita-tiwari/sizer) <br> [data](https://nextcloud.mpi-klsb.mpg.de/index.php/s/nx6wK6BJFZCTF8C/authenticate/showShare) | 
|[DeepHuman: 3D Human Reconstruction from a Single Image](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zheng_DeepHuman_3D_Human_Reconstruction_From_a_Single_Image_ICCV_2019_paper.pdf)| ICCV 2019 | [project](http://www.liuyebin.com/deephuman/deephuman.html) <br> [data](http://www.liuyebin.com/deephuman/deephuman.html) |
|[3DPeople: Modeling the Geometry of Dressed Humans](https://arxiv.org/abs/1904.04571)| ICCV 2019 | [project](https://www.albertpumarola.com/research/3DPeople/index.html) <br> [data](https://cv.iri.upc-csic.es/) |
|[Dynamic FAUST: Registering Human Bodies in Motion](https://ieeexplore.ieee.org/document/8100074)| CVPR 2017 | [project](https://is.mpg.de/publications/dfaust-cvpr-2017)  <br> [data](https://dfaust.is.tue.mpg.de/)|
|[Learning from Synthetic Humans](https://arxiv.org/abs/1701.01370)| CVPR 2017| [project](https://www.di.ens.fr/willow/research/surreal/) <br> [code](https://github.com/gulvarol/surreal) <br> [data](https://www.di.ens.fr/willow/research/surreal/data/) |
|[Unstructured Video-Based Rendering: Interactive Exploration of Casually Captured Videos](https://dl.acm.org/doi/10.1145/1778765.1778824) | SIGGRAPH 2010 | [data](https://cvg.ethz.ch/research/unstructured-vbr/) |
|[Articulated Mesh Animation from Multi-view Silhouettes](http://people.csail.mit.edu/drdaniel/research/vlasic-2008-ama.pdf) | ToG 2008 | [project](http://people.csail.mit.edu/drdaniel/mesh_animation/) <br> [data](http://people.csail.mit.edu/drdaniel/mesh_animation/#data)|


## Dataset Repositories
A list of larger dataset repos that are used for multiple works.
|Title|
|-----|
|[4D Repository](https://kinovis.inria.fr/4d-repository/)|
|[CVSSP3D](https://cvssp.org/data/cvssp3d/)| 


