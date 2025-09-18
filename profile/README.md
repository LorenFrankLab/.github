# The Frank Lab
https://franklab.ucsf.edu/

Our laboratory focuses on the circuitry of the hippocampus and anatomically related regions.   We use a combination of techniques, including large scale multielectrode recording, real-time signal processing and targeted optogenetic interventions and behavioral manipulations of awake, behaving animals to understand how the brain learns, remembers and decides.

<img src="lab_picture_2022.jpg" alt="lab picture" width="250"/>

#### Main Data Processing Pipelines
+ [spyglass](https://github.com/LorenFrankLab/spyglass) - Neuroscience data analysis framework using NWB files and Datajoint pipelines
+ [trodes_to_nwb](https://github.com/LorenFrankLab/trodes_to_nwb) - Convert trodes .rec files to the NWB 2.0+ data format
+ [NWB Yaml creator](https://github.com/LorenFrankLab/rec_to_nwb_yaml_creator) - Create standardized metadata YAML files for use with `trodes_to_nwb`

#### Useful Data Processing Packages 
+ [track_linearization](https://github.com/LorenFrankLab/track_linearization) - Convert 2D position to 1D position
+ [replay_trajectory_classification](https://github.com/Eden-Kramer-Lab/replay_trajectory_classification) - Decode and categorize trajectories from spiking data
+ [ripple_detection](https://github.com/Eden-Kramer-Lab/ripple_detection) - Detect ripples using the LFP
+ [position_tools](https://github.com/LorenFrankLab/position_tools) - Tools for calculating smoothed 2D position, speed, head direction from LEDs on head stage

#### Code for Papers
+ Joshi, A., Comrie, A.E., Bray, S., Mankili, A., Guidera, J.A., Nevers, R., Sun, X., Monroe, E., Kharazia, V., Ly, R., et al. (2025). Disruption of theta-timescale spiking impairs learning but spares hippocampal replay. bioRxiv, 2025.09.15.675587.
[[Paper]](https://doi.org/10.1016/j.neuron.2024.12.023)
[[Code]](https://github.com/LorenFrankLab/ms_stim_analysis)
+ Coulter, M.E., Gillespie, A.K., Chu, J., Denovellis, E.L., Nguyen, T.T.K., Liu, D.F., Wadhwani, K., Sharma, B., Wang, K., Deng, X., et al. (2025). **Closed-loop modulation of remote hippocampal representations with neurofeedback.** Neuron 113, 949-961.e3.
[[Paper]](https://doi.org/10.1016/j.neuron.2024.12.023)
[[Code]](https://github.com/LorenFrankLab/hippocampus_content_neurofeedback)
+ Joshi, A., Denovellis, E.L., Mankili, A., Meneksedag, Y., Davidson, T.J., Gillespie, A.K., Guidera, J.A., Roumis, D., and Frank, L.M. (2023). **Dynamic synchronization between hippocampal representations and stepping.** Nature. 2023 Apr 12;10.1038/s41586-023-05928-6.
[[Paper]](http://dx.doi.org/10.1038/s41586-023-05928-6)
[[Code]](https://github.com/LorenFrankLab/Joshi_et_al_2023)
[[Data]](https://dandiarchive.org/dandiset/000410/draft)
+ Denovellis EL, Gillespie AK, Coulter ME, Sosa M, Chung JE, Eden UT, et al. **Hippocampal replay of experience at real-world speeds.** eLife. 2021 Sep 27;10:e64505.
[[Paper]](http://dx.doi.org/10.7554/eLife.64505)
[[Code]](https://github.com/Eden-Kramer-Lab/replay_trajectory_paper)
[[Data]](https://doi.org/10.7272/Q61N7ZC3)
+ Gillespie AK, Astudillo Maya DA, Denovellis EL, Liu DF, Kastner DB, Coulter ME, et al. **Hippocampal replay reflects specific past experiences rather than a plan for subsequent choice.** Neuron. 2021 Aug;S0896627321005730.
[[Paper]](http://dx.doi.org/10.1016/j.neuron.2021.07.029)
[[Code]](https://github.com/LorenFrankLab/Gillespie_Neuron_2021)
[[Data]](https://doi.org/10.48324/dandi.000115/0.210914.1732)

