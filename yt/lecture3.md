# lecture 3

***Process***
* Process is a sequence of instructions executed in a pre-defined order.
* Any program that is executed is termed as process.
* Process can change their states as they execute and can be either new, ready, running, waiting or terminated.
* A process in OS is managed by *Process Control Block (PCB)*.
* Program under execution is known as process.

***Thread***
* Light weight process
* Sub-tasks of a process
* Each thread belongs to exactly one process.
* In a multi-threaded os, a process can consist of many threads.
* Threads can be effective only if the CPU is more than one otherwise the threads have to context switch for that single CPU.

### Multi-Tasking vs Multi-Threading
<table>
    <tr>
        <th>Multi-tasking</th>
        <th>Multi-threading</th>
    </tr>
    <tr>
        <td>More than one process.</td>
        <td>More than one thread.</td>
    </tr>
    <tr>
        <td>Isolation and Memory protection</td>
        <td>No isolation and memory protection</td>
    </tr>
    <tr>
        <td>Process scheduled</td>
        <td>Threads scheduled</td>
    </tr>
    <tr>
        <td>No. of CPU is 1</td>
        <td>one or more than one CPU</td>
    </tr>
</table>










