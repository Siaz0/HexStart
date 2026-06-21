HEXSTART

Lightweight terminal-based hex investigation toolkit built for Linux and iSH.

HEXSTART combines hexadecimal decoding, artifact analysis, knowledge-base matching, and investigation workflows into a single portable shell script.

Features

* Hexadecimal decoding
* Reverse hex analysis
* ASCII conversion
* Byte viewer
* Binary viewer
* Quick investigation mode
* Full AI-style investigation reports
* Knowledge Base matching
* Case Book management
* Lightweight and portable
* Linux and iSH compatible

Installation

git clone https://github.com/Siaz0/HexStart.git
cd HexStart
./hexstart

If direct execution is restricted in your environment:

sh hexstart

Example

Input:

43 41 53 45 20 23 30 30 31 0A 0A 54 61 72 67 65 74 3A 20 4F 6E 65 20 51 75 69 63 6B 20 46 69 78 0A 0A 44 61 79 20 31 3A 0A 46 6F 75 6E 64 20 62 75 67 2E 0A 0A 44 61 79 20 32 3A 0A 42 75 67 20 66 6F 75 6E 64 20 66 72 69 65 6E 64 73 2E 0A 0A 44 61 79 20 33 3A 0A 42 75 67 20 66 6F 72 6D 65 64 20 63 6F 6D 6D 75 6E 69 74 79 2E 0A 0A 44 61 79 20 34 3A 0A 50 72 6F 6A 65 63 74 20 72 65 77 72 69 74 74 65 6E 2E 0A 0A 53 74 61 74 75 73 3A 0A 43 61 73 65 20 65 73 63 61 6C 61 74 65 64 2E

Output:

CASE #100

Additional examples can be found in:

examples/sample_hex.txt

Repository Structure

HexStart/
├── LICENSE
├── README.md
├── hexstart
└── examples/
    └── sample_hex.txt

Compatibility

Tested on:

* Linux
* iSH (iOS)

License

Released under the MIT License.

Version

Current Release: v0.1.0