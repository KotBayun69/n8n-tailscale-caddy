# 🚀 Secure n8n Deployment with Caddy & Traefik

## 🌟 Overview  

This repository is a fork of [original repo](https://github.com/telepilotco/n8n-secure-deployment)"Secure n8n Deployment with Caddy & Traefik"  provides **secure deployment template** for **n8n** using:  
- **Caddy** – Simple, automatic SSL and reverse proxy setup  

Setup is designed to:  
- ✅ **Expose only webhooks to the public internet**  
- ✅ **Keep the n8n UI, login, and workflows private** using **Tailscale**  
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
```
cp .env.example .env
```
Edit `.env` to set up domains, Tailscale settings, and n8n configurations.

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


