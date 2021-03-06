#sTorrent

The aim of this project is to implement a BitTorrent like file transfer application which will run on top of
UDP and will be able to simultaneously download different parts, called “chunks”, of a file from different
servers. The main focus will be to implement reliability and congestion control mechanisms to ensure
fair and efficient network utilization. A cryptographic hash of the contents will be used to identify the chunk.
At a later stage, we also intend to implement smart optimizations to get the best possible transfer time. If time permits,
we hope to build and implement a 0MQ (messaging library that helps to design a complex communication system) bridge
using our transport protocol and evaluate performance against real TCP. 
