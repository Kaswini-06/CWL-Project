# Task 1: Server Setup & SSH

## Objective

Set up a Linux server and configure SSH with passwordless login.

---

## Steps

### 1. Install SSH

```bash
sudo apt update
sudo apt install openssh-server -y
```

### 2. Check SSH Status

```bash
sudo systemctl status ssh
```

### 3. Generate SSH Key (Local Machine)

```bash
ssh-keygen
```

### 4. Copy Key to Server

```bash
ssh-copy-id username@server-ip
```

### 5. Test Login

```bash
ssh username@server-ip
```

---

## Outcome

Successfully configured passwordless SSH login to the server.
