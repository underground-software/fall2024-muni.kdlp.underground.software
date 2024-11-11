# MUNI FI Kernel Development Learning Pipeline Course Fall 2024 Information

# Course Description

Linux is the most widely used operating system in the world. The core software component of the Linux operating system is the kernel. A couple of its roles include managing hardware interactions, virtualizing system resources, and enforcing security constraints. In effect, Linux kernel powers almost all of the world’s top supercomputers, android phones, and an innumerable variety of other computers. This course will introduce students to Linux kernel development by focusing on device driver development. This will give students hands-on experience working with internal Linux kernel APIs and provide an overview of some of the core features and components of the kernel. Gaining an understanding of the inner workings of the operating system and how to make changes to it will give students an invaluable perspective on how their computers work behind the scenes that will reveal a new layer of understanding to apply to any future software engineering practice.

# Lecture Time
-   Starting Sep 16, 2024
-   Mondays 14pm-16pm CET

# Teachers
- Carlos Maiolino <cem\<at>maiolino.dev>
- Vratislav Bendel <vbendel\<at>redhat.com>
- Radomir Vrbovsky <rvrbovsk\<at>redhat.com>

# Lecture Room
- FI MUNI, Building S, [Room S505](https://is.muni.cz/kontakty/mistnost?lang=en;id=12880) (Fifth floor)

# Prerequisites
-   English language
-   C language knowledge
-   Basic knowledge about operating systems in general
-   Practical skills in Linux operating system (e.g. Fedora, Debian, Slackware)
-   Basic git
-   Own computer, preferably a laptop with x86 architecture

# Course enrollment
-   KDLP is taught under [PB173 Domain specific development](https://is.muni.cz/course/fi/podzim2024/PB173?lang=en)
-   The reward for passing the course is 3 credits.

# Language of Instruction
-   English

# Objectives
-   Introduce students to the Linux Kernel development workflow, show them how to create and send kernel modifications to mailing lists
-   Excite students about the wonderful world of Linux kernel community
-   Expose students to major kernel subsystems


# Syllabus
-   Introduction and development environment setup
-   General overview of core kernel concepts
-   PC and x86 architecture
-   Process management
-   Synchronization primitives
-   Memory management
-   Storage and filesystems
-   Networking stack
-   Device drivers
-   Kernel Debugging methods
-   GPG signing party

# Teaching Methods
-   In-person lectures
-   Homework assignments

# Assessment Methods
-   Each assignment is assigned a specific number of points based on its difficulty or importance. These points add up to a maximum of 100.
-   To pass the course, students need to accumulate at least 65 points across all assignments.

# Course Schedule

| ID  |         Date | Lesson                                                                                                                       | Presenter                        |
|-----|-------------:|------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| 1.  | Sep 23, 2024 | [Introduction](/slides/L01_Introduction.pdf), [Development environment setup](/slides/L01_Development-environment-setup.pdf) | Izabela, Carlos, Rado, Vratislav |
| 2.  | Sep 30, 2024 | [Basic intro to Linux Kernel](/slides/L02_Basic-intro-to-Linux-Kernel.pdf)                                                   | Vratislav                        |
| 3.  |  Oct 7, 2024 | [PC and the x86](/slides/L03_PC_and_the_x86.pdf)                                                                             | Rado                             |
| 4.  | Oct 14, 2024 | [Process management](/slides/L04_Process_Management.pdf)                                                                     | Rado                             |
| 5.  | Oct 21, 2024 | [Synchronization primitives](/slides/L05_Synchronization.pdf)                                                                | Carlos                           |
| 6.  |  Nov 4, 2024 | [Memory Management](/slides/L06_MemoryManagement.pdf)                                                                        | Carlos                           |
| 7.  | Nov 11, 2024 | [Filesystems](/slides/L07_Filesystems.pdf)                                                                                   | Carlos                           |
| 8.  | Nov 18, 2024 | Networking stack                                                                                                             | Jirka                            |
| 9.  | Nov 25, 2024 | Device drivers and Linux Device Model                                                                                        | Michal, Izabela                  |
| 10. |  Dec 2, 2024 | Kernel Debugging 1                                                                                                           | Vratislav                        |
| 11. |  Dec 9, 2024 | Kernel Debugging 2                                                                                                           | Vratislav                        |
| 12. | Dec 16, 2024 | GPG signing party!                                                                                                           | Izabela, Carlos, Rado, Vratislav |

# Assignments

- Use your \<login>\<at>fi.muni.cz emails to send the assignments
- Use the mailing list <kdlp-brno-assignments\<at>redhat.com> to send the assignments

| ID | Description                                                                                         | Max points | Due date     |
|----|-----------------------------------------------------------------------------------------------------|------------|--------------|
| 1. | [Compile Smallest Custom Kernel](/assignments/A01_Custom_Kernel.md)                                 | 10         | Oct 6, 2024  |
| 2. | [Custom Syscall](/assignments/A02_Custom_Syscall.md)                                                | 20         | Oct 27, 2024 |
| 3. | [Implement operations within the toyfs filesystem](/assignments/A03_filesystem_ops.odt)             | 25         | Nov 24, 2024 |
| 4. | [Implement locking on the toyfs filesystem](/assignments/A04_locking.odt)                           | 10         | Dec 8, 2024  |
| 5. | [Change inode management to use slab cache](/assignments/A05_slab_cache.odt)                        | 15         | Dec 8, 2024  |
| 6. | [Rewrite the metadata read/write paths to use proper endianess](/assignments/A06_fs_endianness.odt) | 10         | Dec 8, 2024  |
| 7. | Use `crash` tool to analyze a panicking kernel                                                      | 10         | Dec 22, 2024 |
