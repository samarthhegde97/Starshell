# ==================================================
# STARSHELL // Ethic // CONSOLE v1.0
# ==================================================

# [!WARNING]
This is a legit hacking tool. Doing illegal activity will be captured.
Starshell is designed for ethical security auditing and educational research. The developer assumes no responsibility for misuse. Ensure you have explicit written permission before testing any network or system.

# 📖 About Starshell
Starshell is a modular command-line framework that serves as an all-in-one hub for security operations. It bridges the gap between Windows and Linux, allowing operators to conduct professional-grade network diagnostics and security auditing directly from a unified interface.

# Key Features
Operator Session Management: Tracks activity and session data via a secure local database.

Hybrid Bridge Architecture: Integrates with WSL to provide native Linux execution on Windows hosts.

Real-time Telemetry: Integrated network and hardware diagnostics.

Toolchain Auditing: Automated verification of essential ethical hacking utilities.

# 🛠️ Setup & Initialization
Follow these steps exactly in your PowerShell (Run as Administrator):
# 1. Enable core virtualization features
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

# 2. RESTART YOUR COMPUTER NOW BEFORE PROCEEDING

# 🚀 How to Start Ethical Auditing
Once you launch Starshell_v1.exe, follow these steps to begin:

Authenticate: Create your operator profile when prompted. This maintains your logs and history.

Launch Kernel: Type kali to drop into your Linux environment.

Audit Tools: Type audit to ensure essential tools like nmap and sqlmap are ready.

Information Gathering: Use the built-in networking utilities to probe your own internal network.

Example (Passive Recon): dig target-domain.com

Example (Network Mapping): nmap -v 127.0.0.1

# 💻 Operational Commands Reference
# Directive--------------- Function
1. sysinfo------------------	Displays host ID, local IP, and kernel architecture.
2. kali-----------------------Switches the terminal session to the Linux subsystem.
3. audit-----------------------Runs a health check on your toolset.
4. profile---------------------Views your operator session metadata.
5. clear------------------------Flushes console output.
6. exit--------------------------Closes the framework and saves logs.
