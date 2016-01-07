# Protostar
[Protostar](https://exploit-exercises.com/protostar/) introduces basic memory corruption issues such as buffer overflows, format strings and heap exploitation under “old-style” Linux system that does not have any form of modern exploit mitigiation systems enabled.

Protostar introduces the following in a friendly way:
- Network programming
- Byte order
- Handling sockets
- Stack overflows
- Format strings
- Heap overflows

The above is introduced in a simple way, starting with simple memory corruption and modification, function redirection, and finally executing custom shellcode.

In order to make this as easy as possible to introduce Address Space Layout Randomisation and Non-Executable memory has been disabled. If you are interested in covering ASLR and NX memory, please see the [Fusion](https://exploit-exercises.com/fusion/) page.