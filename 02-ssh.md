# SSH
SSH is secure shell protocol

## How SSH Works
How Secure Shell Works (SSH) - Computerphile: https://youtu.be/ORcvSkgdA58
#### 1. Symmetric Encryption
  - Key Excahnge Algorithm
  - Use one secret key for encryption and decryption.
  - (Host) "Helloooooo" with the secret key <---> "EI320+@2" <---> "Helloooooo" with the same key (Client)
#### 2. Asymmetric Encryption
  - Difiie-Hellman Key Excahange:
    - https://www.youtube.com/watch?v=NmM9HA2MQGI
    - https://www.youtube.com/watch?v=Yjrfm_oRO0w
    - https://www.youtube.com/watch?v=vsXMMT2CqqE&t=
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
  Identity added: /path/id_rsa_github  <-- check this message

# to check added the key list
$ ssh-add -l
```

## Set up SSH on GitHub
* Link: https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh
* Link: https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/troubleshooting-ssh
#### Check my public key and copy it
```shell
$ cat id_rsa_github.pub
```
#### Go to GitHub > Setting > SSH and GPG keys > "New SSH Keys" > add Title and paste the content of the id_rsa_github.pub > Add SSH Key
* Setup-ssh-for-github: https://github.com/antonykidis/Setup-ssh-for-github/blob/master/Setup-ssh-on-github.pdf

## Git clone with SSH key
#### Copy a repo url with the ssh option
```shell
$ git clone {ssh git clone url}
```

## Switching remote URLs from HTTPS to SSH
* Link: https://docs.github.com/en/free-pro-team@latest/github/using-git/changing-a-remotes-url#switching-remote-urls-from-https-to-ssh
```shell
# Change your remote's URL from HTTPS to SSH with the git remote set-url command.
$ git remote set-url origin git@github.com:USERNAME/REPOSITORY.git

# Verify that the remote URL has changed.
$ git remote -v
```

## How to Connect
```shell
$ ssh {user_name}@{host_ip}
or
$ ssh -i {key_path} {user_name}@{host_ip}
```
