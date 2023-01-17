# Awesome EM Datasets

[![Awesome](https://awesome.re/badge.svg)](https://github.com/topics/awesome)
[![Commit](https://img.shields.io/github/last-commit/JackieZhai/awesome-em-datasets)](https://github.com/JackieZhai/awesome-em-datasets/commits)
[![RepoSize](https://img.shields.io/github/repo-size/JackieZhai/awesome-em-datasets)](https://github.com/JackieZhai/awesome-em-datasets/archive/refs/heads/master.zip)

## Contents

* [Overview](https://github.com/JackieZhai/awesome-em-datasets#overview)
* [Species](https://github.com/JackieZhai/awesome-em-datasets#species)
* [Microscopy](https://github.com/JackieZhai/awesome-em-datasets#microscopy)
* [Size and Resolution](https://github.com/JackieZhai/awesome-em-datasets#size-and-resolution)
* [Reference](https://github.com/JackieZhai/awesome-em-datasets#reference)
* [Related Work](https://github.com/JackieZhai/awesome-em-datasets#related-work)
* [Acknowledgment](https://github.com/JackieZhai/awesome-em-datasets#acknowledgement)
* [Contribution](https://github.com/JackieZhai/awesome-em-datasets#contribution)


## Overview

<table>
    <tr>
        <th>Name<br>$\textit{for short}$</th>
        <th>Species</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sample&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Microscopy&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>Size<br>$\mu m^{3}$</th>
        <th>Resolution<br>$nm^{3}$</th>
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
        <td rowspan="2">$30\times 30\times 30$</td>
        <td>$7\times 7\times 40$</td>
        <td rowspan="2">18,000 axons</td>
        <td rowspan="2"><a href="https://axonem.grand-challenge.org/">grand-challenge</a></td>
        <td rowspan="2">Wei $\textit{et al}$., <a href="https://github.com/JackieZhai/awesome-em-datasets#2021">2021</a></td>
        <td rowspan="2">subsets of MICrONS and H01</td>
    </tr>
    <tr>
        <td>human</td>
        <td>temporal cortex</td>
        <td>ATUM-mSEM</td>
        <td>$8\times 8\times 30$</td>
    </tr>
    <tr>
        <td>H01</td>
        <td>human</td>
        <td>temporal lobe</td>
        <td>ATUM-mSEM</td>
        <td>$2,000\times 3,000\times 175$</td>
        <td>$4\times 4\times 30$</td>
        <td>50,000 cells <br> 133,700,000 synapses</td>
        <td><a href="https://h01-release.storage.googleapis.com/landing.html">google</a></td>
        <td>Shapson-Coe $\textit{et al}$., <a href="https://github.com/JackieZhai/awesome-em-datasets#2021">2021</a></td>
        <td></td>
    </tr>
    <tr>
        <td>J0126</td>
        <td>finch</td>
        <td>area X</td>
        <td>SBF-SEM</td>
        <td>$96\times 98\times 114$</td>
        <td>$9\times 9\times 20$</td>
        <td>33 blocks<br>12+50 skels</td>
        <td><a href="https://storage.googleapis.com/j0126-nature-methods-data/GgwKmcKgrcoNxJccKuGIzRnQqfit9hnfK1ctZzNbnuU/rawdata_realigned">cloudvolume-raw</a><br><a href="https://storage.googleapis.com/j0126-nature-methods-data/GgwKmcKgrcoNxJccKuGIzRnQqfit9hnfK1ctZzNbnuU/ffn_segmentation">cloudvolume-seg</a>
        </td>
        <td>Januszewski $\textit{et al}$., <a href="https://github.com/JackieZhai/awesome-em-datasets#2018">2018</a></td>
        <td>testing for FFN</td>
    </tr>
    <tr>
        <td>Kasthuri</td>
        <td>mouse</td>
        <td>neocortex</td>
        <td>ATUM-SEM</td>
        <td>$40\times 40\times 50$</td>
        <td>$3\times 3\times 30$</td>
        <td>1,700 synapses</td>
        <td><a href="https://lichtman.rc.fas.harvard.edu/vast/">vast</a></td>
        <td>Kasthuri $\textit{et al}$., <a href="https://github.com/JackieZhai/awesome-em-datasets#2015">2015</a></td>
        <td>superset of SNEMI</td>
    </tr>
    <tr>
        <td>MICrONS Cortical $mm^3$</td>
        <td>mouse</td>
        <td>primary visual cortex and three higher visual areas</td>
        <td>autoTEM</td>
        <td>$1,300\times 870\times 820$</td>
        <td>$4\times 4\times 40$</td>
        <td>200,000 cells<br>524,000,000 synapses</td>
        <td><a href="https://www.microns-explorer.org/cortical-mm3">microns</a><br><a href="https://zenodo.org/record/5760218#.Yrq7y6hBxPY">zenodo</a><br><a href="https://bossdb.org/project/microns-minnie">bossdb</a></td>
        <td>MICrONS Consortium $\textit{et al}$., <a href="https://github.com/JackieZhai/awesome-em-datasets#2021">2021</a></td>
        <td></td>
    </tr>
    <tr>
        <td>MICrONS Layer 2/3</td>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>ssTEM</td>
        <td>$250\times 140\times 90$</td>
        <td>$3.58\times 3.58\times 40$</td>
        <td>451 neurons (417 PyCs)<br>169 non-neuronal cells</td>
        <td><a href="https://www.microns-explorer.org/phase1">microns</a></td>
        <td>Turner $\textit{et al}$., <a href="https://github.com/JackieZhai/awesome-em-datasets#2022">2022</a></td>
        <td>pilot dataset of MICrONS Cortical $mm^3$</td>
    </tr>
    <tr>
        <td>ISBI</td>
        <td>drosophila</td>
        <td>ventral nerve line</td>
        <td>ssTEM</td>
        <td>$2\times 2\times 1.5$</td>
        <td>$4\times 4\times 50$</td>
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
        <td>$6\times 6\times 3$</td>
        <td>$6\times 6\times 30$</td>
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
        <td>$5\times 5\times 5$</td>
        <td>$4\times 4\times 40$</td>
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
        <td>$3.5\times 3.5\times 6.8$</td>
        <td>$7\times 7\times 40$</td>
        <td></td>
        <td></td>
        <td>Kisuk Lee $\textit{et al}$., <a href="https://github.com/WillieBigHead/awesome-em-datasets#2015">2015</a></td>
        <td></td>
    </tr>
    <tr>
        <td>VNC</td>
        <td>drosophila</td>
        <td>ventral nerve cord</td>
        <td>ssTEM</td>
        <td>$4.7\times 4.7\times 1$</td>
        <td>$4.6\times 4.6\times 45$</td>
        <td></td>
        <td><a href="https://github.com/unidesigner/groundtruth-drosophila-vnc">github</a></td>
        <td>Gerhard $\textit{et al}$., <a href="https://github.com/WillieBigHead/awesome-em-datasets#2013">2013</a></td>
        <td></td>
    </tr>
</table>


## Elaborate Review

* Kornfeld $\textit{and}$ Denk. [Progress and Remaining Challenges in High-throughput Volume Electron Microscopy](https://doi.org/10.1016/j.conb.2018.04.030). 2018
* Kievits $\textit{et al}$. [How Innovations in Methodology Offer New Prospects for Volume Electron Microscopy](https://doi.org/10.1111/jmi.13134). 2022
* Beyer $\textit{et al}$. [A Survey of Visualization and Analysis in High-Resolution Connectomics](https://doi.org/10.1111/cgf.14574). 2022


## Open-access Resource

* [Open Connectome Project](https://neurodata.io/project/ocp/)
* [webKnossos](https://webknossos.org/publications)
* [NeuroMorpho.Org](https://neuromorpho.org/index.jsp)
* [EMPIAR](https://www.ebi.ac.uk/empiar/)


## Related Work

* [connectomics-vis-survey.github.io](https://connectomics-vis-survey.github.io/)


## Group

* **Lichtman** Lab, Department of Molecular and Cellular Biology, Center for Brain Science, Harvard University
* **Seung** Lab, Computer Science Department, Princeton Neuroscience Institute
* **Helmstaedter** Lab, Department of Connectomics, Max Planck Institute for Brain Research
* **Pfister** Lab, Visual Computing Group, School of Engineering and Applied Sciences, Harvard University
* **Funke** Lab, Janelia Research Campus, Howard Hughes Medical Institute


## Contribution

* [Hao Zhai](https://github.com/JackieZhai)

Please [**contribute**](https://github.com/JackieZhai/awesome-em-datasets/pulls) if you think a new dataset or a relevant paper is missing.

Let's enjoy the beauty of EM data and micro-connectomes!
