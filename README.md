# How to SSH-Product key Generate for our Github Account

### 1. Open Git Bash / Terminal on your laptop/PC

<hr>

### 2. Generat a new ED25519 key pair by running blow command. Please ensure that you are usning your Email-Id(email which is use in github a/c and gitbash terminal):

```
ssh-keygen -t ed25519 -C "<EMAIL>"

```

<hr>

### 3. Then press 'enter' three-times.
<hr>

### 4. Copy your public SSH key to the clipboard by using below option 1 or 2 command:

```
1. cat ~/.ssh/id_ed25519.pub | chip
2. clip < ~/ .ssh/id_ed25519.pub

```

<hr>

### Note: If clip isn't working, you can locate the hidden .ssh folder, open the file in your favorite text editor, and copy it to your clipboard.

<hr>

### 5. Paste it inside --> Github --> Account Settings --> SSH & GPG Keys --> Add New SSH Key -->key(text-area)-->Save
---
## 📬 Contact

- **Portfolio:** [Roshan Rawal's Portfolio](https://your-portfolio-link.com)  
- **GitHub:** [Roshan Rawal's GitHub](https://github.com/your-github-username)  
- **LinkedIn:** [Roshan Rawal's LinkedIn](https://www.linkedin.com/in/your-linkedin-id/)  
- **Email:** roshanrawal@zuckonit.com  

---
## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.

##### <buttom>By Roshan Rawal</button>
