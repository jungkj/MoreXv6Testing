# Xv6 System Calls
More Xv6 Experiments/Testing

<br/>

# Added new system call named sysinfo
That fetches and prints a variety of system information. <br/> Also added a new user space program, sysinfo, that will call sysinfo() to print out the system information.


# Kernel Backtrace
Added a backtrace() function to kernel/printf.c to show the current function call stack, a.k.a. backtrace, in the kernel.

# Process Backtrace
Added an xv6 feature to print the backtrace for a process when it encounters a processor exception (crash).
