20260512
Copied from 20260422_reiser_feature_learning_board4_150mm. Changed
circleRadius_mm in registration_params.txt from 60 to 75, since the
150 mm bowl has a 75 mm radius. The previous value of 60 caused PPM
to be computed as 615/60 = 10.25 px/mm, vs the correct 615/75 = 8.2
px/mm (matching the parent calibration's PPM). Repointed the
current_reiser_feature_learning_board_4_150mm symlink to this folder.
flytracker-parent-calibration.mat is unchanged from
20260422_reiser_feature_learning_board4_150mm: a fresh calibration
built from experiment 20260422_155408_L2A_P013 was tried but had
essentially identical fly-size params, so we kept the original.

20260210
Created this analysis-protocol folder that is specific for board 3,
with appropriate flytracker-parent-calibration.mat

2025-late
Updated for Shubham's rig

copied from FlyDiscoAnalysis/settings/20210806_flybubble_LED

modified the ctrax results movie params for the 20220414 LED protocol

20220609
changed VNC_barcode to VNC2__barcode in incoming checks

20220913
added jab classifiers

202201005
added parameters for APT tracking

20230213 from - 20220913_flybubble_LED_VNC2
adding parameters for apt results movie

20230307
updated the lbl file, same name in apt_params.txt 
Same tracker just updated the slots for tracking and training to work with APT update

20230518
added Alice updated walk jaaba classifier -> scores_walk2.mat

20230622
updated the singularity image pointer for cluster upgrade

20230907
added missing parameter to datalocs 
flytrackerbgstr,movie-bg.mat

20240906
update gpu queue to gpu_l4_large

20240913
change gpu queue to gpu_l4

20241203
add locomotion stage
