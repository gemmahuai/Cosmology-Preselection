# Cosmology-Preselection
color-magnitude cut for the SPHEREx cosmology preselection (Nov 15th, 2024) 

Several notes: 

* Goal: apply some color-magnitude cut to select sources that are expected to provide accurate redshift estimates for downstream cosmology studies.

* Method: this initial preselection uses photometry from the Legacy Survey (LS) z-band and WISE1 band. Future selections many involve more complicated cuts.

* Please follow the jupyter notebook for more details. To reproduce the results, you can simply pull the jupyter notebook and the cross-matched catalog (between COSMOS 166k and SPHEREx refcat v0.6), and rerun the notebook. A summary of the statistics is available at the end of the notebook. 

* Dependencies: really just some common python packages. There is no dependence on the SPHEREx sky simulator or any associated pipelines. The primary input needed is the catalog.