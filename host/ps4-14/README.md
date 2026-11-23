# Abo-Adam 07703911986 (web)

Kernel exploit for the PlayStation 4 on firmware **12.00, 12.02, 12.50, 12.52,
13.00, 13.02, 13.04, 13.50, 13.52, 14.00 and 14.02**, run from the console's own
browser. It leaves the kernel readable and writable, `uid 0`, `mmap` handing
out RWX and `syscall 11` as a kexec gate — so the usual payloads work as they
do after any other kernel exploit.

afterglow is not Lapse.

## You need

* PS4 on firmware 12.00, 12.02, 12.50, 12.52, 13.00, 13.02, 13.04, 13.50,
  13.52, 14.00 or 14.02, on your network
* A machine on the same network with `python3`
