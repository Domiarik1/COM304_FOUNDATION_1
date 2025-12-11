[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 7

## Topics covered
*What topics were covered in this session*

Looking at the wider structure and utilities of operating systems and in particular Linux.

## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

An Operating system is an interface between users and the hardware of a computer system. It is a system software that is viewed as an organized collection of software consisting of procedures and functions, providing an environment for the execution of programs. The operating system manages system software and computer hardware resources. It allows computing resources to be used in an efficient way. Programs interact with computer hardware with the help of operating system. A user can interact with the operating system by making system calls or using OS commands.

Main memory is a flexible and volatile type of storage device. It is a large sequence of bytes and addresses used to store volatile data. Main memory is also called Random Access Memory (RAM), which is the fastest computer storage available on PCs. It is costly and low in terms of storage as compared to secondary storage devices. Whenever computer programs are executed, it is temporarily stored in the main memory for execution. Later, the user can permanently store the data or program in the secondary storage device. The components of an operating system work together to make a computer system function easily. Each component, from process management to security, plays a unique role in handling tasks, managing resources, and ensuring data safety. By coordinating these functions, the operating system provides a stable and efficient environment for users and applications.

(https://www.geeksforgeeks.org/operating-systems/components-of-operating-system/)

## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

Especially Linux it reveals how a cohesive, flexible environment is built from layered components and powerful tools. At the core, Linux follows a modular kernel design, where essential functions such as process scheduling, memory management, networking, and device control operate through tightly integrated yet independently loadable modules. This structure allows the system to remain efficient while supporting a vast range of hardware. Looking beyond kernel, the results show how Linux organizes its ecosystem through a well defined directory hierarchy, with configuration, usr for shared utilities, var for dynamic data, and proc and sys as virtual file systems exposing kernel information. Analyzing these components reaveled how the OS communicate internally and how administrators can monitor system behaviour in real time.

Exploring Linux utilities highlights the strengths of its command line environment. Tools such as ps, top and systemctl demonstrates process and service management; df, du and mount illustrate file system handling and networking utilities like; ip, ss, and ping show how connectivity is tracked and controlled. Package managers such as APT, DNF, or Pacman reaveal structured software distribution and dependency management. Personally, the results shows how Linux's broader strcuture and utilities show a transparent, customizable, and highly scalable operating system designed for both control and reliability.  

## Summary of learning
*What did you learn through these exercises*

Learned it reveals how the complex systems are organised, managed and controlled. One of the first thing i learned is the layered design of an operating system, where the kernel, system libraries, user utilities, and applications each play distinct roles. Linux in particular demonstrates a modular kernel structure, allowing components such as device drivers, networking stacks, and file system support to be loaded and unloaded dynamically. I also learned how Linux organizes its environment through the Filesystem hierarchy standard, which clearly separates configuration files, system binaries, logs, user files, and virtual system information, this helped me understand how the OS maintains order, security and consistency.
