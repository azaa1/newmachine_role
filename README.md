# newmachine_role
This role:
1. Takes input from user for : 
      - which host to run the role on 
      - hostname for remote host
      - user to be added on the remote host
      - password for the new-user  (for security reasons hashed password is recommended)
      - IP/CIDR block to be ignored on Fail2ban configuration file
      - Nagios Server's IP address for NRPE configuration
      
2. Adds a user to remote hosts
3. Changes hostname on remote hosts
4. Installs Apache
5. Installs and Configures Fail2ban
6. Installs and Configures NRPE
