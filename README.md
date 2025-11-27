# vgpu
==============NVSMI LOG==============

Timestamp                                 : Tue Nov 1 12:06:50 2025
Driver Version                            : 525.147.01
CUDA Version                              : Not Found
vGPU Driver Capability
        Heterogenous Multi-vGPU           : Supported

Attached GPUs                             : 1
GPU 00000000:01:00.0
    Product Name                          : NVIDIA GeForce RTX 4088
    Product Brand                         : GeForce
    Product Architecture                  : Ada Lovelace
    Display Mode                          : Enabled
    Display Active                        : Disabled
    Persistence Mode                      : Enabled
    vGPU Device Capability
        Fractional Multi-vGPU             : Supported
        Heterogeneous Time-Slice Profiles : Supported
        Heterogeneous Time-Slice Sizes    : Not Supported
    MIG Mode
        Current                           : N/A
        Pending                           : N/A
--
    GPU Operation Mode
        Current                           : N/A
        Pending                           : N/A
    GSP Firmware Version                  : N/A
    GPU Virtualization Mode
        Virtualization Mode               : Host VGPU
        Host VGPU Mode                    : Non SR-IOV

Tue Nov 1 12:06:50 2025       
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 525.147.01             Driver Version: 525.147.01                |
|---------------------------------+------------------------------+------------+
| GPU  Name                       | Bus-Id                       | GPU-Util   |
|      vGPU ID     Name           | VM ID     VM Name            | vGPU-Util  |
|=================================+==============================+============|
|   0  NVIDIA GeForce RTX 408...  | 00000000:01:00.0             |   0%       |
+---------------------------------+------------------------------+------------+

[    4.284387] nvidia: module verification failed: signature and/or required key missing - tainting kernel
[    4.352879] nvidia-nvlink: Nvlink Core is being initialized, major device number 509
[    4.353680] nvidia 0000:01:00.0: vgaarb: changed VGA decodes: olddecodes=io+mem,decodes=none:owns=none
[    5.058014] NVRM: GPU at 0000:01:00.0 has software scheduler DISABLED with policy BEST_EFFORT.
[    5.718532] nvidia 0000:01:00.0: MDEV: Registered

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=akb486/vgpu&type=date&legend=top-left)](https://www.star-history.com/#akb486/vgpu&type=date&legend=top-left)
