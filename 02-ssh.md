# SSH Command

## How SSH Works
#### 1. Symmetric Encryption
  - Key Excahnge Algorithm
  - Use one secret key for encryption and decryption.
  - (Host) "Helloooooo" with the secret key <---> "EI320+@2" <---> "Helloooooo" with the same key (Client)
#### 2. Asymmetric Encryption
  - Difiie-Hellman Key Excahange: 
    - https://www.youtube.com/watch?v=NmM9HA2MQGI
    - https://www.youtube.com/watch?v=Yjrfm_oRO0w
    - https://www.youtube.com/user/Computerphile/playlists
    - https://www.youtube.com/watch?v=NF1pwjL9-DE
  - Uses two separate keys (public and private) for encryption and decryption
  - More time consuming than Symmetric Encryption
  - (Host) "Helloooooo" with the public key of the Client ---> "EI320+@2" ---> "Helloooooo" with the private key of the Client (Client)
#### 3. Hashing
  - Another form of cryptography used in secure shell connections
#### 4. Authenticate User
  - Using passwords
  - Using RSA
  
## SSH Into A Server
#### Generating public/private rsa key pair
```shell
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com" -f "id_rsa_github"
```
#### Adding my ssh key to ssh-agent
```shell
$ ssh-add ~/.ssh/id_rsa_github
# Identity added: /path/id_rsa_github  <-- check this message 
```
