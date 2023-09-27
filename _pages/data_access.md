---
title: Data Access
author: Kai Zhu
date: 2023-02-01
category: Jekyll
layout: post
---

The MaNGA DynPop catalogs are publicly available on [Github][1], including (1) the stellar dynamical properties and (2) the stellar population and star-formation history properties for over 10000 galaxies from [MaNGA survey][MaNGA survey]. 

The stellar dynamical properties are obtained using the well-established Jeans Anisotropic Modelling (JAM) method ([Cappellari 2008][Cappellari2008]; [Cappellari 2020][Cappellari2020]). 

The stellar population and star-formation history properties are obtained from the stellar population synthesis (SPS) method using the Penalized Pixel-Fitting software (pPXF; [Cappellari&Emsellem 2004][Cappellari2004]; [Cappellari 2017][Cappellari2017]; [Cappellari 2023][Cappellari2023]).

<font color=red>If you use any data below, you are requested to cite the paper in the section where the link to the data is given.</font>

---

### [Paper I][PaperI]

The JAM catalog file `SDSSDR17_MaNGA_JAM.fits` and the data model file `SDSSDR17_MaNGA_JAM_datamodel.pdf` can be downloaded from [here][2].

The supplementary files including the MGE models and the mass profiles will be released once prepared.

---

### [Paper II][PaperII]
The stellar population (SP) and star-formation history (SFH) catalogue (`DynPop2_SPSFH_v1.hdf5`), the data explanation (`SP_catalog_explanation.pdf`), and an example PYTHON script for reading the catalogue (`HDF5_reading_script.py`) can be downloaded from [zenodo][3]. 

---


[1]: https://github.com/manga-dynpop/manga-dynpop.github.io/tree/main/catalogs
[2]: https://github.com/manga-dynpop/manga-dynpop.github.io/tree/main/catalogs/JAM
[3]: https://zenodo.org/record/8381999
[MaNGA survey]: https://ui.adsabs.harvard.edu/abs/2015ApJ...798....7B/abstract
[Cappellari2008]: https://ui.adsabs.harvard.edu/abs/2008MNRAS.390...71C/abstract
[Cappellari2020]: https://ui.adsabs.harvard.edu/abs/2020MNRAS.494.4819C/abstract
[Cappellari2004]: https://ui.adsabs.harvard.edu/abs/2004PASP..116..138C/abstract
[Cappellari2017]: https://ui.adsabs.harvard.edu/abs/2017MNRAS.466..798C/abstract
[Cappellari2023]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.tmp.2472C/abstract
[PaperI]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.522.6326Z/abstract
[PaperII]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.tmp.2611L/abstract
