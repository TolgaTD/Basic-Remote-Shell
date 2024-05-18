# Basic Remote Shell

This repository contains a simple remote shell tool written in Go. The tool listens for incoming TCP connections and provides an interactive bash shell to the connected client.

## Features
- Listens for incoming TCP connections on a specified port.
- Provides an interactive bash shell to the connected client.
- Handles each connection in a separate goroutine for concurrent processing.

## Prerequisites
- Go 1.16 or later

## How to Run
1. Clone the repository:

    git clone https://github.com/yourusername/Basic-Remote-Shell.git
    cd Basic-Remote-Shell


2. Build the project:

    go build -o remoteshell main.go


3. Run the executable:

    ./remoteshell


4. Connect to the remote shell from another terminal or system using:

    nc <server_ip> 20089


## Important Notes
- This tool is intended for educational purposes only. Use it responsibly.
- Ensure you have proper authorization before using this tool on any system.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
