# password-manager
NB//: THIS IS NOT A SAFE APPLICATION TO STORE YOUR PASSWORDS!!!!
## Hash Verification
 To authenticate the user, they are prompted to create a master password (that is also used to decrypt data) which is then stored using a SHA256 Hash Function and is verified at login. Whenever the user is prompted to verify their master password, the password they enter is compared to the hash of the stored master password and access if granted if the two hashes match.
 ## Changelog
Python-Password-Manager has been completely rewritten to be more object-oriented and abstract even more of the methods found in the original version.