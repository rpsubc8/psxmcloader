# psxmcloader
launch psexe from memory card

It is a basic functional version, not suitable for comfortable personal use. I started in 2008 to make it for my own use, but now I'm modifying it to create a PSX development environment.
<center><img src='https://github.com/rpsubc8/psxmcloader/blob/master/previews/mctool.gif'></center>

It consists of the MCTOOL (Windows), which is a .MCR file generator of the PSX cards (15 blocks of 8192 bytes), allowing 122880 - 512 EXE header bytes.

<center><img src='https://github.com/rpsubc8/psxmcloader/blob/master/previews/psxmcloader.gif'></center>
  
On the other hand there is an exe loader inside the memory card (MCLOAD). In this test, 51 KB of file are read in blocks of 2048 bytes. When it finishes, the executable is launched, which is a fire in PSX.

<center><img src='https://github.com/rpsubc8/psxmcloader/blob/master/previews/psxmcloader2.gif'></center>
