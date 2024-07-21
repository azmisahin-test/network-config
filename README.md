# Network Configuration Repo

This repository contains Netplan configuration files used for managing static IP configurations on virtual machines and other network devices.

## Features

- Netplan configuration files
- Static IP address settings
- Simple installation and configuration

## Installation

Clone this repository:

1. Clone this repository:

   ```bash
   git clone https://github.com/azmisahin-test/network-config.git
   ```

2. Copy the configuration files to the appropriate directories:

   ```bash
   cp config/01-netcfg.yaml /etc/netplan/
   ```

3. Apply the Netplan configuration:

   ```bash
   sudo netplan apply
   ```

## Usage

- Edit the IP address and other network settings in the 01-netcfg.yaml file as needed.
- Copy the configuration file to the /etc/netplan/ directory.
- Apply the configuration using the sudo netplan apply command.

## Contributing

If you would like to contribute, please follow these steps:

1. Fork this repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Make your changes and commit them.
4. Create a pull request.

You can use the Issues page for any questions or suggestions.

## License

This project is licensed under the MIT License.
