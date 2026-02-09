Markdown

# Lab: Port Scanning with Nmap

## 🎯 Objective
To identify open ports and services running on a target system using Nmap.

## 🛠 Tool Used
- Nmap

## 📌 Commands Used
curl https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/9yTdNwJzgw_mSVlbDLT-lw/Dockerfile > Dockerfile
docker build . -t kalilinux
docker run --tty --interactive  kalilinux
apt-get update
apt-get install -y nmap
nmap scanme.nmap.org
nmap -p22,113,139 scanme.nmap.org
nmap -d --packet-trace -p22,113,139 scanme.nmap.org
nmap -d5 --packet-trace -p22,113,139 scanme.nmap.org
