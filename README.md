# password-manager
NB//: THIS IS NOT A SAFE APPLICATION TO STORE YOUR PASSWORDS!!!!
## Hash Verification
 To authenticate the user, they are prompted to create a master password (that is also used to decrypt data) which is then stored using a SHA256 Hash Function and is verified at login. Whenever the user is prompted to verify their master password, the password they enter is compared to the hash of the stored master password and access if granted if the two hashes match.
 ## Changelog
Python-Password-Manager has been completely rewritten to be more object-oriented and abstract even more of the methods found in the original version.
# Vulnerability
As mentioned at the top, this was made as a project and not intended for actual use. Below I demonstrate what any expert hacker can accomplish by exploiting a vulnerability. Just kidding, anyone can do this. Since the files are stored locally, they can easily be deleted without needing to enter any credentials and consequently all stored passwords are gone along with other data.