
# COFII framework examples 

This series of jupyter notebooks demonstrates features of the `Chevron Optimization Framework for Imaging and Inversion`.

* The notebooks are intended to be run in order. 
<br>
* Downstream notebooks may depend on artifacts created in previous notebooks. For example the Marmousi dataset is downloaded and processed in the series `20_marmousi_model_setup`, and used in subsequent notebooks. 
<br>
* Some notebooks may require reasonable HPC resources to run. For example the FWI and RTM examples can run for more than one hour, depending on what hardware you execute them on. 


## Brief description of notebook series
* `10_jets_basics` introduction to `Jets` and `DistributedJets` 
* `20_marmousi_model_setup` download the Marmousi model
* `30_forward_modeling` static and dynamic scheduled modeling
* `40_single_trace_sensitivity` generation of FWI sensitivity kernel
* `50_fwi` brute force Marmousi time domain FWI 
* `60_rtm` brute force RTM of the Marmous FWI results