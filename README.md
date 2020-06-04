The instruction leave out that you must open port 8080. I did not restrict port 22 to my IP because I use a YubiKey, and since my VM only accepts a private key (not a password) I am not concerned about brute force attacks. The following step is missing from the instructions.
MISSING: ubuntu@ip-172-31-31-235:~$ sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 9B7D32F2D50582E6

In step C, I reinstalled Jenkins on a fresh server. I had been working along during the lesson and this is the only part that I could not use the virtual machine that I had been using for.
