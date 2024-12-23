操作系统编译后的内核源码，实现添加335号系统调用功能，仅包含更改部分内容。

335号系统调用定义更改内容在syscalls/syscall_64.tbl查看(文件虚拟机中源地址为“/usr/src/kernels/linux-4.19.325/arch/x86/entry/syscalls/syscall_64.tbl”)，

具体调用内容在kernel/sys.c文件尾部查看(文件虚拟机中源地址为“/usr/src/kernels/linux-4.19.325/kernel/sys.c”)。

