# Vapoursynth-HIP-SSIMU2
An easy to use plugin for vapoursynth performing SSIMU2 measurments using the GPU with HIP

Current status: (with fps for feature and above on my laptop with RTX 4050 mobile on some x264 clip)

- vs plugin part = complete (360 fps)
- put frames on GPU = complete (106 fps)
- downsampling = complete (106 fps)
- make XYB = complete (106 fps)
- fill buffer s11, s22, s12 = x
- gaussian blur = x
- ssim map = x
- edge diff map = x
- get score back = x
- enjoy (debug + quality_check) = x