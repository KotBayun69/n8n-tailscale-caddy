# 🚀 Secure n8n Deployment with Tailscale and Caddy

## 🌟 Overview  

This repository is a fork of [original repo](https://github.com/telepilotco/n8n-secure-deployment "Secure n8n Deployment with Caddy & Traefik")  provides **secure deployment template** for **n8n** using:  
- **Caddy** – Simple, automatic SSL and reverse proxy setup
- **Tailscale** - Best VPN Service for Secure Networks  

Setup is designed to:  
- ✅ **Expose webhooks to the public internet**  
- ✅ **Manage access to n8n UI, login, and workflows** using **Tailscale**  
- ✅ **Automatically manage SSL certificates** via Let's Encrypt  
- ✅ **Use Docker Compose for easy deployment**  

---

## 🚀 Quick Start  

### 1️⃣ Clone the repository  

```sh
git clone https://github.com/KotBayun69/n8n-tailscale-caddy.git
cd n8n-caddy-tailscale/
```

### 3️⃣ Configure environment variables

Copy `.env.example` to `.env`

```sh
cp n8n/.env.example n8n/.env
cp caddy/.env.example caddy/.env
```

Edit `.env` files in both directories to set correct enviromental variables.

### 4️⃣ Deploy the setup  

```sh
sh start.sh
```

---

## 📌 Summary  

- ✅ **Secure n8n deployments with Caddy**  
- ✅ **Public webhooks, private admin access via Tailscale**  
- ✅ **Automatic SSL certificates with Let's Encrypt**  
- ✅ **Docker-based setup for easy management**  

---

## 🤝 Contributing  

Have improvements or want to report issues? Feel free to **open a PR or issue**.  

🔗 **Happy automating with n8n, Caddy, and Traefik!** 🚀


