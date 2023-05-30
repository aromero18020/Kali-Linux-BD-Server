# Backdoor Server

This is a server script designed to be run on a Kali Linux machine. It listens for a backdoor connection on the target machine.

## Prerequisites

- Kali Linux machine with Python installed
- Target Machine with a backdoor exe placed.

## Usage

1. Update the IP address and port number in the script to match the Kali Linux machine's IP address and a port number of your choice:
2. Run the script on the kali linux machine: python server.py
3. The server will begin to listen for any incomming connections
4. Execute the backdoor client on the target machine and establish a connection with the server.
5. Once the connection is established, you can interact with the target machine through the server's shell. 

## Commands

The following commands can be used in the server's shell:

- `quit`: Terminate the connection with the target machine and exit the server.
- `clear`: Clear the console screen.
- `cd <directory>`: Change the current working directory on the target machine.
- `download <file_name>`: Download a file from the target machine to the server.
- `upload <file_name>`: Upload a file from the server to the target machine.


## Disclaimer:
  This script is intended for educational and testing purposes only. Unauthorized use of this script to gain unauthorized access to computer systems is illegal and prohibited. The author is not responsible for any illegal actions performed with this script.
