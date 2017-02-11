# Brute-Force

Brute-Force password file generation for 16 bytes alphanumeric characters and their corresponding hashes

Part I: Brute-force attacks. (brute.c)

There is a password system you want to break into.  The system accepts hashes of alphanumeric passwords consisting of up to 16 bytes.  This C program generates hashes of all possible passwords.  That is, the program will output all passwords with corresponding hashes.  


Part II: Dictionary attacks (pass2hash.c)

This program will use a dictionary to generate passwords and hashes.  Here, I have used a small password dictionary. It would work for a much larger dictionary (logic remains the same).  This program will also display the entropy for each password it generates.
