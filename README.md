# One-Shot Affordance Detection
[[code]()]
[[paper]()]
[[supp]()]
[[dataset]()]
[[results]()]
[[tools]()]
> Authors:
> Hongchen Luo, Wei Zhai, Jing Zhang, Yang Cao, Dacheng Tao

## Abstract
Affordance detection refers to identifying the potential action possibilities of objects in an image, which is a crucial ability for robot perception and manipulation. To empower robots with this ability in unseen scenarios, we first consider the challenging one-shot affordance detection problem in this paper, i.e., given a support image that depicts the action purpose, all objects in a scene with the common affordance should be detected. To this end, we devise a One-Shot Affordance Detection Network (OSAD-Net) that firstly estimates the human action purpose and then transfers it to help detect the common affordance from all candidate images. Through collaboration learning, OSAD-Net can capture the common characteristics between objects having the same underlying affordance and learn a good adaptation capability for perceiving unseen affordances.  Besides, we build a Purpose-driven Affordance Dataset v2 (PADv2) by collecting and labeling 30k images from 39 affordance and 94 object categories. With complex scenes and rich annotations, our PADv2 can comprehensively understand the affordance of objects and can even be used in other vision tasks, such as scene understanding, action recognition,  robot manipulation, etc. We present a standard one-shot affordance detection benchmark comparing 11 advanced models in several different fields. Experimental results demonstrate the superiority of our model over previous representative ones in terms of both objective metrics and visual quality.

## Dataset(PADv2)
<p align="center">
    <img src="./img/dataset_summary.png" width="860"/> <br />
    <em> 
    </em>
</p>

2.[http://users.umiacs.umd.edu/~amyers/part-affordance-dataset/](http://users.umiacs.umd.edu/~amyers/part-affordance-dataset/)

4.[https://sites.google.com/site/ocnncrf/](https://sites.google.com/site/ocnncrf/)

5.[http://sor3d.vcl.iti.gr/](http://sor3d.vcl.iti.gr/)

6.[http://www.cs.utoronto.ca/~cychuang/learning2act/](http://www.cs.utoronto.ca/~cychuang/learning2act/)

7.[https://lhc1224.github.io/lhc.github.io/](https://lhc1224.github.io/lhc.github.io/)

<p align="center">
    <img src="./img/dataset_description.png" width="860"/> <br />
    <em> 
    </em>
</p>

<p align="center">
    <img src="./img/dataset_divide.png" width="860"/> <br />
    <em> 
    </em>
</p>

## Experimental Results
### Performance on PADv2
You can download the affordance maps from [Baidu Pan]()
<p align="center">
    <img src="./img/PADV2result.png" width="860"/> <br />
    <em> 
    </em>
</p>

<p align="center">
    <img src="./img/PADV2result2.png" width="860"/> <br />
    <em> 
    </em>
</p>

### Performance on PAD
You can download the affordance maps from [Baidu Pan]()
<p align="center">
    <img src="./img/PADresult.png" width="860"/> <br />
    <em> 
    </em>
</p>

<p align="center">
    <img src="./img/fig_1.png" width="550"/> <br />
    <em> 
    Figure 1: The classification system and statistics of the Purpose-driven Affordance Dataset (PAD), which contains 4,002 images covering 72 object classes and 31 affordance classes.
    </em>
</p>

<p align="center">
    <img src="./img/fig_2.png" width="750"/> <br />
    <em> 
    Figure 2: The word cloud composition of the PAD dataset.
    </em>
</p>

<p align="center">
    <img src="./img/s_fig_1.png"/> <br />
    <em> 
    Figure 3: Example of our PAD dataset.
    </em>
</p>


<p align="center">
    <img src="./img/fig_3.png"/> <br />
    <em> 
    Figure 4: Definition of each affordance in our PAD dataset and the class of objects it contains (1/2).
    </em>
</p>


<p align="center">
    <img src="./img/fig_4.png"/> <br />
    <em> 
    Figure 5: Definition of each affordance in our PAD dataset and the class of objects it contains (2/2).
    </em>
</p>

## Dataset Divide 
You can download the dataset from [Baidu Pan]()
<p align="center">
    <img src="./img/fig_5.png"/> <br />
    <em> 
    Figure 6:  The specific affordance category contained in the test set in the threefold setting.
    </em>
</p>

## Results
You can download the affordance maps from [Baidu Pan]()
<p align="center">
    <img src="./img/fig_6.png"/> <br />
    <em>
    </em>
</p>

<p align="center">
    <img src="./img/fig_7.png"/> <br />
    <em>
    </em>
</p>

<p align="center">
    <img src="./img/fig_8.png" width="550"/> <br />
    <em>
    </em>
</p>

<p align="center">
    <img src="./img/fig_9.png" width="550"/> <br />
    <em>
    </em>
</p>
                                          
<p align="center">
    <img src="./img/fig_10.png" width="550"/> <br />
    <em>
    </em>
</p>

<p align="center">
    <img src="./img/s_fig_2.png"/> <br />
    <em>
    </em>
</p>

<p align="center">
    <img src="./img/s_fig_3.png"/> <br />
    <em>
    </em>
</p>

<p align="center">
    <img src="./img/s_fig_4.png"/> <br />
    <em>
    </em>
</p>



## Citation
