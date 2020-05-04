# CCPregen

[![Build Status](https://jenkins.daporkchop.net/job/Minecraft/job/CCPregen/job/master/badge/icon)](https://jenkins.daporkchop.net/job/Minecraft/job/CCPregen/job/master/)


### Usage

Note that all coordinates listed below are given in blocks, not cubes. Coordinate conversion is handled automatically.

CCPregen is pretty simple to use. It adds a single command, unimaginatively named `/ccpregen`.  
To pregenerate a 500³ block cube starting at (0,0,0):  
`/ccpregen 0 0 0 500 500 500`

To pregenerate a 300 block wide+tall, 1000 block long tunnel in the nether:  
`/ccpregen -150 0 0 149 300 1000 -1`
