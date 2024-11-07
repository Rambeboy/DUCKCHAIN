## DUCKCHAIN BOT

![duck1](https://github.com/user-attachments/assets/778b18b7-0d8b-4448-8943-7bff90ac679c)

---

## BOT FEATURE

- Auto Daily
- Auto Task
- Auto Claim Faucet
- Auto Play Game

---

## REQUIREMENTS

- Node JS
- Git

---

## INSTALL MODULES

1. Clone Project Repository
   ```bash
   git clone https://github.com/Rambeboy/DUCKCHAIN.git && cd DUCKCHAIN
   ```

2. Install Depedencies
   ```bash
   npm install
   ```

Create two files: `data.txt` and `proxy.txt`

For those using multiple accounts, it's recommended to use a proxy (if using only one account, there's no need to create the `proxy.txt` file).

---

# PROXY FORMAT

```bash
http://username:password@hostname:port
socks5://username:password@hostname:port
```

---

# GET DATA

- In the `data.txt` file, you need to have the following format:
  ```bash
  query_id=xxx
  user=xxxx
  ```

- In the `auth.txt` and `wallet.txt` file:

![edit](https://github.com/user-attachments/assets/c8efd7f8-0df1-4bcd-8603-9e60a2dc76cf)

![edit3](https://github.com/user-attachments/assets/82fefaad-1af2-4cef-a633-d38d39462988)

---

# RUN BOT

- Faucet
  ```bash
  node faucet.js
  ```

- No Proxy
  ```bash
  node main.js
  ```

- Proxy
  ```bash
  node duck-proxy.js
  ```

  ---
