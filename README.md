# CarNet_databases
This project contains our three crack detection datasets，i.e., Sun520, Rain365, and BJN260.
The datasets can be downloaded from [**aliyundrive**](https://www.aliyundrive.com/s/o2L3v5PCwZQ) with pass code: **3j6f**

# Overview

Cracks as common pavement defects, provide a sign of potential road damage. Pixel-level pavement crack detection is of great importance for intelligent transportation. However, it is challenging since cracks usually manifest themselves in various characteristics, such as low contrast, poor continuity, extreme aspect ratio, multiple scales and etc. These crack charateristics may attribute to some external environments, such as weather, light, crack pictures captured in different viewpoints and etc, or their inherent properties. The figure below shows some visual examples of real cracks: (a) contain shadows on sunny days, (b)rainwater on rainy days, , (c) uneven illuminations in night scenes, and (d) grain-like texture in the background, respectively.

![example](https://github.com/shiyanrubing/CarNet_databases/blob/main/datasets/example/noise_in_cracks_black_00.png)

However, to our knowledge, the existing pavement crack databases are usually captured under clear weather.
Crack data under other weather, such as rainy day, are absent in this field.
Besides, the open-source single dataset for sunny days is small in data scale, e.g. it usually contains no more than 400 images.

Therefore, we propose three new pavement crack databases, i.e. Sun520, Rain365 and BJN260, to promote the relevant research in the community. We annotated the cracks in the pixel level.
We detail each dataset in the following sections.

# Sun520

Sun520 consists of 520 crack images captured on sunny days.
These pictures reflects road surface conditions in the Zhongguancun Campus of University of Chinese Academy of Sciences.
These pictures contain various background noises, such as shadows, oil stains, lane marking, and curved lines of tiles.
Besides, since data were collected in the morning, afternoon, and dusk, Sun520 is rich in image brightness.
Some visual examples are shown below where the first column is the crack image, the second column is the ground truth, the last column is a composition of the crack and ground truth image.

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

Rain365 collects 365 crack images taken after rain.
These images mainly reflects pavement conditions in the South Third Street of Zhongguancun.
Since human eyes hardly distinguish cracks and non-cracks in rainy night scenes, we only utilize post-rain images in the daytime.
Rain365 embraces three backgrounds, i.e., completely wet, partially wet and partially dry, and completely dry.
Among them, the first case is the majority.
Some visual examples are shown below where the first column is the crack image, the second column is the ground truth, the last column is a composition of the crack and ground truth image.

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

BJN260 includes 260 crack images collected at night scene in Beijing.
These images mainly reflect pavement conditions in the side road of North Fourth Ring West Road.
Due to various light sources (e.g. street lamps, car lights, truck lights, etc) and different light intensities, pavement conditions at night are complex and changeable, which brings new challenges to pixel-level detection. Some visual examples are shown below where the first column is the crack image, the second column is the ground truth, the last column is a composition of the crack and ground truth image.

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
```
