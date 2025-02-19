# python-pterodactyl-tunnel



Pterodactyl Python  egg with Git & Cloudflare Tunnel support 
<br><br>
## Features

#### 🔹 Supports AMD64 & ARM64
#### 🔹 Cloudflare Tunnel support
#### 🔹 Git support for your Python
#### 🔹 You can select the desired Python version:
- ✅ 3.14
- ✅ 3.13
- ✅ 3.12


[Python supported versions](https://devguide.python.org/versions/)
<br><br>
## How to install

- **Step 1:** Download the egg (json file `egg-python.json`)
- **Step 2:** In your panel, go to the "Nests" category in the sidebar
- **Step 3:** Import the egg under "Import egg"
- **Step 4:** Create a new server and select the "Python" egg
- **Step 5:** Select the corresponding Docker image with the desired Python version
- **Step 6:** Fill in the text fields. Whether Git is desired or not. It is important to **enter the Cloudflare Token And the domain/subdomain u wanna in they field**.
<br><br>
## 🚀 Cloudflared Tunnel Tutorial  

With **Cloudflared**, you can create a secure tunnel to your server, making it accessible over the internet **without** complicated port forwarding!  
[Cloudflared | Create a remotely-managed tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/get-started/create-remote-tunnel/)

### 📌 Requirements  
- A [Cloudflare](https://dash.cloudflare.com/) account  

---

- 🔹 **Step 1: Log in to Zero Trust ↗ and go to Networks > Tunnel**  
- 🔹 **Step 2: Select Create a tunnel.**  
- 🔹 **Step 3: Choose Cloudflared for the connector type and select Next.**  
- 🔹 **Step 4: Enter a name for your tunnel.**  
- 🔹 **Step 5: Select Save tunnel.**  
- 🔹 **Step 6: Save the token. (The token is very long)**
  
![grafik](https://github.com/user-attachments/assets/0c0430a5-5cb6-45e4-8b26-1805cddde3cc)


---

- 🔹 **Step 7: Activate Cloudflared**
    
![grafik](https://github.com/user-attachments/assets/726c5dad-7cb6-4537-a215-6aaec59d827a)


---

- 🔹 **Step 8: Add your token.**
  
![grafik](https://github.com/user-attachments/assets/46b09f6a-30b0-48aa-9980-53697b1fbcf6)

---

- 🔹 **Step 9: Add public hostname**
  
![grafik](https://github.com/user-attachments/assets/2107c323-1ed1-406b-8fcf-12ceac963aea)

---

- 🔹 **Step 10: Depending on the type, select http and URL always “localhost” + the python port**

![grafik](https://github.com/user-attachments/assets/7b1a4e91-50f3-4fcb-a0da-7eed611ae391)

---

- 🔹 **Step 11: Restart your Python.**
  
![grafik](https://github.com/user-attachments/assets/3d4b63fd-db66-4a7d-85ea-0bec4a7ef948)


✅ You have successfully set up Cloudflared and connected it to your server!<br><br>
🔹 Info: Your web server ip and port does not have to be accessible from outside and can have a local IP such as 127.0.0.1.
<br><br>
## FAQ

```bash
Core, apt-get, update, install, build-essential, libssl-dev, zlib1g-dev, libbz2-dev, libreadline-dev, libsqlite3-dev, libgdbm-dev, libdb5.3-dev, libexpat1-dev, git, liblzma-dev, libffi-dev, iproute2, libncurses5-dev, libncursesw5-dev, xz-utils, tk-dev, wget, curl, ca-certificates, jq, clean, rm, uname, x86_64, aarch64, dpkg, cloudflared, unsupported architecture
```

Small differences in the extensions between the Python versions.
<br><br>
## License

[MIT License](https://choosealicense.com/licenses/mit/)
