<h2>Description</h2>

This project centers on the analysis and assessment of network security, specifically focusing on password-related vulnerabilities across various systems. Beginning with the setup of a virtual environment through the MARS platform and connecting via VPN, the project delves into password analysis on Cisco routers, Windows, and Linux systems. It entails tasks such as configuring and encrypting router passwords, using password cracking tools to assess Cisco IOS-MD5 hashes, disabling password complexity requirements in Windows, creating user accounts, and performing dictionary and brute-force attacks to assess password security. The project provides a practical hands-on approach to identifying and mitigating password vulnerabilities, enhancing overall network security.

<h2>Section 1: Connecting to MARS</h2>

1. Navigate to the MARS website for virtual desktop access.
2. Connect to the virtual private network (VPN) in MARS.
3. Start your Windows virtual machine (VM).
4. Download and launch a premade Remote Desktop Protocol (RDP) file to connect to a remote system.

<h2>Section 2: Analyzing Passwords of Devices on the Network</h2>

1. Launch Cisco Packet Tracer and add a Cisco router to the workspace.
2. Rename the router to your first name followed by "Router."
3. Take a screenshot of the router configuration.
4. Access the router's CLI tab and enter enable mode.
5. Enter global configuration mode and change the router's hostname.
6. Encrypt the router's password and save the configuration.
7. Exit the router configuration.
8. Verify the encrypted password and take a screenshot.
9. Launch the Cain password cracking tool.
10. Add Cisco IOS-MD5 Hashes to the list.
11. Manually insert the hash and perform a Dictionary Attack.
12. Add a wordlist for the attack and start the cracking process.


<h2>Section 3: Analyzing Windows Passwords</h2>

1. Open the Local Group Policy Editor.
2. Disable the "Password must meet complexity requirements" policy.
3. Add multiple user accounts using the net user command.
4. List all user accounts using the net user command.
5. Launch Cain and add LM & NTLM Hashes.
6. Import the hashes from the local system.
7. Perform a Dictionary Attack on NTLM hashes.
8. Capture the cracked passwords for some accounts.
9. Perform Brute-Force Attacks on other accounts with varying complexities.

<h2>Section 4: Analyzing Linux Passwords</h2>

1. Connect to the Kali Linux virtual machine.
2. Retrieve the Linux password from the login section.
3. Create new Linux user accounts.
4. Assign passwords to the new user accounts.
5. View the encrypted Linux password hashes.
6. Redirect the password hashes to a new file.
7. Use John the Ripper to crack the Linux password hashes.

<h2>Conclusion:</h2>

In conclusion, this lab exercise has provided me with valuable insights into password security, vulnerability assessment, and password cracking techniques. I've learned the critical importance of strong, unique passwords, secure configurations, and flexible yet effective password policies. As an aspiring analyst in the field of cybersecurity, these experiences have equipped me with the knowledge and skills needed to identify and mitigate password-related security risks effectively. I am now better prepared to contribute to the development of robust security strategies and policies, enhancing overall system security in my future endeavors.
