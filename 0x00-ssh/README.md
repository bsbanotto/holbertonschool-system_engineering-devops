This is a README for 0x00.SSH

There are 4 mandatory tasks in this project as follows:

Task 0 - Use a private key
 - Write a bash script that uses ssh to connect to your server using the
 private key ~/.ssh/school whit the user ubuntu

Task 1 - Create an SSH key pair
 - Write a bash script that creats an RSA key pair
  - Name of the created private key must be school
  - Number of bits in the created key to be created 4096
  - The created key myst be protected by the passphrase betty

Task 2 - Client configuration file
 - Your machine has an SSH configuration file for the local SSH client,
 lets configure it to our needs so that you can connect to a server
 without typing a password. Share your SSH client configuration
 in your answer file
  - SSH client configuration must be configured to use the private key
  ~/.ssh/school
  - SSH client configuration must be configured to refuse to authenticate
  using a password

Task 3 - Let me in!
 - Now that you have successfully connected to your server, we would also
 like to joing the party.
 - Add the SSH public key below to your server so that we can connect
 using the ubuntu user
