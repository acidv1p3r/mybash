# Blissful Bash
A Clean and Minimal Bash Configuration

Blissful Bash is a streamlined and efficient .bashrc configuration designed for users who prefer a clean, functional, and minimal Bash experience. It includes useful aliases, custom functions, and configurations for system information, Docker, networking, and more.

Features
--------
- Convenient Aliases: Shortcuts for commonly used commands:
  - System Management: update, upgrade
  - Docker Shortcuts: dps, di, dockerclean
  - Networking Tools: myip, ports, fdns
  - File Management: ll, la, diskfree

- Prompt Customization: The prompt is configured to display the username, hostname, and current directory in color. Modify the colors or structure by editing the PS1 variable in the .bashrc.

- Docker Integration:
  - If Docker is installed, the configuration will enable Docker command autocompletions.
  - Adjust Docker aliases as needed.

System Commands
---------------
- c: Clear the terminal.
- d: Change directory (cd).
- la: List files, including hidden ones.
- ll: Detailed listing of files, including hidden files.
- upgrade: Update and upgrade the system using apt.
- update: Alias for upgrade.

Networking Commands
-------------------
- myip: Fetch your external IP address.
- pingg: Ping Google to check connectivity.
- ports: List all open ports.
- fdns: Flush the DNS cache.

Docker Commands
---------------
- dockerclean: Prune unused Docker objects (volumes, images, etc.).
- dc: Short for docker-compose.
- dps: List running Docker containers.
- di: List Docker images.

System Information
------------------
- uptime: Display system uptime in a user-friendly format.
- sysinfo: Show detailed system information using FastFetch.

Installation
------------
Before using this configuration, you will need to install the following dependencies:

1. **Oh My Posh**:
   - Follow the installation instructions for **Oh My Posh** here: https://ohmyposh.dev/docs/
   - Ensure it’s installed and configured properly to enable the shell theme features.

2. **FastFetch**:
   - Install **FastFetch** to display system information with the following command:
     ```bash
     git clone https://github.com/dylanaraps/fastfetch.git
     cd fastfetch
     make
     sudo make install
     ```
   - Alternatively, you can follow the official instructions here: https://github.com/dylanaraps/fastfetch

Once you have both dependencies installed, you can simply copy the `default.bashrc` or the text from `bashrc.txt` into your (`~/.bashrc`).

Credits
-------
- FastFetch: For fast and elegant system information display.
- Oh My Posh: For a beautiful shell theme (requires Oh My Posh installation).

License
-------
This configuration is open-source and available for personal or educational use.
