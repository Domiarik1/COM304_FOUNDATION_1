[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 6

## Topics covered
*What topics were covered in this session*

Looking at the structure of a modern operating system.


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

A modern operating system is defined as a set of software extensions of primitive hardware, culminating in a virtual machine that serves as a high-level programming environment and manages the flow of work in a network of computers. It controls all the computer's resources and provides the base upon which application programs can be written, offering services such as interprocess communication, file and directory systems, data transfer over networks, and a command language for invoking and controlling programs. The layered architecture of a modern operating system employs information hiding, confining the details of managing a class of objects in a module with a friendly interface, which allows designers to insulate users from hardware or software changes and supports diverse environments including programming, game playing, real-time processing, office automation, and database systems.

Modern operating systems allow several people to use the same computer, permit users to control which information is shared and with whom, and can run many programs at the same time while keeping them from interfering with one another. They provide sophisticated user interfaces, Internet access, file systems, backup and archive applications, device drivers for various hardware gadgets, and a wide range of abstractions to simplify application programming. The division of labor between hardware and software layers in a modern operating system is an engineering trade-off, with factors such as cost, performance, flexibility, convenience, and usage patterns influencing decisions for each function. The operating system layer often exhibits layer bypass, hiding only a few features of the hardware layer while allowing most of the instruction repertoire of the underlying processor to pass through for use by the application layer.

(https://www.sciencedirect.com/topics/computer-science/modern-operating-system)

## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

When exploring a modern operating system, several hands-on execises help reveal its internal structure. One useful exercise is inspecting running processes using tools such as top, Task manager or Activity monitor. The results show how the OS manages multitasking by assigning CPU time, tracking memory usage, and prioritizing threads. Another exercise is examining the file system layout, including directories like, usr and proc on Unix-based systems. This reveals how configuration files, binaries, and virtual system information are organized and how the OS separates user data from system components. Also experimenting with system calls, by writing simple programs that create processes or access files provides insight into the interface between applications and the Kernel, this exercises highlight the layered architecture, security mechanisms, and resource management strategies that define modern operating system structures. Also The file system structure shows how data is organized, accessed, and protected through permissions and metadata. Observing process and thread management highlights how multitasking is archieved and how resources are distributed. The presence of device drivers demonstrates modular hardware support, while security layers including privilege separation and access control show how the OS maintains stability and protects users. 

## Summary of learning
*What did you learn through these exercises*

I gained insight into kernel architecture, including how the kernel controls hardware, schedules processes, and enforces memory protection. This helped me understand why applications cannot directly access hardware and how the OS maintains system reliability. I also learned about process and thread management, how the system creates, switches between, and terminates tasks. This revealed how multitasking works and why some programs feel faster or slower depending on scheduling and resource allocation. Exploring memory managment also taught me about virtual memory, paiging, segmentation, allocation strategies, and how the OS isolated processes to prevent crashes or security breaches. Generally i learned how complex, interconnected components work together to provide a stable, secure, and efficient computing environment. 


