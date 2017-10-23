# RealSense
The Ubuntu Debian release has a bug. It always publish one more extra link called `camera_ir_optical_frame`, besides `wrist_sr300_realsense_ir_optical_frame`, even though I have change the parameter `camera` into `wrist_sr300_realsense`. So we will use the `indigo-devel` branch, which only published the TF for `wrist_sr300_realsense_ir_optical_frame`.
