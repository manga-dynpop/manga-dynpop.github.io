---
title: Data Access
author: Kai Zhu
date: 2023-02-01
category: Jekyll
layout: post
---

The MaNGA DynPop catalogs are publicly available on [Github][1], including the stellar dynamical properties and the stellar population properties. The stellar dynamical properties are obtained using the well-established Jeans Anisotropic Modelling (JAM) method ([Cappellari 2008][Cappellari2008],[Cappellari 2020][Cappellari2020]). The stellar population properties are obtained from the stellar population synthesis (SPS) models.

<font color=red>If you use any data below, you are requested to cite the paper in the section where the link to the data is given.</font>

---

### [Paper I][PaperI]

The JAM catalog file `SDSSDR17_MaNGA_JAM.fits` and the data model file `SDSSDR17_MaNGA_JAM_datamodel.pdf` can be downloaded from [here][2].

The supplementary files including the MGE models and the mass profiles will be released once prepared.

---

### [Paper II][PaperII]

The SPS catalog file, the data model file, and a Python script can be downloaded from [zenodo][3]. 

---


[1]: https://github.com/manga-dynpop/manga-dynpop.github.io/tree/main/catalogs
[2]: https://github.com/manga-dynpop/manga-dynpop.github.io/tree/main/catalogs/JAM
[3]: https://zenodo.org/record/8381999
[Cappellari2008]: https://ui.adsabs.harvard.edu/abs/2008MNRAS.390...71C/abstract
[Cappellari2020]: https://ui.adsabs.harvard.edu/abs/2020MNRAS.494.4819C/abstract
[PaperI]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.522.6326Z/abstract
[PaperII]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.tmp.2611L/abstract
