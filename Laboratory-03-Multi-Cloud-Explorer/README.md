# Laboratory 03 – Multi-Cloud Explorer

## Checkpoint 7 – Linux Investigation

For this checkpoint, I used KillerCoda to investigate a Linux environment. I used basic Linux commands to identify the operating system, CPU, memory, and available disk space.

## Linux System Information

### Operating System

Command used:

```bash
cat /etc/os-release
```

The Linux environment is running **Ubuntu 24.04.4 LTS (Noble Numbat)** with an **x86_64** architecture.

### CPU Information

Command used:

```bash
lscpu
```

The system has **1 CPU** and **1 CPU core**. The processor is an **Intel Xeon E312xx (Sandy Bridge)**, and the system is running on a KVM virtualized environment.

### Memory

Command used:

```bash
free -h
```

The system has **1.9 GiB of total memory**. At the time of checking, about **417 MiB was being used**, while approximately **1.5 GiB was available**.

### Disk Space

Command used:

```bash
df -h /
```

The root filesystem has **19 GB of total disk space**. About **5.4 GB is currently used**, leaving approximately **13 GB available**. The disk is currently at **30% usage**.

## Cloud Hosting Options

If this Linux server were migrated to the cloud, it could be hosted using virtual machine services from AWS, Microsoft Azure, or Google Cloud.

### AWS

The Linux server could be hosted using **Amazon EC2**. EC2 provides virtual servers that can run Linux operating systems, and the resources can be selected based on the workload requirements.

### Microsoft Azure

The server could be hosted using **Azure Virtual Machines**. Azure Virtual Machines supports Linux operating systems and provides different virtual machine sizes based on CPU, memory, and storage requirements.

### Google Cloud

The server could be hosted using **Google Compute Engine**. Compute Engine provides configurable virtual machines that can run Linux and can be selected based on the required CPU, memory, and storage.

## Cloud Service Comparison

| Cloud Provider      | Service That Could Host the Linux Server |
| ------------------- | ---------------------------------------- |
| **AWS**             | Amazon EC2                               |
| **Microsoft Azure** | Azure Virtual Machines                   |
| **Google Cloud**    | Compute Engine                           |

## Evidence

The screenshots below show the Linux commands and their outputs collected from the KillerCoda environment.

### Operating System

![Linux Operating System](linux-os.png)

### CPU Information

![CPU Information](linux-cpu.png)

### Memory

![Memory Information](linux-memory.png)

### Disk Space

![Disk Space](linux-disk.png)
