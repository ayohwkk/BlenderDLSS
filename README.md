DLSS Ray Reconstruction Support
--------------------------------

This Blender build includes support for NVIDIA DLSS Ray Reconstruction.

Due to NVIDIA licensing restrictions, the DLSS runtime library (nvngx_dlssd.dll)
is NOT included.

This file can be obtained from a game that
includes DLSS Ray Reconstruction (such as Portal RTX).

To enable DLSS:
1. Obtain nvngx_dlssd.dll from a DLSS-RR-enabled game.
2. Place the DLL next to blender.exe.
3. Launch Blender and select DLSS as the viewport denoiser.
  

DEVICE REQUIREMENTS & IMPORTANT DOWNLOADS
-----------------------------------------
1. Nvidia Driver 590+
2. GPU capable of DLSS
3. You may need to install cuda_12.4.0_551.61;
"https://developer.nvidia.com/cuda-12-4-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_local"


