1. What is an Operating System?
Advantages:
- Better isolation between services.
- Improved reliability.
- Easier maintenance.
- Smaller kernel size.
Disadvantages:
- Communication between components can introduce performance overhead.
- More complex communication design.
Examples: MINIX 3, QNX.
Monolithic vs Microkernel







wasilzafar.com


Feature	Monolithic	Microkernel
Kernel size	Large	Small
Services	Most services in kernel space	Minimal services in kernel space
Performance	Generally faster	Can have communication overhead
Reliability	Less isolation	Better isolation
Maintenance	More difficult	Easier to maintain
Example	Linux	MINIX 3

8. What Does a Kernel Do?
The kernel performs several important functions:
1. Process Management: Creates, schedules and terminates processes.
2. Memory Management: Allocates and deallocates RAM to programs.
3. Device Management: Controls hardware devices through device drivers.
4. CPU Scheduling: Decides which process gets CPU time.
5. File System Management: Provides access to file-system operations.
6. Security and Protection: Controls access to system resources.
7. System Calls: Provides an interface through which applications request operating system services.
8. Interrupt Handling: Responds to signals from hardware and software that require immediate attention.
9. Kernel Space and User Space
An operating system divides its execution environment into two major areas: kernel space and user space.







samist.medium.com


A. Kernel Space
Kernel space is the protected memory area where the kernel executes.

Characteristics:
- Has privileged access to hardware.
- Manages CPU and memory.
- Controls device drivers.
- Handles system calls and interrupts.
- Can access critical system resources.
B. User Space
User space is the memory area where normal applications and user programs execute.

Examples:
- Google Chrome
- Microsoft Word
- VLC Media Player
- Games
- Text editors
Characteristics:
- Applications have restricted access to hardware.
- Programs cannot directly access protected kernel memory.
- Applications request operating system services through system calls.
- Provides isolation between applications.
Difference Between Kernel Space and User Space
Kernel Space	User Space
Runs the kernel	Runs applications
Privileged mode	Restricted mode
Direct hardware access	Access through OS services
Manages system resources	Uses system resources
Higher level of system privileges	Limited privileges

Example of how they work together:

Suppose you open a file using a text editor.
1. You click the Open button.
2. The application requests the file from the operating system.
3. A system call transfers the request to the kernel.
4. The kernel communicates with the storage device.
5. The file data is returned to the application.
6. The application displays the file on your screen.
10. Operating System Installation Steps
Operating system installation is the process of installing system software on a computer so that it can manage hardware and run applications.

Here are the general steps for installing Windows using a bootable USB drive.




















4












