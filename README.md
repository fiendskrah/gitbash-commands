# This is a reference sheet of commands to use in gitbash

`pwd` - present working directory <br>
returns the current folder open in the shell

`cd` - change directory <br>
moves the pwd to the home directory

`cd` - change directory (specified) <br>
moves the pwd to the specified directory

`ls` - list <br>
lists the files/folders in the directory

`ls -al` - list (all) <br>
lists all files/folders in the directory, including hidden files

`clear` - clear <br>
clears the shell

`mkdir` - make directory <br>
makes a new folder

`history` <br>
returns the history of commands entered durring current session <br>
`!(numerical value associated with history command)` <br>
->runs associated command


# `git` 

# Check RAM details
`wmic MemoryChip get BankLabel, Capacity, MemoryType, TypeDetail, Speed, Tag`<br>
returns details about RAM cards. 'MemoryType' contains data on type (DDR2, DDR3, etc).
Corresponding MemoryType codes

0 = Unknown (May be DDR4, unknown to WMIC)
1 = Other
2 = DRAM
3 = Synchronous DRAM
4 = Cache DRAM
5 = EDO
6 = EDRAM
7 = VRAM
8 = SRAM
9 = RAM
10 = ROM
11 = Flash
12 = EEPROM
13 = FEPROM
14 = EPROM
15 = CDRAM
16 = 3DRAM
17 = SDRAM
18 = SGRAM
19 = RDRAM
20 = DDR
21 = DDR2
22 = DDR2 FB-DIMM
24 = DDR3—May not be available; see note above.
25 = FBD2


