# Museum of vEM Datasets

*Raw and reconstructed volume EM datasets, grouped by organism and listed newest first.* &nbsp;[&larr; back to the list](README.md) · [primer](BACKGROUND.md) · [references](REFERENCE.md)

**How to read the tables.** *Size* is the imaged volume in μm (x&times;y&times;z) unless stated otherwise; *Resolution* is the voxel size in nm (x&times;y&times;z); *Number* says what was reconstructed or annotated; *Reference* points to the publication year in [REFERENCE.md](REFERENCE.md). Empty cells are unknown rather than zero. Microscopy abbreviations (SBEM, FIB-SEM, ATUM-SEM, mSEM, ssSEM, ssTEM, autoTEM, ssEM, CLEM) are explained in the [primer](BACKGROUND.md#imaging-techniques).

## Contents

* [Benchmark Cubes](#benchmark-cubes) <sup>11</sup>
* [Nematodes](#nematodes) <sup>7</sup>
* [Insects](#insects) <sup>14</sup>
* [Other Invertebrates and Chordates](#other-invertebrates-and-chordates) <sup>8</sup>
* [Fish](#fish) <sup>10</sup>
* [Birds](#birds) <sup>3</sup>
* [Mouse and Other Rodents](#mouse-and-other-rodents) <sup>18</sup>
* [Primates and Human](#primates-and-human) <sup>9</sup>
* [Cell Biology and Non-neural Tissue](#cell-biology-and-non-neural-tissue) <sup>2</sup>


## Benchmark Cubes

Small, densely labeled volumes (≲ 30 μm per side) that defined the segmentation and detection benchmarks; download details are in the [Accessible Ground Truth](README.md#accessible-ground-truth) table.

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
        <td>WASPSYN</td>
        <td>micro-wasp (<i>Megaphragma viggianii</i>)</td>
        <td>brain (14 regions from 3 brains)</td>
        <td>FIB-SEM</td>
        <td>14x ~3.3x3.3x3.3</td>
        <td>8x8x8</td>
        <td>pre-/postsynaptic points</td>
        <td><a href="https://codalab.lisn.upsaclay.fr/competitions/9169">codalab</a></td>
        <td>Li <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>ISBI 2023 challenge on domain-adaptive synapse detection</td>
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
        <td rowspan="2">Wei <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td rowspan="2">subsets of MICrONS and H01</td>
    </tr>
    <tr>
        <td>human</td>
        <td>temporal cortex</td>
        <td>ATUM-mSEM</td>
        <td>8x8x30</td>
    </tr>
    <tr>
        <td rowspan="2">MitoEM</td>
        <td>rat</td>
        <td>cortex</td>
        <td>mSEM</td>
        <td rowspan="2">2x 30x30x30</td>
        <td>8x8x30</td>
        <td rowspan="2">~40,000 mitochondria</td>
        <td rowspan="2"><a href="https://mitoem.grand-challenge.org/">grand-challenge</a></td>
        <td rowspan="2">Wei <i>et al.</i>, <a href="REFERENCE.md#2020">2020</a></td>
        <td rowspan="2">mitochondria instance segmentation (ISBI 2021 challenge); harder successor MitoEM 2.0 (Liu <i>et al.</i> 2025)</td>
    </tr>
    <tr>
        <td>human</td>
        <td>frontal cortex layer II</td>
        <td>ATUM-mSEM</td>
        <td>8x8x30</td>
    </tr>
    <tr>
        <td>CREMI A/B/C</td>
        <td>drosophila</td>
        <td>adult brain (from FAFB)</td>
        <td>ssTEM</td>
        <td>3x 5x5x5</td>
        <td>4x4x40</td>
        <td></td>
        <td><a href="https://cremi.org/data/">cremi</a></td>
        <td>Zheng <i>et al.</i>, <a href="REFERENCE.md#2018">2018</a></td>
        <td>MICCAI 2016 challenge: neurons, synaptic clefts and synaptic partners</td>
    </tr>
    <tr>
        <td>SegEM</td>
        <td>mouse</td>
        <td>somatosensory cortex / retina</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td>279 volume-labeled cells</td>
        <td></td>
        <td>Berning <i>et al.</i>, <a href="REFERENCE.md#2015">2015</a></td>
        <td>training data for SegEM segmentation</td>
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
        <td>Kisuk Lee, <a href="REFERENCE.md#2015">2015</a></td>
        <td>2D-3D boundary detection (recursive training)</td>
    </tr>
    <tr>
        <td>FIB-25 (training)</td>
        <td>drosophila</td>
        <td>optic medulla</td>
        <td>FIB-SEM</td>
        <td></td>
        <td>8x8x8</td>
        <td></td>
        <td><a href="https://github.com/janelia-flyem/neuroproof_examples">neuroproof</a></td>
        <td>Takemura <i>et al.</i>, <a href="REFERENCE.md#2015">2015</a></td>
        <td>dense GT; also FFN training data</td>
    </tr>
    <tr>
        <td>AC3/AC4</td>
        <td>mouse</td>
        <td>neocortex</td>
        <td>ATUM-SEM</td>
        <td>6x6x3</td>
        <td>6x6x30</td>
        <td></td>
        <td></td>
        <td>Kasthuri <i>et al.</i>, <a href="REFERENCE.md#2015">2015</a></td>
        <td>subsets of Kasthuri15; different membrane labeling at myelin</td>
    </tr>
    <tr>
        <td>SNEMI3D</td>
        <td>mouse</td>
        <td>neocortex</td>
        <td>ATUM-SEM</td>
        <td>6x6x3</td>
        <td>6x6x30</td>
        <td></td>
        <td><a href="https://snemi3d.grand-challenge.org/">grand-challenge</a></td>
        <td>Kasthuri <i>et al.</i>, <a href="REFERENCE.md#2015">2015</a></td>
        <td>3D segmentation of neurites (ISBI 2013); subset of Kasthuri15</td>
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
        <td>Gerhard <i>et al.</i>, <a href="REFERENCE.md#2013">2013</a></td>
        <td>segmented anisotropic ssTEM stack</td>
    </tr>
    <tr>
        <td>ISBI 2012</td>
        <td>drosophila</td>
        <td>ventral nerve cord</td>
        <td>ssTEM</td>
        <td>2x2x1.5</td>
        <td>4x4x50</td>
        <td></td>
        <td><a href="https://imagej.net/events/isbi-2012-segmentation-challenge">imagej</a></td>
        <td></td>
        <td>2D segmentation of neuronal structures (membranes)</td>
    </tr>
</table>


## Nematodes

<i>C. elegans</i> and its relatives: the first complete connectomes and the reference for comparative and developmental connectomics.

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
        <td>Pristionchus Heads</td>
        <td><i>P. pacificus</i></td>
        <td>head incl. nerve ring (2 adult hermaphrodites)</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Cook <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>all neurons from nose to retrovesicular ganglion; comparative connectomics against <i>C. elegans</i></td>
    </tr>
    <tr>
        <td>Dauer</td>
        <td>c. elegans</td>
        <td>dauer larva</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://bossdb.org/project/yim_choe_bae2024">bossdb</a><br><a href="http://openworm.org/ConnectomeToolbox/Yim_2024/">openworm</a></td>
        <td>Yim <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>connectome of the stress-resistant dauer stage; developmental plasticity</td>
    </tr>
    <tr>
        <td>Witvliet2020</td>
        <td>c. elegans</td>
        <td>brain (nerve ring), birth to adulthood</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td>8 connectomes</td>
        <td><a href="https://bossdb.org/project/witvliet2020">bossdb</a><br><a href="https://nemanode.org/">nemanode</a></td>
        <td>Witvliet <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td>connectomes across development</td>
    </tr>
    <tr>
        <td>Nerve Ring Volumetric</td>
        <td>c. elegans</td>
        <td>nerve ring (L4 and adult, legacy MRC series)</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://zenodo.org/records/4763083">zenodo</a><br><a href="https://github.com/cabrittin/elegansbrainmap">github</a></td>
        <td>Brittin <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td>volumetric re-segmentation: contactome + chemical and gap-junction connectomes</td>
    </tr>
    <tr>
        <td>Pristionchus Amphid</td>
        <td><i>P. pacificus</i></td>
        <td>amphid sensory neurons and partners</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Hong <i>et al.</i>, <a href="REFERENCE.md#2019">2019</a></td>
        <td>sensory circuit evolution in two divergent nematodes</td>
    </tr>
    <tr>
        <td>WormWiring</td>
        <td>c. elegans</td>
        <td>whole animal, both sexes</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td>302 (hermaphrodite)<br>385 (male) neurons</td>
        <td><a href="https://wormwiring.org/">wormwiring</a></td>
        <td>Cook <i>et al.</i>, <a href="REFERENCE.md#2019">2019</a></td>
        <td>whole-animal connectomes of both sexes</td>
    </tr>
    <tr>
        <td>MoW (White1986)</td>
        <td>c. elegans</td>
        <td>whole nervous system</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td>302 neurons</td>
        <td><a href="https://bossdb.org/project/white1986">bossdb</a><br><a href="https://www.wormatlas.org">wormatlas</a></td>
        <td>White <i>et al.</i>, <a href="REFERENCE.md#1986">1986</a></td>
        <td>the first complete connectome (&ldquo;Mind of a Worm&rdquo;)</td>
    </tr>
</table>


## Insects

<i>Drosophila</i> now has whole-brain, whole-nerve-cord and whole-CNS connectomes of several individuals; other insects are catching up.

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
        <td>Male CNS</td>
        <td>drosophila</td>
        <td>whole central nervous system (adult male, brain + VNC)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td>8x8x8</td>
        <td>~166,700 neurons<br>~11,700 cell types</td>
        <td><a href="https://male-cns.janelia.org/">male-cns</a><br><a href="https://neuprint.janelia.org/">neuprint</a></td>
        <td>Berg <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a>, <a href="REFERENCE.md#2026">2026</a></td>
        <td>first complete adult CNS connectome; sexual dimorphism; neuPrint <code>male-cns:v1.0</code> (June 2026); <i>Cell</i> 2026</td>
    </tr>
    <tr>
        <td>BANC</td>
        <td>drosophila</td>
        <td>brain-and-nerve-cord (adult female)</td>
        <td>ssTEM (GridTape)</td>
        <td>7,010 sections</td>
        <td>4x4x45</td>
        <td></td>
        <td><a href="https://bossdb.org/project/bates_phelps_kim_yang2025">bossdb</a><br><a href="https://codex.flywire.ai/">flywire-codex</a><br><a href="https://github.com/htem/BANC-project">github</a></td>
        <td>Bates <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a>, <a href="REFERENCE.md#2026">2026</a></td>
        <td>first connectome spanning brain and ventral nerve cord in one animal; <i>Nature</i> 2026; BossDB data DOI <a href="https://doi.org/10.60533/boss-2025-941r">10.60533/boss-2025-941r</a></td>
    </tr>
    <tr>
        <td>Aedes Antennal Lobe</td>
        <td>mosquito (<i>Aedes aegypti</i>)</td>
        <td>antennal lobes (adult female)</td>
        <td>ssTEM (GridTape)</td>
        <td></td>
        <td>4x4x40</td>
        <td></td>
        <td><a href="https://bossdb.org/projects">bossdb</a></td>
        <td>Bao <i>et al.</i>, <a href="REFERENCE.md#2026">2026</a></td>
        <td>first synapse-resolution circuit of a disease-vector mosquito; CO<sub>2</sub>-sensing olfactory neurons</td>
    </tr>
    <tr>
        <td>Comparative Central Complex</td>
        <td>6 insect species</td>
        <td>central complex (sweat bee, army ant, locust, mantis, cockroach, earwig)</td>
        <td>SBEM</td>
        <td></td>
        <td>8&ndash;12 (synaptic tiles)<br>40&ndash;50 (overview)</td>
        <td></td>
        <td></td>
        <td>Gillet <i>et al.</i>, <a href="REFERENCE.md#2026">2026</a></td>
        <td>multi-resolution pipeline for comparative insect connectomics; head-direction circuits in six species (preprint)</td>
    </tr>
    <tr>
        <td>Optic Lobe</td>
        <td>drosophila</td>
        <td>right optic lobe (adult male)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td>8x8x8</td>
        <td>~53,000 neurons<br>727 cell types</td>
        <td><a href="https://www.janelia.org/project-team/flyem/optic-lobe">janelia</a><br><a href="https://neuprint.janelia.org/">neuprint</a><br><a href="https://github.com/reiserlab/male-drosophila-visual-system-connectome">cell-type-explorer</a></td>
        <td>Nern <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>complete, exhaustively cell-typed visual system; same sample as Male CNS</td>
    </tr>
    <tr>
        <td>Megaphragma Eye + Lamina</td>
        <td>micro-wasp (<i>Megaphragma viggianii</i>)</td>
        <td>compound eye and lamina (adult)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td>8 (in-plane)</td>
        <td></td>
        <td><a href="https://github.com/nicholasjchua/megaphragma-lamina">github</a></td>
        <td>Chua <i>et al.</i>, <a href="REFERENCE.md#2023">2023</a>; Makarova <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>complete early visual system of one of the smallest insects</td>
    </tr>
    <tr>
        <td>MANC</td>
        <td>drosophila</td>
        <td>whole ventral nerve cord (adult male)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td>8x8x8</td>
        <td>~23,000 neurons<br>~10,000,000 presynaptic sites</td>
        <td><a href="https://www.janelia.org/project-team/flyem/manc-connectome">janelia</a><br><a href="https://neuprint.janelia.org/">neuprint</a></td>
        <td>Takemura <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a>; Marin <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a>; Cheong <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>first complete adult nerve-cord connectome (neuPrint <code>manc:v1.2.1</code>)</td>
    </tr>
    <tr>
        <td>FANC</td>
        <td>drosophila</td>
        <td>whole ventral nerve cord (adult female)</td>
        <td>ssTEM (GridTape)</td>
        <td></td>
        <td>4.3x4.3x45</td>
        <td>~14,600 neuronal cell bodies<br>~45,000,000 synapses</td>
        <td><a href="https://bossdb.org/project/phelps_hildebrand_graham2021">bossdb</a><br><a href="https://github.com/htem/FANC_auto_recon">github</a></td>
        <td>Phelps <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a>; Azevedo <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>motor control circuits; automated reconstruction + CAVE proofreading in Azevedo <i>et al.</i> 2024</td>
    </tr>
    <tr>
        <td>FAFB (FlyWire)</td>
        <td>drosophila</td>
        <td>whole adult female brain</td>
        <td>ssTEM (TEMCA2)</td>
        <td>~750x350x250</td>
        <td>4x4x40</td>
        <td>139,255 neurons<br>54,500,000 synapses</td>
        <td><a href="https://codex.flywire.ai/">flywire-codex</a><br><a href="https://zenodo.org/records/10676866">zenodo-v783</a><br><a href="https://fafb.catmaid.virtualflybrain.org/">catmaid</a><br><a href="https://bossdb.org/project/flywire2020">bossdb</a></td>
        <td>Zheng <i>et al.</i>, <a href="REFERENCE.md#2018">2018</a>; Dorkenwald <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>first complete adult brain volume; FlyWire = proofread whole-brain connectome (v783); cell types in Schlegel <i>et al.</i> 2024, optic lobe in Matsliah <i>et al.</i> 2024; neurotransmitter predictions in Eckstein <i>et al.</i> 2024</td>
    </tr>
    <tr>
        <td>L1EM (larval CNS)</td>
        <td>drosophila</td>
        <td>whole central nervous system (L1 larva)</td>
        <td>ssTEM</td>
        <td>~250 per side (brain)</td>
        <td>3.8x3.8x50</td>
        <td>3,016 neurons<br>548,000 synapses</td>
        <td><a href="https://bossdb.org/project/ohyama2015">bossdb</a><br><a href="https://l1em.catmaid.virtualflybrain.org/">catmaid</a></td>
        <td>Ohyama <i>et al.</i>, <a href="REFERENCE.md#2015">2015</a>; Winding <i>et al.</i>, <a href="REFERENCE.md#2023">2023</a></td>
        <td>first whole-brain connectome of an insect; mushroom body in Eichler <i>et al.</i> 2017</td>
    </tr>
    <tr>
        <td>Bumblebee Central Complex</td>
        <td>bumblebee</td>
        <td>central complex</td>
        <td>SBEM</td>
        <td></td>
        <td>24 (nodulus) to ~100 (overview)</td>
        <td>&gt;1,300 neuron skeletons</td>
        <td><a href="https://www.insectbraindb.org/app/connectomics;experiment=61;handle=EIN-0000061.1">insectbraindb</a></td>
        <td>Sayre <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td>first central-complex projectome outside <i>Drosophila</i></td>
    </tr>
    <tr>
        <td>Hemi-brain</td>
        <td>drosophila</td>
        <td>central brain (hemisphere)</td>
        <td>FIB-SEM</td>
        <td>~250x250x250</td>
        <td>8x8x8</td>
        <td>~25,000 neurons<br>~20,000,000 synapses</td>
        <td><a href="https://neuprint.janelia.org/">neuprint</a></td>
        <td>Scheffer <i>et al.</i>, <a href="REFERENCE.md#2020">2020</a></td>
        <td>isotropic voxels; dense synapse prediction (neuPrint <code>hemibrain:v1.2.1</code>)</td>
    </tr>
    <tr>
        <td>Larval VNC (L1 vs. L3)</td>
        <td>drosophila</td>
        <td>abdominal nerve cord segments (L1 and L3 larvae)</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Gerhard <i>et al.</i>, <a href="REFERENCE.md#2017">2017</a></td>
        <td>comparative connectomics across larval development</td>
    </tr>
    <tr>
        <td>FIB-25</td>
        <td>drosophila</td>
        <td>optic medulla (seven columns)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td>8x8x8</td>
        <td></td>
        <td><a href="https://neuprint-examples.janelia.org/">neuprint-examples</a></td>
        <td>Takemura <i>et al.</i>, <a href="REFERENCE.md#2015">2015</a></td>
        <td>seven-column medulla connectome (neuPrint dataset <code>medulla7column</code>)</td>
    </tr>
</table>


## Other Invertebrates and Chordates

Whole-body and nerve-net reconstructions that anchor the evolution of nervous systems.

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
        <td>Ctenophore Aboral Organ</td>
        <td>comb jelly (<i>Mnemiopsis leidyi</i>)</td>
        <td>aboral organ (1-day larva)</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td>~900 cells<br>17 morphotypes</td>
        <td></td>
        <td>Ferraioli <i>et al.</i>, <a href="REFERENCE.md#2026">2026</a></td>
        <td>5 SBEM datasets; nerve net condenses around an integrative centre</td>
    </tr>
    <tr>
        <td>Ctenophore Statocyst</td>
        <td>comb jelly (<i>Mnemiopsis leidyi</i>)</td>
        <td>aboral organ (statocyst) + nerve net (5-day larva)</td>
        <td>ssSEM</td>
        <td>~60x40x30</td>
        <td>2.8x2.8x50</td>
        <td>1,011 cells</td>
        <td><a href="https://catmaid.jekelylab.ex.ac.uk">catmaid</a></td>
        <td>Jokura <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>first nerve-net connectome</td>
    </tr>
    <tr>
        <td>Hydra Nerve Net</td>
        <td><i>Hydra vulgaris</i></td>
        <td>endodermal nerve net</td>
        <td>ssEM</td>
        <td>40.5x13x60</td>
        <td>20x20x30</td>
        <td>20 neurons</td>
        <td><a href="https://doi.org/10.60533/BOSS-2025-08G4">bossdb</a></td>
        <td>Zhang <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>neurons joined by interdigitating &ldquo;handshakes&rdquo;; vesicles segmented</td>
    </tr>
    <tr>
        <td>Platynereis Whole Body</td>
        <td>annelid (<i>Platynereis dumerilii</i>)</td>
        <td>whole body (72 hpf larva)</td>
        <td>ssTEM</td>
        <td>4,845 sections of 40 nm</td>
        <td></td>
        <td>&gt;9,000 cells<br>202 neuronal cell types</td>
        <td><a href="https://catmaid.jekelylab.ex.ac.uk">catmaid</a></td>
        <td>Verasztó <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>whole-body connectome of a segmented larva</td>
    </tr>
    <tr>
        <td>Octopus Vertical Lobe</td>
        <td><i>Octopus vulgaris</i></td>
        <td>vertical lobe (memory centre)</td>
        <td>ssEM</td>
        <td>260x390x27</td>
        <td>4x4x30</td>
        <td>516 cell processes<br>13,434 postsynaptic sites</td>
        <td><a href="https://lichtman.rc.fas.harvard.edu/octopus_connectomes">lichtman-lab</a></td>
        <td>Bidel <i>et al.</i>, <a href="REFERENCE.md#2023">2023</a></td>
        <td>first cephalopod connectome; memory-acquisition network</td>
    </tr>
    <tr>
        <td>Ctenophore Nerve Net</td>
        <td>comb jelly (<i>Mnemiopsis leidyi</i>)</td>
        <td>subepithelial nerve net (hatchling)</td>
        <td>SBEM (HPF)</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Burkhardt <i>et al.</i>, <a href="REFERENCE.md#2023">2023</a></td>
        <td>syncytial nerve net without synaptic gaps between its neurons</td>
    </tr>
    <tr>
        <td>Platynereis 6 dpf</td>
        <td>annelid (<i>Platynereis dumerilii</i>)</td>
        <td>whole body (6-day larva)</td>
        <td>SBEM</td>
        <td>11,416 slices</td>
        <td></td>
        <td></td>
        <td><a href="https://www.ebi.ac.uk/empiar/EMPIAR-10365/">empiar</a></td>
        <td>Vergara <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td>all cells and nuclei segmented and registered to a gene-expression atlas (not a synaptic connectome)</td>
    </tr>
    <tr>
        <td>Ciona Larva</td>
        <td>tunicate (<i>Ciona intestinalis</i>)</td>
        <td>whole CNS (tadpole larva)</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td>177 CNS neurons<br>6,618 synapses</td>
        <td></td>
        <td>Ryan <i>et al.</i>, <a href="REFERENCE.md#2016">2016</a></td>
        <td>first chordate CNS connectome; left&ndash;right asymmetry</td>
    </tr>
</table>


## Fish

Larval zebrafish is the first vertebrate whose whole brain has been imaged and reconstructed at synaptic resolution.

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
        <td>Electrosensory Lobe</td>
        <td>mormyrid fish (<i>Gnathonemus petersii</i>)</td>
        <td>anterior electrosensory lobe (cerebellum-like)</td>
        <td>ATUM-mSEM</td>
        <td>450x450x105</td>
        <td></td>
        <td></td>
        <td><a href="https://zenodo.org/records/19892261">zenodo</a></td>
        <td>Perks <i>et al.</i>, <a href="REFERENCE.md#2026">2026</a></td>
        <td>FFN segmentation; circuit for cancelling predictable sensory input</td>
    </tr>
    <tr>
        <td>Fish Fire&amp;Wire</td>
        <td>zebrafish</td>
        <td>whole brain (larva)</td>
        <td>ssEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://www.janelia.org/fish-firewire">janelia</a></td>
        <td></td>
        <td>whole-brain light-sheet activity and EM of the same behaving fish (Janelia, Harvard, Google); draft connectome in proofreading, early snapshots on application; no paper yet</td>
    </tr>
    <tr>
        <td>Fish1</td>
        <td>zebrafish</td>
        <td>whole brain + spinal cord + ganglia (7-dpf larva)</td>
        <td></td>
        <td></td>
        <td>4x4x30</td>
        <td>~187,000 cell bodies<br>~30,000,000 synapses</td>
        <td><a href="https://fish1-release.storage.googleapis.com/index.html">fish1</a></td>
        <td>Lichtman / Engert / Google, <a href="REFERENCE.md#2025">2025</a></td>
        <td>EM + confocal LM of the same specimen; &gt;40,000 molecularly annotated neurons; CAVE community reconstruction (preprint)</td>
    </tr>
    <tr>
        <td>Fish-X</td>
        <td>zebrafish</td>
        <td>whole brain (larva)</td>
        <td>ssSEM</td>
        <td>22,901 sections</td>
        <td>4x4x33</td>
        <td>~177,000 cells<br>~25,000,000 synapses</td>
        <td></td>
        <td>ION-CAS, <a href="REFERENCE.md#2025">2025</a></td>
        <td>neuromodulatory-type-annotated whole-brain reconstruction (preprint)</td>
    </tr>
    <tr>
        <td>Hindbrain CLEM</td>
        <td>zebrafish</td>
        <td>anterior hindbrain (larva)</td>
        <td>CLEM (ssEM)</td>
        <td></td>
        <td></td>
        <td>84 functionally identified neurons<br>165 synaptic partners</td>
        <td><a href="https://zenodo.org/records/19231045">zenodo</a><br><a href="https://github.com/jboulanger91/Zebrafish_CLEM">github</a></td>
        <td>Boulanger-Weill <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>circuit motifs for evidence accumulation (preprint)</td>
    </tr>
    <tr>
        <td>Hindbrain Integrator</td>
        <td>zebrafish</td>
        <td>larval hindbrain (oculomotor integrator)</td>
        <td>ssTEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Vishwanathan <i>et al.</i>, <a href="REFERENCE.md#2017">2017</a>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>functionally identified cells (calcium imaging + EM); modular function prediction</td>
    </tr>
    <tr>
        <td>Svara2022 (mapzebrain)</td>
        <td>zebrafish</td>
        <td>whole brain (larva)</td>
        <td>SBEM</td>
        <td>~0.058 mm<sup>3</sup><br>(12.5 Tvx, ~29,000 sections)</td>
        <td>14x14x25</td>
        <td>~121,000 neurons</td>
        <td><a href="https://mapzebrain.org">mapzebrain</a></td>
        <td>Svara <i>et al.</i>, <a href="REFERENCE.md#2022">2022</a></td>
        <td>FFN segmentation + automated synapse detection; pretectal motion-processing network; community proofreading</td>
    </tr>
    <tr>
        <td>Zebrafish OB</td>
        <td>zebrafish</td>
        <td>larval olfactory bulb</td>
        <td>SBEM</td>
        <td>72x108x119</td>
        <td>9.25x9.25x25</td>
        <td>~1,000 neurons</td>
        <td><a href="https://bossdb.org/project/wanner16">bossdb</a></td>
        <td>Wanner <i>et al.</i>, <a href="REFERENCE.md#2016">2016</a>; Wanner and Friedrich, <a href="REFERENCE.md#2020">2020</a></td>
        <td>whitening of odor representations</td>
    </tr>
    <tr>
        <td>Svara2018 (spinal cord)</td>
        <td>zebrafish</td>
        <td>larval spinal cord</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Svara <i>et al.</i>, <a href="REFERENCE.md#2018">2018</a></td>
        <td>wiring specificity in speed-related motor circuits</td>
    </tr>
    <tr>
        <td>Hildebrand2017</td>
        <td>zebrafish</td>
        <td>whole brain (5.5-dpf larva)</td>
        <td>ssTEM</td>
        <td></td>
        <td>56.4x56.4x60<br>(18.8 in-plane subareas)</td>
        <td></td>
        <td><a href="https://bossdb.org/project/hildebrand2017">bossdb</a></td>
        <td>Hildebrand <i>et al.</i>, <a href="REFERENCE.md#2017">2017</a></td>
        <td>whole-brain serial-section EM; myelinated-axon projectome</td>
    </tr>
</table>


## Birds

Songbird circuits for learned vocal behavior.

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
        <td>Area X Connectome</td>
        <td>zebra finch</td>
        <td>basal ganglia (area X)</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Rother <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>songbird basal ganglia connectome (preprint); see also J0126</td>
    </tr>
    <tr>
        <td>J0126</td>
        <td>zebra finch</td>
        <td>area X</td>
        <td>SBEM</td>
        <td>96x98x114</td>
        <td>9x9x20</td>
        <td>33 blocks<br>12+50 skels</td>
        <td><a href="https://storage.googleapis.com/j0126-nature-methods-data/GgwKmcKgrcoNxJccKuGIzRnQqfit9hnfK1ctZzNbnuU/rawdata_realigned">cloudvolume-raw</a><br><a href="https://storage.googleapis.com/j0126-nature-methods-data/GgwKmcKgrcoNxJccKuGIzRnQqfit9hnfK1ctZzNbnuU/ffn_segmentation">cloudvolume-seg</a></td>
        <td>Januszewski <i>et al.</i>, <a href="REFERENCE.md#2018">2018</a></td>
        <td>testing for FFN; &ldquo;Zebrafinch&rdquo; benchmark of LSD</td>
    </tr>
    <tr>
        <td>HVC</td>
        <td>zebra finch</td>
        <td>HVC (song premotor nucleus)</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://github.com/jmrk84/HVC_paper">github</a></td>
        <td>Kornfeld <i>et al.</i>, <a href="REFERENCE.md#2017">2017</a></td>
        <td>axonal target variation in a sequence-generating network</td>
    </tr>
</table>


## Mouse and Other Rodents

From retina and barrel cortex to the cubic millimeter of visual cortex; cross-species samples are listed under Primates.

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
        <td>CA3</td>
        <td>mouse</td>
        <td>hippocampal area CA3</td>
        <td>ssTEM (GridTape)</td>
        <td>1,000x1,000x92</td>
        <td>3x3x45</td>
        <td>1,815 pyramidal + 229 inhibitory cells<br>&gt;55,000 mossy-fiber axons</td>
        <td><a href="https://github.com/seung-lab/ca3_paper">github</a></td>
        <td>Zheng <i>et al.</i>, <a href="REFERENCE.md#2026">2026</a></td>
        <td>gradient of mossy-fiber inputs and selective feedforward inhibition; data shared via the Pyr platform</td>
    </tr>
    <tr>
        <td>V1DD (V1 Deep Dive)</td>
        <td>mouse</td>
        <td>primary visual cortex, all layers</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://github.com/AllenInstitute/allen_v1dd">allen-sdk</a></td>
        <td></td>
        <td>Allen Institute functional (2-/3-photon) + EM dataset; public CAVE datastack <code>v1dd_public</code> since Aug 2025; no dataset paper yet</td>
    </tr>
    <tr>
        <td>CA1</td>
        <td>mouse</td>
        <td>hippocampal area CA1</td>
        <td></td>
        <td>1,100x921x143</td>
        <td></td>
        <td></td>
        <td><a href="https://wklink.org/7023">webknossos</a></td>
        <td>Corteze <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>large-scale hippocampal dataset (preprint); Hebbian plasticity traces across CA3, CA1 and MEC in Grasso <i>et al.</i> 2025</td>
    </tr>
    <tr>
        <td>MICrONS Cortical mm<sup>3</sup></td>
        <td>mouse</td>
        <td>primary visual cortex and three higher visual areas</td>
        <td>autoTEM</td>
        <td>1,300x870x820</td>
        <td>4x4x40</td>
        <td>200,000 cells<br>524,000,000 synapses</td>
        <td><a href="https://www.microns-explorer.org/cortical-mm3">microns</a><br><a href="https://tutorial.microns-explorer.org/">tutorial</a><br><a href="https://bossdb.org/project/microns-minnie">bossdb</a></td>
        <td>MICrONS Consortium, <a href="REFERENCE.md#2021">2021</a>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>two-photon imaging of ~75,000 neurons + EM of the same volume; CAVE datastack <code>minnie65_public</code> (v1718, Mar 2026); companion analyses in <i>Nature</i> 2025; postsynaptic census in Pedigo <i>et al.</i> 2026</td>
    </tr>
    <tr>
        <td>Barrel Column (Si150L4)</td>
        <td>mouse</td>
        <td>somatosensory cortex (S1), one barrel column, all layers</td>
        <td>mSEM</td>
        <td></td>
        <td></td>
        <td>~10<sup>4</sup> neurons</td>
        <td><a href="https://wklink.org/7122">webknossos</a></td>
        <td>Sievers <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>first complete cortical column connectome (preprint); ~1.1 PB</td>
    </tr>
    <tr>
        <td>PPC</td>
        <td>mouse</td>
        <td>posterior parietal cortex, all layers</td>
        <td>ssTEM (GridTape)</td>
        <td>~0.1 mm<sup>3</sup> (2,500 sections)</td>
        <td>4.3x4.3x40</td>
        <td></td>
        <td><a href="https://github.com/htem/PPC_inhibitoryMotifs">github</a></td>
        <td>Kuan <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>two-photon imaging during a decision task + EM; opponent-inhibition motifs</td>
    </tr>
    <tr>
        <td>Cerebellum (Nguyen)</td>
        <td>mouse</td>
        <td>cerebellar cortex</td>
        <td>ssTEM (GridTape)</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://bossdb.org/project/nguyen_thomas2022">bossdb</a></td>
        <td>Nguyen <i>et al.</i>, <a href="REFERENCE.md#2023">2023</a></td>
        <td>structured connectivity supports resilient pattern separation</td>
    </tr>
    <tr>
        <td>MICrONS Layer 2/3 (Pinky)</td>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>ssTEM</td>
        <td>250x140x90</td>
        <td>3.58x3.58x40</td>
        <td>451 neurons (417 PyCs)<br>169 non-neuronal cells</td>
        <td><a href="https://www.microns-explorer.org/phase1">microns</a><br><a href="https://bossdb.org/project/microns_pinky2021">bossdb</a></td>
        <td>Turner <i>et al.</i>, <a href="REFERENCE.md#2022">2022</a></td>
        <td>pilot dataset of MICrONS Cortical mm<sup>3</sup></td>
    </tr>
    <tr>
        <td>Cochlea</td>
        <td>mouse</td>
        <td>cochlea</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Hua <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td>neural circuitry of the peripheral auditory system</td>
    </tr>
    <tr>
        <td>Postnatal Barrel Cortex</td>
        <td>mouse</td>
        <td>barrel cortex (P5&ndash;P28)</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td>13 local connectomes</td>
        <td><a href="https://webknossos.org/publications">webknossos</a></td>
        <td>Gour <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td>postnatal connectomic development of inhibition</td>
    </tr>
    <tr>
        <td>L4dense</td>
        <td>mouse</td>
        <td>barrel cortex layer 4</td>
        <td>SBEM</td>
        <td>62x95x93</td>
        <td>11.24x11.24x28</td>
        <td>89 somata<br>6,979 axons</td>
        <td><a href="https://l4dense2019.brain.mpg.de/">l4dense</a></td>
        <td>Motta <i>et al.</i>, <a href="REFERENCE.md#2019">2019</a></td>
        <td>dense connectomic reconstruction with focused proofreading (FocusEM)</td>
    </tr>
    <tr>
        <td>e2198 (EyeWire)</td>
        <td>mouse</td>
        <td>retina</td>
        <td>SBEM</td>
        <td></td>
        <td>16.5x16.5x23</td>
        <td>396 ganglion cells</td>
        <td><a href="https://museum.eyewire.org/">eyewire-museum</a></td>
        <td>Briggman <i>et al.</i>, <a href="REFERENCE.md#2011">2011</a>; Kim <i>et al.</i>, <a href="REFERENCE.md#2014">2014</a>; Bae <i>et al.</i>, <a href="REFERENCE.md#2018">2018</a></td>
        <td>citizen-science reconstruction; direction-selectivity circuit</td>
    </tr>
    <tr>
        <td>MEC (Schmidt)</td>
        <td>mouse</td>
        <td>medial entorhinal cortex</td>
        <td>SBEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://webknossos.org/publications">webknossos</a></td>
        <td>Schmidt <i>et al.</i>, <a href="REFERENCE.md#2017">2017</a></td>
        <td>axonal synapse sorting</td>
    </tr>
    <tr>
        <td>dLGN</td>
        <td>mouse</td>
        <td>visual thalamus (dLGN)</td>
        <td>ATUM-SEM</td>
        <td>400x600x280</td>
        <td>4x4x30</td>
        <td></td>
        <td><a href="https://bossdb.org/project/morgan2020">bossdb</a></td>
        <td>Morgan <i>et al.</i>, <a href="REFERENCE.md#2016">2016</a></td>
        <td>fuzzy logic of network connectivity</td>
    </tr>
    <tr>
        <td>Lee2016</td>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>ssTEM</td>
        <td>450x450x150</td>
        <td>4x4x40</td>
        <td></td>
        <td><a href="https://bossdb.org/project/lee2016">bossdb</a></td>
        <td>Lee <i>et al.</i>, <a href="REFERENCE.md#2016">2016</a></td>
        <td>excitatory network anatomy + function</td>
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
        <td>Kasthuri <i>et al.</i>, <a href="REFERENCE.md#2015">2015</a></td>
        <td>saturated reconstruction; superset of SNEMI3D</td>
    </tr>
    <tr>
        <td>e2006</td>
        <td>mouse</td>
        <td>retina (inner plexiform layer)</td>
        <td>SBEM</td>
        <td>114x80x132</td>
        <td>16.5x16.5x25</td>
        <td>950 neurons</td>
        <td><a href="https://bossdb.org/project/helmstaedter2013">bossdb</a><br><a href="https://neuro.rzg.mpg.de/">mpi-repo</a></td>
        <td>Helmstaedter <i>et al.</i>, <a href="REFERENCE.md#2013">2013</a></td>
        <td>first dense mammalian connectome</td>
    </tr>
    <tr>
        <td>Bock2011</td>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>TEMCA</td>
        <td>450x350x52</td>
        <td>4x4x45</td>
        <td></td>
        <td><a href="https://bossdb.org/project/bock2011">bossdb</a></td>
        <td>Bock <i>et al.</i>, <a href="REFERENCE.md#2011">2011</a></td>
        <td>function (two-photon) + structure</td>
    </tr>
</table>


## Primates and Human

Surgical biopsies, brain-bank tissue and non-human primates.

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
        <td>Prefrontal Cortex (postmortem)</td>
        <td>human</td>
        <td>dorsolateral prefrontal cortex, layer 3 (brain bank)</td>
        <td>FIB-SEM</td>
        <td>2,630 μm<sup>3</sup> in total</td>
        <td>5x5x5</td>
        <td></td>
        <td></td>
        <td>Glausier <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>synaptic and mitochondrial nanoarchitecture in tissue stored for ~8 years</td>
    </tr>
    <tr>
        <td>MEC (Plaza-Alonso)</td>
        <td>human</td>
        <td>medial entorhinal cortex, all layers (autopsy)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://bossdb.org/project/plaza-alonso2024">bossdb</a></td>
        <td>Plaza-Alonso <i>et al.</i>, <a href="REFERENCE.md#2025">2025</a></td>
        <td>DeFelipe lab; laminar synaptic characteristics</td>
    </tr>
    <tr>
        <td>Primary Cortex Regions (Cajal)</td>
        <td>human</td>
        <td>BA17, BA3b, BA4 (autopsy)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://search.kg.ebrains.eu/">ebrains</a></td>
        <td>Cano-Astorga <i>et al.</i>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>DeFelipe lab; synapses in primary visual, somatosensory and motor cortex</td>
    </tr>
    <tr>
        <td>H01</td>
        <td>human</td>
        <td>temporal lobe (epilepsy surgery biopsy)</td>
        <td>ATUM-mSEM</td>
        <td>2,000x3,000x175</td>
        <td>4x4x30</td>
        <td>50,000 cells<br>133,700,000 synapses<br>104 proofread neurons</td>
        <td><a href="https://h01-release.storage.googleapis.com/landing.html">google</a></td>
        <td>Shapson-Coe <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a>, <a href="REFERENCE.md#2024">2024</a></td>
        <td>petavoxel (~1.4 PB); blood vessels (BvEM) at <a href="https://bossdb.org/project/wan2024">bossdb</a>; AxonEM-H and MitoEM-H are subsets</td>
    </tr>
    <tr>
        <td rowspan="2">Synapse Development</td>
        <td>macaque</td>
        <td>V1, layers 2/3 and 4, postnatal ages</td>
        <td>ssEM</td>
        <td rowspan="2"></td>
        <td></td>
        <td rowspan="2"></td>
        <td rowspan="2"><a href="https://bossdb.org/project/wildenberg2023">bossdb</a></td>
        <td rowspan="2">Wildenberg <i>et al.</i>, <a href="REFERENCE.md#2023">2023</a></td>
        <td rowspan="2">synapses form and prune at similar (&ldquo;isochronic&rdquo;) times in primate and mouse</td>
    </tr>
    <tr>
        <td>mouse</td>
        <td>S1 and V1, layers 2/3 and 4, postnatal ages</td>
        <td>ssEM</td>
        <td></td>
    </tr>
    <tr>
        <td>Karlupia2023</td>
        <td>human</td>
        <td>cortex biopsies (multicubic millimeter)</td>
        <td>ATUM-mSEM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>Karlupia <i>et al.</i>, <a href="REFERENCE.md#2023">2023</a></td>
        <td>immersion fixation + staining protocol toward connectomic screening of patient tissue</td>
    </tr>
    <tr>
        <td rowspan="3">Comparative Cortex</td>
        <td>human</td>
        <td>temporal cortex, layer 2/3 and all layers (neurosurgery biopsies)</td>
        <td>SBEM</td>
        <td rowspan="3">175x220x100 (human L2/3)<br>1,700x2,100x30 (human all layers)</td>
        <td></td>
        <td rowspan="3">9 connectomic samples</td>
        <td rowspan="3"><a href="https://webknossos.org/publications">webknossos</a></td>
        <td rowspan="3">Loomba <i>et al.</i>, <a href="REFERENCE.md#2022">2022</a></td>
        <td rowspan="3">cortex (S1, A1, PFC, temporal / parietal) across species; interneuron-to-interneuron network expansion in primates</td>
    </tr>
    <tr>
        <td>macaque</td>
        <td>cortex</td>
        <td>SBEM</td>
        <td></td>
    </tr>
    <tr>
        <td>mouse</td>
        <td>cortex</td>
        <td>SBEM</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="2">Primate vs. Mouse V1</td>
        <td>macaque</td>
        <td>primary visual cortex</td>
        <td>ssEM</td>
        <td rowspan="2"></td>
        <td></td>
        <td rowspan="2">15,748 synapses</td>
        <td rowspan="2"></td>
        <td rowspan="2">Wildenberg <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td rowspan="2">primate neurons receive 2&ndash;5&times; fewer synapses than mouse neurons</td>
    </tr>
    <tr>
        <td>mouse</td>
        <td>primary visual cortex</td>
        <td>ssEM</td>
        <td></td>
    </tr>
    <tr>
        <td>Hippocampus CA1 (Cajal)</td>
        <td>human</td>
        <td>hippocampal CA1 field (autopsy)</td>
        <td>FIB-SEM</td>
        <td></td>
        <td></td>
        <td>24,752 synapses</td>
        <td><a href="https://search.kg.ebrains.eu/">ebrains</a></td>
        <td>Montero-Crespo <i>et al.</i>, <a href="REFERENCE.md#2020">2020</a></td>
        <td>DeFelipe lab; 3D synaptic organization across CA1 layers</td>
    </tr>
</table>


## Cell Biology and Non-neural Tissue

vEM beyond connectomics: whole cells, organelles and tissues.

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
        <td>CellMap</td>
        <td>mouse, drosophila, zebrafish, human</td>
        <td>9 cell cultures + 13 tissues (brain, heart, liver, kidney, …)</td>
        <td>FIB-SEM (enhanced)</td>
        <td></td>
        <td>4x4x4 or 8x8x8</td>
        <td>289 annotated crops from 22 datasets<br>&gt;40 organelle classes</td>
        <td><a href="https://cellmapchallenge.janelia.org/">challenge</a><br><a href="https://doi.org/10.25378/janelia.c.7456966">data</a></td>
        <td></td>
        <td>ground truth of the CellMap Segmentation Challenge (2025); full volumes on OpenOrganelle</td>
    </tr>
    <tr>
        <td>OpenOrganelle (COSEM)</td>
        <td>cultured cells and tissues</td>
        <td>whole cells and tissue samples</td>
        <td>FIB-SEM (enhanced)</td>
        <td></td>
        <td></td>
        <td></td>
        <td><a href="https://openorganelle.janelia.org/">openorganelle</a></td>
        <td>Heinrich <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a>; Xu <i>et al.</i>, <a href="REFERENCE.md#2021">2021</a></td>
        <td>whole-cell organelle segmentations and an open atlas of cells and tissues</td>
    </tr>
</table>


(curated with Xinghui Zhao)
