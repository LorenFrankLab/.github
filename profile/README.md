# The Frank Lab
https://franklab.ucsf.edu/

Our laboratory focuses on the circuitry of the hippocampus and anatomically related regions.   We use a combination of techniques, including large scale multielectrode recording, real-time signal processing and targeted optogenetic interventions and behavioral manipulations of awake, behaving animals to understand how the brain learns, remembers and decides.

<img src="profile/lab_picture_2022.jpg" alt="lab picture" width="250"/>

#### Main Data Processing Pipelines
+ [spyglass](https://github.com/LorenFrankLab/spyglass) - Neuroscience data analysis framework using NWB files and Datajoint pipelines
+ [rec_to_nwb](https://github.com/LorenFrankLab/rec_to_nwb) - Convert trodes .rec files to the NWB 2.0 data format
+ [NWB Yaml creator](https://github.com/LorenFrankLab/rec_to_nwb_yaml_creator) - Create standardized metadata YAML files for use with `rec_to_nwb`

#### Useful Data Processing Packages 
+ [track_linearization](https://github.com/LorenFrankLab/track_linearization) - Convert 2D position to 1D position
+ [replay_trajectory_classification](https://github.com/Eden-Kramer-Lab/replay_trajectory_classification) - Decode and categorize trajectories from spiking data
+ [ripple_detection](https://github.com/Eden-Kramer-Lab/ripple_detection) - Detect ripples using the LFP
+ [position_tools](https://github.com/LorenFrankLab/position_tools) - Tools for calculating smoothed 2D position, speed, head direction from LEDs on head stage

#### Code for Papers
+ [Gillespie AK, Astudillo Maya DA, Denovellis EL, Liu DF, Kastner DB, Coulter ME, et al. Hippocampal replay reflects specific past experiences rather than a plan for subsequent choice. Neuron. 2021 Aug;S0896627321005730. 
](https://github.com/LorenFrankLab/Gillespie_Neuron_2021)
+ [Denovellis EL, Gillespie AK, Coulter ME, Sosa M, Chung JE, Eden UT, et al. Hippocampal replay of experience at real-world speeds. eLife. 2021 Sep 27;10:e64505. 
](https://github.com/Eden-Kramer-Lab/replay_trajectory_paper)
