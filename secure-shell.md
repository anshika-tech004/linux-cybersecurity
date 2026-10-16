## What is SSH?
- SSH stands for Secure Shell
- It is a network protocol used to securely access and manage a remote computer over an unsecured network.
# Usage 
It is commonly used by Linux administrators and cybersecurity professionals to:
- Access remote Linux servers.
- Execute commands on remote systems.
- Manage servers securely.
- Transfer files securely using related tools such as SCP and SFTP.
- Perform remote system administration and troubleshooting.

# Difference between SSH Client and SSH Server
|Basis|	SSH Client|	SSH Server|
|----|----|----|
|Meaning|	Software used to connect to another computer|	Software that accepts SSH connections|
|Purpose|	Initiates the connection|	Receives and manages the connection|
|Role|	Client/user side|	Remote computer side|
|Common command| ssh command	|sshd service|
|Default port	|Connects to port 22 by default|	Listens on port 22 by default|
|Example|	Your Windows PC connecting to Ubuntu|	Ubuntu computer accepting your connection|

# Remote Login Using SSH
- Remote login means accessing another computer through a network instead of physically using that computer.
- SSH allows an authorized user to log in to a remote Linux machine and execute commands through a terminal.

   # General SSH Command
      ssh username@server_ip
      Here:
        - "ssh" starts the SSH client.
        - "username" is the account on the remote machine.
        - "server_ip" is the IP address or hostname of the remote machine.
# SSH Authentication
- SSH authentication is the process of verifying the identity of a user who wants to access a remote system.

   # Authentication methods:
      - Two common authentication methods are:
      - A. Password Authentication- The user authenticates using the password associated with their remote account.
             - Security considerations:
                   - Use strong, unique passwords.
                   - Avoid sharing passwords.
                   - Follow the server's authentication and access policies.
      - B. Public-Key Authentication- Public-key authentication uses a cryptographic key pair:
            - Private key: Kept secret by the user.
            - Public key: Placed on the remote server, usually in the user's "~/.ssh/authorized_keys" file.

  # Basic SSH Commands
  




