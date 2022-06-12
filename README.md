# Description
A virtual machine that can run programs in assembly language.
The virtual machine simulates a fictional computer called LC-3.
It has a simplified instruction set compared to x86, but contains all the basic ideas used in modern processors.


# Running

### Download [2028](https://github.com/rpendleton/lc3-2048) or [Rogue](https://github.com/justinmeiners/lc3-rogue) obj file.

### Compile the VM: 
`
$ gcc lc3.c -o lc3-vm
`
### Run the VM with the .obj file as an argument:
`
$ ./lc3-vm <path to the file>
`

# Sources
[Read tutorial here](https://www.jmeiners.com/lc3-vm/#b/lc3.c:867)
