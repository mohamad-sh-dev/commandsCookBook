### Generate a new SSH key with email as a label 
`ssh-keygen -t ed25519 -C "your_email@example.com"`


### If ed25519 is not supported, use RSA 
` ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`


`ssh-keygen -l -f ~/.ssh/id_rsa.pub`

`ssh-keygen -y -f ~/.ssh/id_rsa > ~/.ssh/id_rsa.pub`

`ssh-add ~/.ssh/id_rsa`
