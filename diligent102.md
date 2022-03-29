---
layout: default
title: DiLiGent10<sup>2</sup>
description: A Photometric Stereo Benchmark Dataset with Controlled Shape and Material Variation
show_downloads: true
---

![diligent102](./imgs/poster.png)
<p style="text-align:justify">Evaluating photometric stereo using real-world dataset is important yet difficult. Existing datasets are insufficient due to their limited scale and random distributions in shape and material. This paper presents a new real-world photometric stereo dataset with “ground truth” normal maps, which is 10 times larger than the widely adopted one. More importantly, we propose to control the shape and material variations by fabricating objects from CAD models with carefully selected materials, covering typical aspects of reflectance properties that are distinctive for evaluating photometric stereo methods. By benchmarking recent photometric stereo methods using these 100 sets of images, with a special focus on recent learning based solutions, a 10×10 shape-material error distribution matrix is visualized to depict a “portrait” for each evaluated method. From such comprehensive analysis, open problems in this field are discussed. </p>
<br><br>



# Datatset
100 objects matrix with 10 shapes-by-10 materials<br>
<table>
  <tr>
    <th><font color="dodgerblue">Shapes</font></th>
    <th>Ball</th>
    <th>Golf</th>
    <th>Spike</th>
    <th>Nut</th>
    <th>Square</th>
    <th>Pentagon</th>
    <th>Hexagon</th>
    <th>Propeller</th>
    <th>Turbine</th>
    <th>Bunny</th>
  </tr>
  <tr>
      <th><font color="dodgerblue">Materials</font></th>
      <th>Pom</th>
      <th>Pp</th>
      <th>Nylon</th>
      <th>Pvc</th>
      <th>Abs</th>
      <th>Bakelite</th>
      <th>Al</th>
      <th>Cu</th>
      <th>Steel</th>
      <th>Acylic</th>
  </tr>
</table>
<br><br>


# Equipment
![cage](./imgs/equipmentAll.png)
- Dark specular balls for calibration "on the fly";
- Omnidirectional illumination stage;
- Darkroom cage;
<br><br>


## Results
![heatmap](./imgs/heatmap.png)
A 10×10 shape-material error distribution matrix is visualized to depict a “portrait” for each evaluated method.
<br><br>




## Files
- Paper([PDF](./imgs/pdfs/00793.pdf))
- Supplementary([PDF](./imgs/pdfs/00793-supp.pdf))
- Dataset([DownLoad.zip](http://120.27.211.155:8080/DiLiGenT100.zip))
- [<font color="dodgerblue">Evaluation WebSite</font>](http://120.27.211.155)
<br/><br/>


## Citations
```bib
@InProceedings{Ren_2021_CVPR,
    author    = {Ren, Jieji and Wang, Feishi and Zhang, Jiahaoand Zheng, Qian and Ren Mingjun and Shi, Boxin},
    title     = {DiLiGenT102: A Photometric Stereo Benchmark Dataset with Controlled Shape and Material Variation},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2022},
    pages     = {0000-0000}
}

```
<br><br>



## Authors
[Jieji Ren]()     &nbsp;&nbsp;[FeiShi Wang]()     &nbsp;&nbsp;[Jiahao Zhang]()      &nbsp;&nbsp;[Qian Zheng](https://q-zh.github.io)      &nbsp;&nbsp;[Mingjun Ren](https://me.sjtu.edu.cn/teacher_directory1/renmingjun.html)     &nbsp;&nbsp;[Boxin Shi](https://ci.idm.pku.edu.cn/People.htm)





<br><br>
---
[<--- Back to Main Page <--- ](./)



