# CarNet_databases
This project contains our three crack detection datasets，i.e., Sun520, Rain365, and BJN260.
The datasets can be downloaded from [**aliyundrive**](https://www.aliyundrive.com/s/o2L3v5PCwZQ) with pass code: **3j6f**

# Overview

Cracks as common pavement defects, provide a sign of potential road damage. Pixel-level pavement crack detection is of great importance for intelligent transportation. However, it is challenging since cracks usually manifest themselves in various characteristics, such as low contrast, poor continuity, extreme aspect ratio, multiple scales, etc. These crack characteristics may be attributed to some external environment, such as weather, light, captured viewpoint, etc. The figure below shows some visual examples of real cracks: (a) shadows on sunny days, (b) rainwater on rainy days, (c) uneven illuminations in night scenes, and (d) grain-like textures in the background images, respectively.

![example](https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/example/noise_in_cracks_black_00.png)

However, to the best of our knowledge, the existing pavement crack databases are usually captured on clear sunny days. The crack data for other scenarios, such as night and rain, are not available in this domain. Also, the open-source single database data size for sunny weather is small, e.g. it usually contains no more than 400 images.

Therefore, we propose three new pavement crack databases, namely Sun520, Rain365, and BJN260, to facilitate related research in the community. We annotated cracks at the pixel level. We describe each database in detail in the following sections.


# Sun520

Sun520 consists of 520 crack images taken on sunny days. These pictures reflect the road conditions of the Zhongguancun campus of the University of Chinese Academy of Sciences. These images contain various background noises such as shadows, oil stains, lane markings, and the curves of tiles. In addition, because the images were collected in the morning, afternoon and dusk, they have rich image brightness. Some visual examples are shown below, where the first column is the crack image, the second column is the ground truth, and the last column is the composite of the crack and ground truth image.

<table>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/img/IMG_20201021_113730.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/gt/IMG_20201021_113730.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/visualization/IMG_20201021_113730.png"></center></td>
    </tr>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/img/IMG_20201025_155556.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/gt/IMG_20201025_155556.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/visualization/IMG_20201025_155556.png"></center></td>
    </tr>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/img/IMG_20201025_171017.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/gt/IMG_20201025_171017.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Sun520/visualization/IMG_20201025_171017.png"></center></td>
    </tr>
</table>

# Rain365

Rain365 contains 365 crack images taken after rain. These pictures mainly reflect the pavement condition of Zhongguancun South Third Street. Since it is difficult for the human eye to distinguish cracks from non-cracks in rainy night scenes, we only use post-rain images during daytime. Rain365 includes three kinds of backgrounds: full wet, half wet and half dry, and full dry. Among them, the first case is the majority. Some visual examples are shown below, where the first column is the crack image, the second column is the ground truth, and the last column is the composite of the crack and ground truth image.

<table>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/img/IMG_20200923_172845.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/gt/IMG_20200923_172845.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/visualization/IMG_20200923_172845.png"></center></td>
    </tr>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/img/IMG_20200923_181049.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/gt/IMG_20200923_181049.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/visualization/IMG_20200923_181049.png"></center></td>
    </tr>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/img/IMG_20200923_181358.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/gt/IMG_20200923_181358.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/Rain365/visualization/IMG_20200923_181358.png"></center></td>
    </tr>
</table>

# BJN260
BJN260 includes 260 crack images collected at night scene in Beijing. These pictures mainly reflect the pavement condition of the side road of West North Fourth Ring Road. Due to various light sources (e.g. street lamps, car lights, truck lights, etc) and different light intensities, pavement conditions at night are complex and changeable, which brings new challenges to pixel-level detection. Some visual examples are shown below, where the first column is the crack image, the second column is the ground truth, and the last column is the composition of the crack and ground truth image.

<table>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/img/IMG_20201025_174847.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/gt/IMG_20201025_174847.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/visualization/IMG_20201025_174847.png"></center></td>
    </tr>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/img/IMG_20201025_180707.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/gt/IMG_20201025_180707.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/visualization/IMG_20201025_180707.png"></center></td>
    </tr>
    <tr>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/img/IMG_20201116_222434.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/gt/IMG_20201116_222434.png" ></center></td>
        <td ><center><img src="https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/BJN260/visualization/IMG_20201116_222434.png"></center></td>
    </tr>
</table>


# Citation

```
@article{li2021fast,
    title={Fast and Accurate Road Crack Detection Based on Adaptive Cost-Sensitive Loss Function},
    author={Kai Li and Bo Wang and Yingjie Tian and Zhiquan Qi},
    journal={IEEE Transactions on Cybernetics},
    pages={1-12},
    year={2021},
    doi={10.1109/TCYB.2021.3103885}
}

@article{li2023fast,
  title={{Rethinking Lightweight Convolutional Neural Networks for Efficient and High-quality Pavement Crack Detection}},
  author={Kai Li, Jie Yang, Siwei Ma, Bo Wang, Shanshe Wang, Yingjie Tian, and Zhiquan Qi},
journal="arXiv preprint arXiv:2109.05707",
  year={2023}
  }
```
