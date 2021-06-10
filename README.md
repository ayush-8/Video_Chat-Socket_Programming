# Video_Chat-Socket_Programming

A Video Chat program without audio created using Socket Programming in Python. Open-CV library is used along with Multi-Threading so that sender and receiver programs work simultaneously.

Care must be taken while working with files. Both files must be loaded in the Both Server and Client, as each will work as both sender and receiver.

An IP and port is required for a system to act as server to which the client connects for transfer of packets containing array bytes data for images.

Files in System A:
sender file must contain IP and port of System A
receiver file must contain IP and port of System B.


Files in System B:
sender file must contain IP and port of System B
receiver file must contain IP and port of System A.
