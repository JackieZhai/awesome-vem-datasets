# Awesome vEM Datasets

[![Awesome](https://awesome.re/badge.svg)](https://github.com/topics/awesome)
[![Commit](https://img.shields.io/github/last-commit/JackieZhai/awesome-em-datasets)](https://github.com/JackieZhai/awesome-em-datasets/commits)
[![RepoSize](https://img.shields.io/github/repo-size/JackieZhai/awesome-em-datasets)](https://github.com/JackieZhai/awesome-em-datasets/archive/refs/heads/master.zip)


## Contents

* [Overview](https://github.com/JackieZhai/awesome-em-datasets#overview)
* [Background](https://github.com/JackieZhai/awesome-em-datasets/blob/master/BACKGROUND.md)
* [Reference](https://github.com/JackieZhai/awesome-em-datasets/blob/master/REFERENCE.md)
* Materials
    * [Elaborate Review](https://github.com/JackieZhai/awesome-em-datasets#elaborate-review)
    * [Open-access Resource](https://github.com/JackieZhai/awesome-em-datasets#open-access-resource)
    * [Related Work](https://github.com/JackieZhai/awesome-em-datasets#related-work)
* [Group](https://github.com/JackieZhai/awesome-em-datasets#group)
* [Contribution](https://github.com/JackieZhai/awesome-em-datasets#contribution)


## Overview

We are mainly focusing connectomics datasets generated by the volume electron microscopy.

### Challenge-level Datasets (size ~10<i>μm<sup>3</sup></i>)

<table>
    <tr>
        <th>Name<br><i>for short</i></th>
        <th>Species</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sample&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Microscopy&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>Size<br><i>μm<sup>3</sup></i></th>
        <th>Resolution<br><i>nm<sup>3</sup></i></th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Number&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>Link</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Reference&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Note&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
    </tr>
    <tr>
        <td rowspan="2">AxonEM</td>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>ssTEM</td>
        <td rowspan="2">30x30x30</td>
        <td>7x7x40</td>
        <td rowspan="2">18,000 axons</td>
        <td rowspan="2"><a href="https://axonem.grand-challenge.org/">grand-challenge</a></td>
        <td rowspan="2">Wei <i>et al.</i>, <a href="https://github.com/JackieZhai/awesome-em-datasets#2021">2021</a></td>
        <td rowspan="2">subsets of MICrONS and H01</td>
    </tr>
    <tr>
        <td>human</td>
        <td>temporal cortex</td>
        <td>ATUM-mSEM</td>
        <td>8x8x30</td>
    </tr>
    <tr>
        <td>ISBI</td>
        <td>drosophila</td>
        <td>ventral nerve line</td>
        <td>ssTEM</td>
        <td>2x2x1.5</td>
        <td>4x4x50</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Segmentation of neuronal structures in EM stacks</td>
    </tr>
    <tr>
        <td>SNEMI3D</td>
        <td>mouse</td>
        <td>cortex</td>
        <td>ATUM-SEM</td>
        <td>6x6x3</td>
        <td>6x6x30</td>
        <td></td>
        <td></td>
        <td></td>
        <td>SNEMI3D: 3D Segmentation of neurites in EM images</td>
    </tr>
    <tr>
        <td>AC3/AC4</td>
        <td>mouse</td>
        <td>cortex</td>
        <td>ATUM-SEM</td>
        <td>6x6x3</td>
        <td>6x6x30</td>
        <td></td>
        <td></td>
        <td></td>
        <td>different membrane labeling at myelin</td>
    </tr>
    <tr>
        <td>CREMI</td>
        <td>drosophila</td>
        <td>melanogaster brain</td>
        <td>ssTEM</td>
        <td>5x5x5</td>
        <td>4x4x40</td>
        <td></td>
        <td><a href="https://cremi.org/data/">
        CREMI</a></td>
        <td></td>
        <td>MICCAI Challenge on
        Circuit Reconstruction from Electron Microscopy Images</td>
    </tr>
    <tr>
        <td>VNC</td>
        <td>drosophila</td>
        <td>ventral nerve cord</td>
        <td>ssTEM</td>
        <td>4.7x4.7x1</td>
        <td>4.6x4.6x45</td>
        <td></td>
        <td><a href="https://github.com/unidesigner/groundtruth-drosophila-vnc">github</a></td>
        <td>Gerhard <i>et al.</i>, <a href="https://github.com/WillieBigHead/awesome-em-datasets#2013">2013</a></td>
        <td></td>
    </tr>
    <tr>
        <td>SegEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td> <i>et al.</i>, <a href="https://github.com/WillieBigHead/awesome-em-datasets#2015">2015</a></td>
        <td></td>
    </tr>
    <tr>
        <td>FIB-25 (training)</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>https://github.com/janelia-flyem/neuroproof_examples</td>
        <td> <i>et al.</i>, <a href="https://github.com/WillieBigHead/awesome-em-datasets#2013">2013</a></td>
        <td></td>
    </tr>
    <tr>
        <td>MICRONS (training from 3 stacks)</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td> <i>et al.</i>, <a href="https://github.com/WillieBigHead/awesome-em-datasets#2013">2013</a></td>
        <td></td>
    </tr>
</table>

### Large-scale Datasets (size from ~100<i>μm<sup>3</sup></i> to ~1<i>mm<sup>3</sup></i>)

<table>
    <tr>
        <th>Name<br><i>for short</i></th>
        <th>Species</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sample&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Microscopy&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>Size<br><i>μm<sup>3</sup></i></th>
        <th>Resolution<br><i>nm<sup>3</sup></i></th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Number&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>Link</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Reference&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Note&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
    </tr>
    <tr>
        <td rowspan="2">AxonEM</td>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>ssTEM</td>
        <td rowspan="2">30x30x30</td>
        <td>7x7x40</td>
        <td rowspan="2">18,000 axons</td>
        <td rowspan="2"><a href="https://axonem.grand-challenge.org/">grand-challenge</a></td>
        <td rowspan="2">Wei <i>et al.</i>, <a href="https://github.com/JackieZhai/awesome-em-datasets#2021">2021</a></td>
        <td rowspan="2">subsets of MICrONS and H01</td>
    </tr>
    <tr>
        <td>human</td>
        <td>temporal cortex</td>
        <td>ATUM-mSEM</td>
        <td>8x8x30</td>
    </tr>
    <tr>
        <td>H01</td>
        <td>human</td>
        <td>temporal lobe</td>
        <td>ATUM-mSEM</td>
        <td>2,000x3,000x175</td>
        <td>4x4x30</td>
        <td>50,000 cells <br> 133,700,000 synapses</td>
        <td><a href="https://h01-release.storage.googleapis.com/landing.html">google</a></td>
        <td>Shapson-Coe <i>et al.</i>, <a href="https://github.com/JackieZhai/awesome-em-datasets#2021">2021</a></td>
        <td></td>
    </tr>
    <tr>
        <td>J0126</td>
        <td>finch</td>
        <td>area X</td>
        <td>SBF-SEM</td>
        <td>96x98x114</td>
        <td>9x9x20</td>
        <td>33 blocks<br>12+50 skels</td>
        <td><a href="https://storage.googleapis.com/j0126-nature-methods-data/GgwKmcKgrcoNxJccKuGIzRnQqfit9hnfK1ctZzNbnuU/rawdata_realigned">cloudvolume-raw</a><br><a href="https://storage.googleapis.com/j0126-nature-methods-data/GgwKmcKgrcoNxJccKuGIzRnQqfit9hnfK1ctZzNbnuU/ffn_segmentation">cloudvolume-seg</a>
        </td>
        <td>Januszewski <i>et al.</i>, <a href="https://github.com/JackieZhai/awesome-em-datasets#2018">2018</a></td>
        <td>testing for FFN</td>
    </tr>
    <tr>
        <td>Kasthuri</td>
        <td>mouse</td>
        <td>neocortex</td>
        <td>ATUM-SEM</td>
        <td>40x40x50</td>
        <td>3x3x30</td>
        <td>1,700 synapses</td>
        <td><a href="https://lichtman.rc.fas.harvard.edu/vast/">vast</a></td>
        <td>Kasthuri <i>et al.</i>, <a href="https://github.com/JackieZhai/awesome-em-datasets#2015">2015</a></td>
        <td>superset of SNEMI</td>
    </tr>
    <tr>
        <td>MICrONS Cortical mm<sup>3</sup></td>
        <td>mouse</td>
        <td>primary visual cortex and three higher visual areas</td>
        <td>autoTEM</td>
        <td>1,300x870x820</td>
        <td>4x4x40</td>
        <td>200,000 cells<br>524,000,000 synapses</td>
        <td><a href="https://www.microns-explorer.org/cortical-mm3">microns</a><br><a href="https://zenodo.org/record/5760218#.Yrq7y6hBxPY">zenodo</a><br><a href="https://bossdb.org/project/microns-minnie">bossdb</a></td>
        <td>MICrONS Consortium <i>et al.</i>, <a href="https://github.com/JackieZhai/awesome-em-datasets#2021">2021</a></td>
        <td></td>
    </tr>
    <tr>
        <td>MICrONS Layer 2/3</td>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>ssTEM</td>
        <td>250x140x90</td>
        <td>3.58x3.58x40</td>
        <td>451 neurons (417 PyCs)<br>169 non-neuronal cells</td>
        <td><a href="https://www.microns-explorer.org/phase1">microns</a></td>
        <td>Turner <i>et al.</i>, <a href="https://github.com/JackieZhai/awesome-em-datasets#2022">2022</a></td>
        <td>pilot dataset of MICrONS Cortical mm<sup>3</sup></td>
    </tr>
    <tr>
        <td>ISBI</td>
        <td>drosophila</td>
        <td>ventral nerve line</td>
        <td>ssTEM</td>
        <td>2x2x1.5</td>
        <td>4x4x50</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Segmentation of neuronal structures in EM stacks</td>
    </tr>
    <tr>
        <td>SNEMI3D</td>
        <td>mouse</td>
        <td>cortex</td>
        <td>ATUM-SEM</td>
        <td>6x6x3</td>
        <td>6x6x30</td>
        <td></td>
        <td></td>
        <td></td>
        <td>SNEMI3D: 3D Segmentation of neurites in EM images</td>
    </tr>
    <tr>
        <td>CREMI</td>
        <td>drosophila</td>
        <td>melanogaster brain</td>
        <td>ssTEM</td>
        <td>5x5x5</td>
        <td>4x4x40</td>
        <td></td>
        <td><a href="https://cremi.org/data/">
        CREMI</a></td>
        <td></td>
        <td>MICCAI Challenge on
        Circuit Reconstruction from Electron Microscopy Images</td>
    </tr>
    <tr>
        <td>Images of mouse piriform cortex</td>
        <td>mouse</td>
        <td>piriform cortex</td>
        <td>ssTEM</td>
        <td>3.5x3.5x6.8</td>
        <td>7x7x40</td>
        <td></td>
        <td></td>
        <td>Kisuk Lee <i>et al.</i>, <a href="https://github.com/WillieBigHead/awesome-em-datasets#2015">2015</a></td>
        <td></td>
    </tr>
    <tr>
        <td>VNC</td>
        <td>drosophila</td>
        <td>ventral nerve cord</td>
        <td>ssTEM</td>
        <td>4.7x4.7x1</td>
        <td>4.6x4.6x45</td>
        <td></td>
        <td><a href="https://github.com/unidesigner/groundtruth-drosophila-vnc">github</a></td>
        <td>Gerhard <i>et al.</i>, <a href="https://github.com/WillieBigHead/awesome-em-datasets#2013">2013</a></td>
        <td></td>
    </tr>
</table>

### Human Datasets

@ Xinghui Zhao


## Ground Truth


<table>
    <tr>
        <th>Name<br><i>for short</i></th>
        <th>Size<br><i>μm<sup>3</sup></i></th>
        <th>Resolution<br><i>nm<sup>3</sup></i></th>
        <th>GT Size<br><i>μm<sup>3</sup></i></th>
        <th>GT Resolution<br><i>nm<sup>3</sup></i></th>
        <th>GT Size<br><i>voxel</i></th>
        <th>Link</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Note&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
    </tr>
    <tr>
        <td rowspan="2">AxonEM</td>
        <td rowspan="2">30x30x30</td>
        <td>7x7x40</td>
        <td rowspan="2"></td>
        <td>7x7x40</td>
        <td rowspan="2"></td>
        <td rowspan="2"><a href="https://axonem.grand-challenge.org/">grand-challenge</a></td>
        <td rowspan="2">subsets of MICrONS and H01</td>
    </tr>
    <tr>
        <td>8x8x30</td>
        <td>8x8x30</td>
    </tr>
    <tr>
        <td>H01</td>
        <td>2,000x3,000x175</td>
        <td>4x4x30</td>
        <td></td>
        <td>8x8x30</td>
        <td></td>
        <td><a href="https://h01-release.storage.googleapis.com/landing.html">google</a></td>
        <td></td>
    </tr>
</table>


## Elaborate Review

* Kornfeld <i>and</i> Denk. [Progress and Remaining Challenges in High-throughput Volume Electron Microscopy](https://doi.org/10.1016/j.conb.2018.04.030). 2018
* Kievits <i>et al.</i> [How Innovations in Methodology Offer New Prospects for Volume Electron Microscopy](https://doi.org/10.1111/jmi.13134). 2022
* Beyer <i>et al.</i> [A Survey of Visualization and Analysis in High-Resolution Connectomics](https://doi.org/10.1111/cgf.14574). 2022


## Open-access Resource

* [Open Connectome Project](https://neurodata.io/project/ocp/)
* [BossDB](https://bossdb.org/projects)
* [webKnossos](https://webknossos.org/publications)
* [Neuroglancer](https://github.com/google/neuroglancer)
* [Local Shape Descriptors](https://github.com/funkelab/lsd)
* [PyTorch Connectomics](https://connectomics.readthedocs.io/en/latest/tutorials/neuron.html)
* [EMPIAR](https://www.ebi.ac.uk/empiar/)
* [Zenodo](https://zenodo.org/)


## Related Work

* [connectomics-vis-survey.github.io](https://connectomics-vis-survey.github.io/)


## Related Group

* **Lichtman** Lab, Department of Molecular and Cellular Biology, Center for Brain Science, Harvard University
* **Seung** Lab, Computer Science Department, Princeton Neuroscience Institute
    * Futures
* **Helmstaedter** Lab, Department of Connectomics, Max Planck Institute for Brain Research
* **Pfister** Lab, Visual Computing Group, School of Engineering and Applied Sciences, Harvard University
* **Funke** Lab, Janelia Research Campus, Howard Hughes Medical Institute
* **Lee** Lab, Boston Children's Hospital, Harvard Medical School


## Contribution

* [Hao Zhai](https://github.com/JackieZhai)
* [Liuyun Jiang](https://github.com/WillieBigHead)
* Xinghui Zhao
* [Yanchao Zhang](https://github.com/Cristand)
* [Jinyue Guo](https://github.com/fenglingbai)

Please [**contribute**](https://github.com/JackieZhai/awesome-em-datasets/pulls) <sup>Pull Request & Issue</sup> if you think a new dataset or a relevant paper is missing.

Let's enjoy the beauty of EM data and the awesome micro-connectomes!
