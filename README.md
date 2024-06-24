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
![Screenshot 2024-06-24 at 2 30 07 PM](https://github.com/ModeCyber/Password-Cracking-with-John-the-Ripper/assets/173691504/9758b497-df96-4cd9-a667-e6cf1f7c5e6b)
![Screenshot 2024-06-24 at 2 38 21 PM](https://github.com/ModeCyber/Password-Cracking-with-John-the-Ripper/assets/173691504/61ea24c4-5b57-4da4-964f-e051eb4b4d81)
![Screenshot 2024-06-24 at 2 31 17 PM](https://github.com/ModeCyber/Password-Cracking-with-John-the-Ripper/assets/173691504/5606a006-6045-44e1-abaf-b40f74e5476a)
![Screenshot 2024-06-24 at 2 35 02 PM](https://github.com/ModeCyber/Password-Cracking-with-John-the-Ripper/assets/173691504/9f0ccf47-f619-4761-991e-1a0444139700)
![Screenshot 2024-06-24 at 2 35 36 PM](https://github.com/ModeCyber/Password-Cracking-with-John-the-Ripper/assets/173691504/1a8347c5-c344-46b8-ab31-4d08b3b15a89)
![Screenshot 2024-06-24 at 2 30 31 PM](https://github.com/ModeCyber/Password-Cracking-with-John-the-Ripper/assets/173691504/c169162c-715a-4925-86c3-d4f50b5ec9a4)
![Screenshot 2024-06-24 at 2 28 29 PM](https://github.com/ModeCyber/Password-Cracking-with-John-the-Ripper/assets/173691504/9883976b-d799-4bb9-a777-dd0cd07b701c)


