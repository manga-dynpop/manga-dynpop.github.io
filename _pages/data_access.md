---
title: Data Access
author: Kai Zhu
date: 2023-02-01
category: Jekyll
layout: post
---

The MaNGA DynPop catalogues are publicly available, including (1) the stellar dynamical properties and (2) the stellar population and star-formation history properties for over 10000 galaxies from [MaNGA survey][MaNGA survey]. 

The stellar dynamical properties are obtained using the well-established Jeans Anisotropic Modelling (JAM) method ([Cappellari 2008][Cappellari2008]; [Cappellari 2020][Cappellari2020]). 

The stellar population and star-formation history properties are obtained from the stellar population synthesis (SPS) method using the Penalized Pixel-Fitting software (pPXF; [Cappellari&Emsellem 2004][Cappellari2004]; [Cappellari 2017][Cappellari2017]; [Cappellari 2023][Cappellari2023]).

<font color=red>If you use any data below, you are requested to cite the paper in the section where the link to the data is given.</font>

---

### [Paper I][PaperI] and [Paper V][PaperV]
NOTE: The JAM catalogue has been updated to v2 (on 2026.02.06) to include two additional PL models (the power-law models from [PaperV]).

The updated JAM catalogue file `SDSSDR17_MaNGA_JAM_v2.fits` and the data model file `SDSSDR17_MaNGA_JAM_v2_datamodel.pdf` can be downloaded from [zenodo][JAMmass]. No changes are made for the original models: the mass-follows-light (MFL), NFW, fixedNFW, gNFW models. Please cite [PaperI] if you use the mass-follows-light (MFL), NFW, fixedNFW, gNFW models and [PaperV] if you use the PL models.

The supplementary files including the MGE models and the mass profiles have been released in [PaperVII] (see below).

---

### [Paper II][PaperII]
NOTE: The SP catalogue has been updated to v2 (on 2025.06.26) to fix three incorrectively saved parameters  ("delta_Map", "Fred_tot_Map", "Fred_gal_Map") and include two additional parameters ("chi2_Re", "chi2_Map").

The updated stellar population (SP) and star-formation history (SFH) catalogue (`DynPop2_SP_SFH_v2.hdf5`), the catalogue documentation (`DynPop2_catalogue_documentation.pdf`), an example PYTHON script for reading the catalogue (`DynPop2_reading_script.py`), and a Jupyter Notebook with tutorials on how to use this catalogue (`DynPop2-Tutorial.ipynb`) can be downloaded from [zenodo][SPScat].

---

### [Paper VII][PaperVII]

All data derived from the stellar dynamical models including 3D mass distributions (mass density profiles), 2D mass distributions (surface mass density maps), and circular velocity curves will be released. One can use the MGE coefficients and best-fitting free parameters taken from the catalogues ([PaperI] and [PaperV]) to derive the mass distributions of stellar, dark matter, and total components. The database and a Python script for the calculation can be downloaded from [zenodo][JAMmass]. Please also cite [PaperVII] if you use the Pyhton script to calculate the mass distributions.

---


[SPScat]: https://zenodo.org/records/15742825
[JAMmass]: https://zenodo.org/records/17518315
[MaNGA survey]: https://ui.adsabs.harvard.edu/abs/2015ApJ...798....7B/abstract
[Cappellari2008]: https://ui.adsabs.harvard.edu/abs/2008MNRAS.390...71C/abstract
[Cappellari2020]: https://ui.adsabs.harvard.edu/abs/2020MNRAS.494.4819C/abstract
[Cappellari2004]: https://ui.adsabs.harvard.edu/abs/2004PASP..116..138C/abstract
[Cappellari2017]: https://ui.adsabs.harvard.edu/abs/2017MNRAS.466..798C/abstract
[Cappellari2023]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.tmp.2472C/abstract
[PaperI]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.522.6326Z/abstract
[PaperII]: https://ui.adsabs.harvard.edu/abs/2023MNRAS.526.1022L/abstract
[PaperIII]: https://ui.adsabs.harvard.edu/abs/2024MNRAS.527..706Z/abstract
[PaperIV]: https://ui.adsabs.harvard.edu/abs/2024MNRAS.527.1580W/abstract
[PaperV]: https://ui.adsabs.harvard.edu/abs/2024MNRAS.530.4474L/abstract
[PaperVI]: https://ui.adsabs.harvard.edu/abs/2024MNRAS.529.4633L/abstract
[PaperVII]: https://ui.adsabs.harvard.edu/abs/2025ApJS..280...55Z/abstract
