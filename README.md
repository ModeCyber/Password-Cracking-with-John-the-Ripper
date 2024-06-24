Password Cracking with John the Ripper
Introduction
This project demonstrates the use of John the Ripper, a powerful password cracking tool, to understand the importance of strong passwords. 
By generating password hashes and attempting to crack them, we highlight the vulnerabilities associated with weak passwords and emphasize best practices for password security.

Tools needed
A computer with internet access (I used Linux)
Install John the Ripper
Install mkpasswd
Rockyou.txt list (Downloaded)

Since I used Linux, you can typically install it via package managers like apt or yum.
sudo apt-get install john
sudo apt-get install whois (mkpasswd)
Create a Sample Password File with text editor and save as passwords.txt
Add a few sample passwords to the file, one per line. Save and close the file.

Generate Hashes using mkpasswd
Create a file named hashes.txt and add the generated hashes, one per line.
Crack Password Hashes

Run John the Ripper:
Open a terminal and navigate to the directory containing hashes.txt.

Run John the Ripper with the following command:
john hashes.txt

Monitor the Cracking Process:
View the status by running:
john --status

View Cracked Passwords:

Once the process is complete, view the cracked passwords with:
john --show hashes.txt

Findings
Highlight which passwords were easier to crack and why.

Recommendations
Use complex passwords with a mix of characters.
Avoid common words and easily guessable information.

Conclusion
Strong passwords are crucial for security. This project showed how easily weak passwords can be cracked, emphasizing the need for robust password practices.

[Password Cracking with John the Ripper.pdf](https://github.com/user-attachments/files/15960155/Password.Cracking.with.John.the.Ripper.pdf)

