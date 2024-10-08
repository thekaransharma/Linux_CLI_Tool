# Linux_CLI_Tool
# sysopctl

`sysopctl` is a custom command-line utility for managing various system resources, services, and tasks on a Linux-based operating system. It provides a set of subcommands to view system information, manage services, monitor processes, analyze logs, and more.

## Features

- **Service Management**: Start, stop, and list running services.
- **System Monitoring**: View system load averages and monitor processes in real-time.
- **Disk Usage**: Display disk usage statistics by partition.
- **Log Analysis**: Summarize and analyze recent critical system logs.
- **Backup Utility**: Backup system files to a specified directory.

## Prerequisites

- Linux-based operating system
- Bash shell (`/bin/bash`)
- Common system commands (`systemctl`, `uptime`, `df`, `top`, `journalctl`, `rsync`)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/thekaransharma/Linux_CLI_Tool.git

1. **Navigate to the Project Directory**:
   ```bash
   cd Linux_CLI_Tool

1. **Make the Script Executabl**:
   ```bash
   chmod +x sysopctl

1. **Move the Script to a Directory in Your PATH**:
   ```bash
   sudo cp sysopctl /usr/local/bin/


1. **Copy the Man Page to the Appropriate Directory**:
   ```bash
   sudo cp sysopctl.1 /usr/share/man/man1/ 


## Usage

1. **View the Man page**:
   ```bash
   man sysopctl

1. **To see the available commands and options, run:**:
   ```bash
   sysopctl --help

1. **List Running Services**:
   ```bash
   sysopctl service list

1. **Start a Service:**:
   ```bash
   sysopctl service start <service-name>
   
1. **Stop a Service:**:
   ```bash
   sysopctl service stop <service-name>

1. **View System Load:**:
   ```bash
   sysopctl system load

1. **Check Disk Usage::**:
   ```bash
   sysopctl disk usage

1. **Monitor Processes:**:
   ```bash
   sysopctl process monitor

1. **Analyze System Logs:**:
   ```bash
   sysopctl logs analyze


1. **Backup Files:**:
   ```bash
   sysopctl backup <path>
