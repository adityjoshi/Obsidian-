
We know how a **Process** moves using schedulers, from the hard disk to RAM and then to the CPU. But what actually is a Process ?

A process is basically a program in execution. It is more than the program code, which is sometimes known as the **text section**. To put it in simple terms, we write our computer programs in text files, which, when run, turn into processes that carry out all the tasks the programs specify.

A process generally also includes the process stack, which contains temporary data (such as function parameters, return addresses, and local variables), and a data section, which contains global variables. A process may also include a heap, which is memory that is dynamically allocated during process run time.

A program for which a process is created is called **Passive Entity**. A file containing a list of instructions stored on disk (often called an executable file). In contrast, a process is an **Active Entity**, with a program counter specifying the next instruction to execute and a set of associated resources.

 A process itself can be an execution environment for other code.The Java programming environment provides a good example. In most circumstances, an executable Java program is executed within the Java virtual machine (JVM). The JVM executes as a process that interprets the loaded Java code and takes actions (via native machine instructions) on behalf of that code.
 For example, to run the compiled Java program Program.class, we would enter java Program. The command java runs the JVM as an ordinary process, which in turns executes the Java program Program in the virtual machine. The concept is the same as simulation, except that the code, instead of being written for a different instruction set, is written in the Java language.

I keep on sharing my learning and knowledge, so if it sparks your curiosity, then follow along. And as always, it will be no-fluff; just engineering. 


A switch is a networking device used to connect multiple devices within a local area network.
It works on Data Link layer(Layer 2). It is responsible for filtering and forwarding the packets between LAN segments based on MAC Address. Here's a breakdown of how switch works:

Broadcast Address Handling: A switch will check if it has the broadcast address of host in the table if not it will register it.Then it will check if it has the MAC address of the destination. If not it will flood frame.

Forwarding: It happens when the switch has entry for the frame's destination MAC address. That frame will be forwarded only out the port indicated by the MAC table.

Flooding: It occurs when the switch has no entry for the frame's destination MAC address in its MAC table. With flooding, the frame is sent out to the every port except the port the frame come in.

Filtering: It happens when the source and destination MAC address are located off the same port. The frame is simply dropped. 

These techniques allow a switch to efficiently manage traffic within a local area network by selectively forwarding packets based on MAC addresses, reducing unnecessary network congestion.

I keep on sharing my learning and knowledge, so if it sparks your curiosity, then follow along. And as always, it will be no-fluff; just engineering. 