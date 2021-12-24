# Kernel Module
https://forum.manjaro.org/t/set-nvidia-gpu-performance-level-possible/47728

-> https://forums.developer.nvidia.com/t/solved-forcing-maximum-power-saving-on-the-desktop-minimum-power-mode-for-powermizer/30403/7

>An update from 2020. Some users may now require a kernel module option instead of an X.org 47 option.
>
>cat /etc/modprobe.d/nvidia.conf
>options nvidia NVreg_RegistryDwords="OverrideMaxPerf=0x1"
