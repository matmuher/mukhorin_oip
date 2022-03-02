## Create SSH
To create SSH key on linux you should use next command:
`ssh-keygen -t ed25519 -C "your_email@example.com"`
Than you will be offered to enter directory, where your keys will be added
`> Enter a file in which to save the key:`
_Or you can use standard path: in this you should just press ENTER_
Than password:
`> Enter passphrase (empty for no passphrase): [Press enter]
 > Enter same passphrase again: [Press enter]`
 If you don't need any password, just press ENTER

 ## Transmit privat SSH to server
To do this you should:
1. Open directory with keys
2. Copy content of file with /'.pub/' extension
3. Open Settings > Access > SSH and GPG keys >> SSH keys > New SSH Key
4. Paste
_You are awesome!_
## To clone reprository
`git clone <SSH key of reprository>`
You can grab this key on github page of reprository