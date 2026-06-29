Eddy detection in polar and subpolar areas from raw L3_LR_SSH SWOT 'filtered SLA'. 

Companion dataset of [1] de Marez et al. 2026b (under review), which uses the methodology defined in [2] de Marez et al. 2026a (https://os.copernicus.org/articles/22/1515/2026/).

For the Norther and the Southern hemishpheres, the detection is performed in sub-domains, as defined in Fig. 1 of [1].

The detections for each sub-domain are stored in sub-folders, in which: 

- Files *post-proc-data-detection_pt_40_ct_0.6_Rmin_05_Amin_0.01_shapeerror_85.nc* contain the eddy position and parameters as used for the eddy density calculation. It follows the methodology of detection and filtering of eddies described in [2]. In these files, duplicates in each cycles are removed.
- *ice-...nc*, *topo-...nc*, and *Rd-...nc* files contain the ice concentration, topography, and deformation radius at eddy locations.
- The sub-sub-folders *raw_detection/* contain the detections from **all** SWOT tracks, prior to duplicate removal. This is the eddy field we suggest to use for *e.g.*, colocalization of profile data.


We supply in the *notebooks/* folder notebooks allowing to load and quickly visualize the eddy field. 




