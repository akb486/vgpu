# vgpu
==============NVSMI LOG==============


Timestamp                                 : Thu Nov 1 21:43:18 2025

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
        
+-----------------------------------------------------------------------------+

| NVIDIA-SMI 525.147.01             Driver Version: 525.147.01                |

|---------------------------------+------------------------------+------------+

| GPU  Name                       | Bus-Id                       | GPU-Util   |

|      vGPU ID     Name           | VM ID     VM Name            | vGPU-Util  |

|=================================+==============================+============|

|   0  NVIDIA GeForce RTX 408...  | 00000000:01:00.0             |   0%       |

+---------------------------------+------------------------------+------------+

mdevctl types

  nvidia-256
  
    Available instances: 24
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-1Q
    
    Description: num_heads=4, frl_config=60, framebuffer=1024M, max_resolution=5120x2880, max_instance=24
    
  nvidia-257
  
    Available instances: 12
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-2Q
    
    Description: num_heads=4, frl_config=60, framebuffer=2048M, max_resolution=7680x4320, max_instance=12
    
  nvidia-258
  
    Available instances: 8
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-3Q
    
    Description: num_heads=4, frl_config=60, framebuffer=3072M, max_resolution=7680x4320, max_instance=8
    
  nvidia-259
  
    Available instances: 6
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-4Q
    
    Description: num_heads=4, frl_config=60, framebuffer=4096M, max_resolution=7680x4320, max_instance=6
    
  nvidia-260
  
    Available instances: 4
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-6Q
    
    Description: num_heads=4, frl_config=60, framebuffer=6144M, max_resolution=7680x4320, max_instance=4
    
  nvidia-261
  
    Available instances: 3
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-8Q
    
    Description: num_heads=4, frl_config=60, framebuffer=8192M, max_resolution=7680x4320, max_instance=3
    
  nvidia-262
  
    Available instances: 2
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-12Q
    
    Description: num_heads=4, frl_config=60, framebuffer=12288M, max_resolution=7680x4320, max_instance=2
    
  nvidia-263
  
    Available instances: 1
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-24Q
    
    Description: num_heads=4, frl_config=60, framebuffer=24576M, max_resolution=7680x4320, max_instance=1
    
  nvidia-343
  
    Available instances: 6
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-4C
    
    Description: num_heads=1, frl_config=60, framebuffer=4096M, max_resolution=4096x2400, max_instance=6
    
  nvidia-344
  
    Available instances: 4
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-6C
    
    Description: num_heads=1, frl_config=60, framebuffer=6144M, max_resolution=4096x2400, max_instance=4
    
  nvidia-345
  
    Available instances: 3
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-8C
    
    Description: num_heads=1, frl_config=60, framebuffer=8192M, max_resolution=4096x2400, max_instance=3
    
  nvidia-346
  
    Available instances: 2
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-12C
    
    Description: num_heads=1, frl_config=60, framebuffer=12288M, max_resolution=4096x2400, max_instance=2
    
  nvidia-347
  
    Available instances: 1
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-24C
    
    Description: num_heads=1, frl_config=60, framebuffer=24576M, max_resolution=4096x2400, max_instance=1
    
  nvidia-435
  
    Available instances: 24
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-1B
    
    Description: num_heads=4, frl_config=45, framebuffer=1024M, max_resolution=5120x2880, max_instance=24
    
  nvidia-436
  
    Available instances: 12
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-2B
    
    Description: num_heads=4, frl_config=45, framebuffer=2048M, max_resolution=5120x2880, max_instance=12
    
  nvidia-437
  
    Available instances: 24
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-1A
    
    Description: num_heads=1, frl_config=60, framebuffer=1024M, max_resolution=1280x1024, max_instance=24
    
  nvidia-438
  
    Available instances: 12
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-2A
    
    Description: num_heads=1, frl_config=60, framebuffer=2048M, max_resolution=1280x1024, max_instance=12
    
  nvidia-439
  
    Available instances: 8
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-3A
    
    Description: num_heads=1, frl_config=60, framebuffer=3072M, max_resolution=1280x1024, max_instance=8
    
  nvidia-440
  
    Available instances: 6
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-4A
    
    Description: num_heads=1, frl_config=60, framebuffer=4096M, max_resolution=1280x1024, max_instance=6
    
  nvidia-441
  
    Available instances: 4
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-6A
    
    Description: num_heads=1, frl_config=60, framebuffer=6144M, max_resolution=1280x1024, max_instance=4
    
  nvidia-442
  
    Available instances: 3
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-8A
    
    Description: num_heads=1, frl_config=60, framebuffer=8192M, max_resolution=1280x1024, max_instance=3
    
  nvidia-443
  
    Available instances: 2
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-12A
    
    Description: num_heads=1, frl_config=60, framebuffer=12288M, max_resolution=1280x1024, max_instance=2
    
  nvidia-444
  
    Available instances: 1
    
    Device API: vfio-pci
    
    Name: GRID RTX6000-24A
    
    Description: num_heads=1, frl_config=60, framebuffer=24576M, max_resolution=1280x1024, max_instance=1


[    5.670781] nvidia 0000:01:00.0: MDEV: Registered

[  113.584254]  nv_vfio_mdev_probe+0x50/0xe0 [nvidia_vgpu_vfio]



## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=akb486/vgpu&type=date&legend=top-left)](https://www.star-history.com/#akb486/vgpu&type=date&legend=top-left)
