# vgpu 30 40 50 coming soon
```
nvidia-smi -q
==============NVSMI LOG==============

Timestamp                                 : Thu Nov 2 21:43:18 2025
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
    GPU Virtualization Mode
        Virtualization Mode               : Host VGPU
        Host VGPU Mode                    : Non SR-IOV
Thu Nov 2 21:43:18 2025       
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 525.147.01             Driver Version: 525.147.01                |
|---------------------------------+------------------------------+------------+
| GPU  Name                       | Bus-Id                       | GPU-Util   |
|      vGPU ID     Name           | VM ID     VM Name            | vGPU-Util  |
|=================================+==============================+============|
|   0  NVIDIA GeForce RTX 408...  | 00000000:01:00.0             |   0%       |
+---------------------------------+------------------------------+------------+
```
```
mdevctl types
0000:01:00.0
  nvidia-522
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-1B
    Description: num_heads=4, frl_config=45, framebuffer=1024M, max_resolution=5120x2880, max_instance=32
  nvidia-523
    Available instances: 23
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-2B
    Description: num_heads=4, frl_config=45, framebuffer=2048M, max_resolution=5120x2880, max_instance=24
  nvidia-524
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-1Q
    Description: num_heads=4, frl_config=60, framebuffer=1024M, max_resolution=5120x2880, max_instance=32
  nvidia-525
    Available instances: 23
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-2Q
    Description: num_heads=4, frl_config=60, framebuffer=2048M, max_resolution=7680x4320, max_instance=24
  nvidia-526
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-3Q
    Description: num_heads=4, frl_config=60, framebuffer=3072M, max_resolution=7680x4320, max_instance=16
  nvidia-527
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-4Q
    Description: num_heads=4, frl_config=60, framebuffer=4096M, max_resolution=7680x4320, max_instance=12
  nvidia-528
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-6Q
    Description: num_heads=4, frl_config=60, framebuffer=6144M, max_resolution=7680x4320, max_instance=8
  nvidia-529
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-8Q
    Description: num_heads=4, frl_config=60, framebuffer=8192M, max_resolution=7680x4320, max_instance=6
  nvidia-530
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-12Q
    Description: num_heads=4, frl_config=60, framebuffer=12288M, max_resolution=7680x4320, max_instance=4
  nvidia-531
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-16Q
    Description: num_heads=4, frl_config=60, framebuffer=16384M, max_resolution=7680x4320, max_instance=3
  nvidia-532
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-24Q
    Description: num_heads=4, frl_config=60, framebuffer=24576M, max_resolution=7680x4320, max_instance=2
  nvidia-533
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-48Q
    Description: num_heads=4, frl_config=60, framebuffer=49152M, max_resolution=7680x4320, max_instance=1
  nvidia-534
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-1A
    Description: num_heads=1, frl_config=60, framebuffer=1024M, max_resolution=1280x1024, max_instance=32
  nvidia-535
    Available instances: 23
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-2A
    Description: num_heads=1, frl_config=60, framebuffer=2048M, max_resolution=1280x1024, max_instance=24
  nvidia-536
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-3A
    Description: num_heads=1, frl_config=60, framebuffer=3072M, max_resolution=1280x1024, max_instance=16
  nvidia-537
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-4A
    Description: num_heads=1, frl_config=60, framebuffer=4096M, max_resolution=1280x1024, max_instance=12
  nvidia-538
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-6A
    Description: num_heads=1, frl_config=60, framebuffer=6144M, max_resolution=1280x1024, max_instance=8
  nvidia-539
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-8A
    Description: num_heads=1, frl_config=60, framebuffer=8192M, max_resolution=1280x1024, max_instance=6
  nvidia-540
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-12A
    Description: num_heads=1, frl_config=60, framebuffer=12288M, max_resolution=1280x1024, max_instance=4
  nvidia-541
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-16A
    Description: num_heads=1, frl_config=60, framebuffer=16384M, max_resolution=1280x1024, max_instance=3
  nvidia-542
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-24A
    Description: num_heads=1, frl_config=60, framebuffer=24576M, max_resolution=1280x1024, max_instance=2
  nvidia-543
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-48A
    Description: num_heads=1, frl_config=60, framebuffer=49152M, max_resolution=1280x1024, max_instance=1
  nvidia-548
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-4C
    Description: num_heads=1, frl_config=60, framebuffer=4096M, max_resolution=4096x2400, max_instance=12
  nvidia-549
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-6C
    Description: num_heads=1, frl_config=60, framebuffer=6144M, max_resolution=4096x2400, max_instance=8
  nvidia-550
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-8C
    Description: num_heads=1, frl_config=60, framebuffer=8192M, max_resolution=4096x2400, max_instance=6
  nvidia-551
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-12C
    Description: num_heads=1, frl_config=60, framebuffer=12288M, max_resolution=4096x2400, max_instance=4
  nvidia-552
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-16C
    Description: num_heads=1, frl_config=60, framebuffer=16384M, max_resolution=4096x2400, max_instance=3
  nvidia-553
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-24C
    Description: num_heads=1, frl_config=60, framebuffer=24576M, max_resolution=4096x2400, max_instance=2
  nvidia-554
    Available instances: 0
    Device API: vfio-pci
    Name: NVIDIA RTXA6000-48C
    Description: num_heads=1, frl_config=60, framebuffer=49152M, max_resolution=4096x2400, max_instance=1
```
```
○ nvidia-vgpud.service - NVIDIA vGPU Daemon
     Loaded: loaded (/lib/systemd/system/nvidia-vgpud.service; enabled; preset: enabled)
    Drop-In: /etc/systemd/system/nvidia-vgpud.service.d
             └─vgpu_unlock.conf
     Active: inactive (dead) since Thu 2025-11-2 21:40:41 CST; 2min 37s ago
   Duration: 678ms
    Process: 940 ExecStart=/usr/bin/nvidia-vgpud (code=exited, status=0/SUCCESS)
    Process: 1028 ExecStopPost=/bin/rm -rf /var/run/nvidia-vgpud (code=exited, status=0/SUCCESS)
   Main PID: 965 (code=exited, status=0/SUCCESS)
        CPU: 77ms

Nov 2 21:40:41 pve nvidia-vgpud[965]: Frame Rate Limiter enabled: 0x1
Nov 2 21:40:41 pve nvidia-vgpud[965]: Number of Displays: 1
Nov 2 21:40:41 pve nvidia-vgpud[965]: Max pixels: 9216000
Nov 2 21:40:41 pve nvidia-vgpud[965]: Display: width 4096, height 2400
Nov 2 21:40:41 pve nvidia-vgpud[965]: Multi-vGPU Exclusive supported: 0x1
Nov 2 21:40:41 pve nvidia-vgpud[965]: License: NVIDIA-vComputeServer,9.0;Quadro-Virtual-DWS,5.0
Nov 2 21:40:41 pve nvidia-vgpud[965]: PID file unlocked.
Nov 2 21:40:41 pve nvidia-vgpud[965]: PID file closed.
Nov 2 21:40:41 pve nvidia-vgpud[965]: Shutdown (965)
Nov 2 21:40:41 pve systemd[1]: nvidia-vgpud.service: Deactivated successfully.
```
```
● nvidia-vgpu-mgr.service - NVIDIA vGPU Manager Daemon
     Loaded: loaded (/lib/systemd/system/nvidia-vgpu-mgr.service; enabled; preset: enabled)
    Drop-In: /etc/systemd/system/nvidia-vgpu-mgr.service.d
             └─vgpu_unlock.conf
     Active: active (running) since Thu 2025-11-2 21:40:40 CST; 2min 38s ago
    Process: 939 ExecStart=/usr/bin/nvidia-vgpu-mgr (code=exited, status=0/SUCCESS)
   Main PID: 964 (nvidia-vgpu-mgr)
      Tasks: 1 (limit: 154175)
     Memory: 980.0K
        CPU: 535ms
     CGroup: /system.slice/nvidia-vgpu-mgr.service
             └─964 /usr/bin/nvidia-vgpu-mgr

Nov 2 21:40:40 pve systemd[1]: Starting nvidia-vgpu-mgr.service - NVIDIA vGPU Manager Daemon...
Nov 2 21:40:40 pve systemd[1]: Started nvidia-vgpu-mgr.service - NVIDIA vGPU Manager Daemon.
Nov 2 21:40:41 pve nvidia-vgpu-mgr[964]: notice: vmiop_env_log: nvidia-vgpu-mgr daemon started
```
```
dmesg
[    4.275380] nvidia: module verification failed: signature and/or required key missing - tainting kernel
[    4.334737] nvidia-nvlink: Nvlink Core is being initialized, major device number 509
[    4.335546] nvidia 0000:01:00.0: vgaarb: changed VGA decodes: olddecodes=io+mem,decodes=none:owns=none
[    4.378677] NVRM: loading NVIDIA UNIX x86_64 Kernel Module  525.147.01  Wed Oct 11 10:20:43 UTC 2023
[    5.016865] NVRM: GPU at 0000:01:00.0 has software scheduler DISABLED with policy BEST_EFFORT.
[    5.670781] nvidia 0000:01:00.0: MDEV: Registered
[   73.932855] nvidia-vgpu-vfio 00000000-0000-0000-0000-000000000101: Adding to iommu group 19
[   74.387912] [nvidia-vgpu-vfio] 00000000-0000-0000-0000-000000000101: vGPU migration enabled with upstream V2 migration protocol
```
```
nvidia-smi
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 525.147.01   Driver Version: 525.147.01   CUDA Version: N/A      |
|-------------------------------+----------------------+----------------------+
| GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |
| Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
|                               |                      |               MIG M. |
|===============================+======================+======================|
|   0  NVIDIA GeForce ...  On   | 00000000:01:00.0 Off |                  N/A |
| N/A   29C    P8     8W / 115W |   2036MiB /  8188MiB |      0%      Default |
|                               |                      |                  N/A |
+-------------------------------+----------------------+----------------------+
                                                                               
+-----------------------------------------------------------------------------+
| Processes:                                                                  |
|  GPU   GI   CI        PID   Type   Process name                  GPU Memory |
|        ID   ID                                                   Usage      |
|=============================================================================|
|    0   N/A  N/A      1583    C+G   vgpu                             2036MiB |
+-----------------------------------------------------------------------------+
```
```
nvidia-smi vgpu
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 525.147.01             Driver Version: 525.147.01                |
|---------------------------------+------------------------------+------------+
| GPU  Name                       | Bus-Id                       | GPU-Util   |
|      vGPU ID     Name           | VM ID     VM Name            | vGPU-Util  |
|=================================+==============================+============|
|   0  NVIDIA GeForce RTX 408...  | 00000000:01:00.0             |   0%       |
|      3251634190  NVIDIA RTXA... | f267...  win10test,debug-... |      0%    |
+---------------------------------+------------------------------+------------+
```
nvidia-smi vgpu -q
GPU 00000000:01:00.0
    Active vGPUs                          : 1
    vGPU ID                               : 3251634190
        VM UUID                           : 
        VM Name                           : win10test,debug-threads=on
        vGPU Name                         : NVIDIA RTXA6000-2Q
        vGPU Type                         : 525
        vGPU UUID                         : 
        MDEV UUID                         : 00000000-0000-0000-0000-000000000101
        Guest Driver Version              : N/A
        License Status                    : N/A (Expiry: N/A)
        GPU Instance ID                   : N/A
        Accounting Mode                   : N/A
        ECC Mode                          : N/A
        Accounting Buffer Size            : 4000
        Frame Rate Limit                  : N/A
        PCI
            Bus Id                        : 00000000:00:00.0
        FB Memory Usage
            Total                         : 2048 MiB
            Used                          : 0 MiB
            Free                          : 2048 MiB
        Utilization
            Gpu                           : 0 %
            Memory                        : 0 %
            Encoder                       : 0 %
            Decoder                       : 0 %
        Encoder Stats
            Active Sessions               : 0
            Average FPS                   : 0
            Average Latency               : 0
        FBC Stats
            Active Sessions               : 0
            Average FPS                   : 0
            Average Latency               : 0
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=akb486/vgpu&type=date&legend=top-left)](https://www.star-history.com/#akb486/vgpu&type=date&legend=top-left)
