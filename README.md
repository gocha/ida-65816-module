SNES 65816 Processor Plugin for IDA
===================================

This is a IDA processor plugin module for SNES 65816 CPU.

**NOTICE**:
The 65816 processor plugin was initially forked from [IDA SDK 6.8](https://www.hex-rays.com/products/ida/support/download.shtml),
published by [Hex-Rays](https://www.hex-rays.com/).

How to compile
--------------

1. Download and install [IDA SDK](https://www.hex-rays.com/products/ida/support/download.shtml) (expected version is IDA SDK 6.9)
2. Clone the repository into $(IDASDK)/module/65816
2. Clone the [snes](https://bitbucket.org/gochaism/ida-snes-ldr) loader repository for addr.cpp and its dependency
3. Compile the project with [Visual Studio](https://www.visualstudio.com/downloads/download-visual-studio-vs.aspx)

Read official development guides for more details of generic IDA development.
