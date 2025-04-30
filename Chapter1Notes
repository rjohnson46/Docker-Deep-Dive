# Containers from 30,000 Feet

Containers are definitely a game-changer in modern computing.

## The Evolution of Virtualization

- **Underutilized Servers**: Traditionally, servers operated at only 5-10% capacity because IT departments overspent on infrastructure to support their applications.
- **Rise of Virtual Machines (VMs)**:
  - Introduced by VMWare, VMs allow multiple servers to run within a single physical server.
  - VMs predate containers and revolutionized resource utilization, but they require their own operating systems. This increases CPU, RAM, and resource consumption, along with the need for patching, monitoring, and often licensing.

- **Limitations of VMs**:
  - Although easier to migrate across hypervisors and cloud platforms, VMs are resource-heavy and can be slow to boot.
  *(Personal note: While some claim VMs aren't portable, I’ve found moving VMs straightforward.)*

## The Container Revolution

- **Why Containers?**:
  - Unlike VMs, containers share a single host operating system, minimizing resource usage.
  - They are fast to start, ultra-portable, and easy to move between environments like local machines, cloud, and even VMs.

- **Origins and Simplicity**:
  - Containers began in the Linux world, developed over time by various contributors. Early implementations were complex.
  - Docker Inc. simplified containers, making them accessible to everyone.

## Similar Technologies

- Before Docker, there were other OS virtualization solutions like:
  - IBM's System/360 on the mainframe.
  - BSD Jails and Solaris Zones, known Unix-based container technologies.
  *(Direct quote: "This is a direct quote straight out the book.")*

## Containers on Different Platforms

- **Windows Containers**:
  - Microsoft introduced Windows Containers on Windows 10 and Windows Server 2016 in collaboration with Docker Inc.
- **Cross-Platform Considerations**:
  - Windows containers cannot run on Linux hosts, and Linux containers cannot run on Windows hosts (with some exceptions).
  - On Windows, Linux containers run using Docker Desktop with two modes: "Windows containers" and "Linux containers."
    - The newer **WSL** mode offers better performance and compatibility, making it the strategic choice over Hyper-V VMs.
- **Mac Containers**:
  - While there are no native Mac containers, Linux containers can run on Mac via Docker Desktop.
