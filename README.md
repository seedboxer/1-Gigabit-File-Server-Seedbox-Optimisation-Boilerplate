# 🚀 1-Gigabit File Server & Seedbox Optimization Boilerplate

This project provides an optimized configuration for running a high-performance file server and seedbox on a 1-Gigabit network. It includes system tweaks, networking optimizations, and application settings to maximize speed, efficiency, and reliability.

🔥 **Why Use This?**

* **Optimized for Gigabit Speeds:** Fine-tuned configurations ensure you get the most out of your 1Gbps connection.
* **Low System Overhead:** Reduces CPU & RAM usage for efficient operation.
* **Network Enhancements:** TCP/IP stack tuning for high-speed transfers.
* **Disk I/O Optimization:** Configurations to handle high read/write speeds.
* **Seeder-Focused:** Ideal for running a seedbox with minimal performance impact.
* **Easy Deployment:** Pre-configured settings for quick and hassle-free setup.
* **ruTorrent Optimization:** Includes optimized settings to make ruTorrent super fast.

⚡ **Performance Improvements**

* **Kernel Tweaks:** Adjusts `sysctl` settings for optimal TCP and UDP performance.
* **Disk Optimization:** Filesystem and I/O scheduler tweaks to maximize throughput.
* **Network Enhancements:** Reduces latency and improves concurrent connections.
* **Torrent Client Optimization:** Configurations to handle high peer connections smoothly.
* **RAM Caching:** Efficient use of memory for disk caching to reduce wear on SSDs/HDDs.
* **Security Hardening:** Ensures secure remote access and data protection.

🛠️ **Quick Setup**

1. Clone the repository:

```bash
git clone [https://github.com/seedboxer/1-Gigabit-File-Server-Seedbox-Optimisation-Boilerplate.git](https://github.com/seedboxer/1-Gigabit-File-Server-Seedbox-Optimisation-Boilerplate.git)
cd 1-Gigabit-File-Server-Seedbox-Optimisation-Boilerplate

mv -f sysctl.conf /etc/

sysctl -P or reboot.

Alternatively just copy past systcl into your /etc/sysctl.conf using Nano, vim etc.
