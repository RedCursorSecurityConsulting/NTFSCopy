# NTFSCopy
This project is based on https://github.com/LordMike/NtfsLib. I have made the NTFSCopy tool usable with execute-assembly in Cobalt Strike. This was done using ILMerge to make a single executable without any dependencies, and removing the fancy colored progress bar which Cobalt Strike couldn't handle (seems like Console.Seek() was throwing an exception).

# Use
Clone the repository and build the NTFSCopy project within the solution.
![example](https://github.com/RedCursorSecurityConsulting/NTFSCopy/blob/master/NTFSCopy_use.jpg?raw=true)

# License
This project is under the MIT license. As such you are allowed to modify and use the code, but are required to attribute me when using it.

