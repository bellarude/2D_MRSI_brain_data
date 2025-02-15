## Data description

Data acquired and curated in spring 2023 @ TIC, University of Bern, Dept. of Neuroradiology.

| Note | Description |
| ------ | ------ |
| Developer | Rudy Rizzo, PhD |
| Format | Matlab _.dat_; table of 4096 x 256 (time x voxel) complex double entries |
| Sequence | 2D metabolite-cycled MRSI sLASER |
| Parameters | FOV: 16 x 16, 200 x 160 mm $^2$; resolution: 80 x 60 x 15 mm $^3$, BW: 4kHz, 4096 datapoints|
|System| 3T, Siemens Healthineers|
| Body area | Brain - supraventricular FOV - 4 healthy volunteers|
| License | CC-BY 4.0 [https://creativecommons.org/licenses/by/4.0/legalcode][PlGd]|
| Credit| Please cite Shamaei A. et al. Water removal in MR spectroscopic imaging with Casorati singular value decomposition, Magn. Reson. Med. _early view_, 2024, https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.29959 |
|Contact| rurizzo@med.umich.edu|


### morphological information
Data should be processed adding a fftshift in spatial domain followed by a matlab reshape on a support matrix of [4096, 16, 16]. 

### IRB
All scans were performed in accordance with the ethical review boards, and informed consent was obtained from all investigated subjects.
