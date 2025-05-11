# sysinternals-bginfo

This repository contains Sysinternals BgInfo configuration and deployment scripts for Windows operating systems.

## Features

- Custom BgInfo configuration for Windows 2016, 2019, and 10
- PowerShell deployment script
- Custom background information display

## Project Structure

- `logonbgi.zip`: BgInfo configuration file
- `deploy-bginfo.ps1`: PowerShell script for deploying BgInfo

## Prerequisites

- Windows 2016, 2019, or 10 operating system
- PowerShell 5.1 or later
- Sysinternals BgInfo tool installed
- Administrative privileges

## Usage

1. Download and install Sysinternals BgInfo from Microsoft's website
2. Copy the repository contents to your deployment location
3. Run the deployment script with administrative privileges:
   ```powershell
   .\deploy-bginfo.ps1
   ```

The script will:
- Configure BgInfo with the custom settings
- Set up automatic startup
- Apply the configuration to the current system

## Configuration

The BgInfo configuration includes:
- System information
- Network details
- Uptime
- IP addresses
- Computer name
- Operating system version

## Security

- The deployment script requires administrative privileges
- Review the script contents before execution
- Ensure proper backup of existing BgInfo configurations

## License

This project is licensed under the terms of the LICENSE file.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
