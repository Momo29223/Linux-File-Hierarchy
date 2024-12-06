![linux-directory-structure](https://github.com/user-attachments/assets/5623da53-8511-4397-83a6-ee9aee18ba85)# Linux-File-Hierarchy
The root directory (`/`) is the top-level directory in Linux. Every file and directory starts from here. It is the beginning of the file system hierarchy.

## Important Subdirectories

1. **/bin (Binaries)** 
   Contains essential user command binaries (e.g., `ls`, `cp`, `mv`). Commands needed for basic system operation, available in single-user mode.

2. **/boot (Boot Loader Files)** 
   Contains files needed for booting the system, such as: 
   - Kernel (`vmlinuz`) 
   - Bootloader files (e.g., GRUB configurations)

3. **/dev (Device Files)** 
   Special device files representing hardware or virtual devices. 
   Examples: 
   - `/dev/sda` for hard drives 
   - `/dev/null` 
   - `/dev/tty`

4. **/etc (Configuration Files)** 
   Stores system-wide configuration files. Examples include: 
   - `/etc/passwd` 
   - `/etc/hosts`
 5. **/home (User Home Directories)** 
   Contains personal directories for users. Each user has their own directory, for example: 
   - `/home/alice` 
   - `/home/bob` 
   These directories store user-specific files, configurations, and personal data.


6. **/root (Root User Directory)** 
   This is the home directory for the root user (system administrator). It is separate from `/home` for security reasons.

7. **/run (Runtime Data)** 
   Holds temporary files that are required during the system's operation, such as process IDs, sockets, and other runtime information. Files in `/run` are usually cleared on reboot.

8. **/sbin (System Binaries)** 
   Contains essential system administration binaries, such as: 
   - `fsck` (File System Check) 
   - `ifconfig` (Interface Configuration) 
   These tools are primarily used by the root user.

9. **/tmp (Temporary Files)** 
   A location for temporary files created by the system or applications. Files stored here are often deleted upon system reboot.

10. **/usr (User Programs)** 
    Contains secondary, non-essential binaries and libraries for user applications. 
    - `/usr/bin`: Non-essential user command binaries. 
    - `/usr/sbin`: Non-essential system binaries. 
    - `/usr/local`: Locally compiled and installed programs. 
    - `/usr/share`: Shared application files such as documentation and icons.

11. **/var (Variable Files)** 
    Holds files that are expected to change frequently. Examples: 
    - `/var/log`: System log files. 
    - `/var/tmp`: Temporary files that persist after a reboot. 
    - `/var/spool`: Files waiting to be processed, such as mail or print jobs.

---
