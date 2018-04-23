1a) 
250x1024x1024 = 262 144 000 KB => 262 144 000 blocks

b)
262 144 000 entries (one entry for each block)

c)
log zur basis 2 von 262 144 000 is 27,97 so we take 28 bit 
One entry needs max. 2 addresses. 1 address has 3,5 bytes. So one entry needs 7 bytes.

d)
262 144 000 entries x 7 bytes = 1 835 008 000 bytes = 1 792 000 KB = 1750 MB = 1,71 GB


2a)
Overjump 107 834 590 bytes 

b)



3)
32 bit are 4 byte.
1024 addresses for 4KB.
256 addresses for 1KB.

Double indirect: 	
1024x1024x4 = 4 194 304 KB = 4096 MB = 4 GB.
256x256x1 = 65 536 KB = 64 MB.

4)
512 B -> 128 addresses.
1024 B -> 256 addresses.

128x128x128x512 = 1 073 741 824 B = 1 048 576 KB = 1024 MB = 1 GB.
256x256x256x1024 = 1 717 986 918 B = 16 777 216 KB = 16 384 MB = 16 GB.

You will need 1024 bytes in both cases. Nothing would change.
