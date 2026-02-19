# Tony Dolingo

Étudiant ingénieur en Cybersécurité & Cloud à l'EFREI Paris, avec une double orientation **Blue Team / SOC** et **Pentest / Red Team**. Passionné par la sécurité des infrastructures cloud, l'analyse de menaces et l'intégration de la sécurité dans les pipelines CI/CD.

> 📅 Disponible pour un stage SOC / Pentest de 6 mois à partir de mars 2026

---

## Compétences

### 🛡️ Cybersécurité
- **SOC** — Déploiement Wazuh, règles de détection custom, ingestion de logs multi-sources
- **Pentest AD** — BloodHound, Kerberoasting, Pass-the-Hash, cassage de hash NTLM (Hashcat)
- **Audit IaC** — Checkov (Terraform), Semgrep SAST (Python), Conftest/Rego (Policy as Code)
- **Analyse de vulnérabilités** — OWASP Top 10, Command Injection, accès non authentifié, DoS

### ☁️ Cloud & Infrastructure
- **Microsoft Azure** — VM, VNet, NSG, Storage Account, IAM
- **Infrastructure as Code** — Terraform (déploiement et sécurisation)
- **Conteneurisation** — Docker, GitLab Container Registry
- **Active Directory** — Administration, audit PingCastle, hardening

### ⚙️ Automatisation & Scripting
- Python, PowerShell, Bash
- **GitLab CI/CD** — Pipelines sécurisés multi-stages (validate → security → plan → deploy)
- **Policy as Code** — Blocage de déploiements non conformes via Conftest + Rego

---

## 📊 Badges & Technologies

### 🔧 Langages & Outils

![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/BASH-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/POWERSHELL-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Terraform](https://img.shields.io/badge/TERRAFORM-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GITLAB%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)
![Flask](https://img.shields.io/badge/FLASK-000000?style=for-the-badge&logo=flask&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🛡️ Cybersécurité

![SOC](https://img.shields.io/badge/SOC-2C3E50?style=for-the-badge&logoColor=white)
![PENTEST](https://img.shields.io/badge/PENTEST-E74C3C?style=for-the-badge&logoColor=white)
![INCIDENT RESPONSE](https://img.shields.io/badge/INCIDENT%20RESPONSE-E67E22?style=for-the-badge&logoColor=white)
![THREAT HUNTING](https://img.shields.io/badge/THREAT%20HUNTING-E67E22?style=for-the-badge&logoColor=white)
![VULNERABILITY ASSESSMENT](https://img.shields.io/badge/VULNERABILITY%20ASSESSMENT-F39C12?style=for-the-badge&logoColor=white)
![DIGITAL FORENSIC](https://img.shields.io/badge/DIGITAL%20FORENSIC-8E44AD?style=for-the-badge&logoColor=white)
![SIEM](https://img.shields.io/badge/SIEM-16A085?style=for-the-badge&logo=wazuh&logoColor=white)
![ELK/WAZUH](https://img.shields.io/badge/ELK%2FWAZUH-005571?style=for-the-badge&logoColor=white)
![KERBEROASTING](https://img.shields.io/badge/KERBEROASTING-C0392B?style=for-the-badge&logoColor=white)
![BLOODHOUND](https://img.shields.io/badge/BLOODHOUND-922B21?style=for-the-badge&logoColor=white)
![HASHCAT](https://img.shields.io/badge/HASHCAT-2C3E50?style=for-the-badge&logoColor=white)
![CHECKOV](https://img.shields.io/badge/CHECKOV-2D9CDB?style=for-the-badge&logoColor=white)
![SEMGREP](https://img.shields.io/badge/SEMGREP-1B2D55?style=for-the-badge&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white)

### ☁️ Cloud & Infra

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![AZURE](https://img.shields.io/badge/AZURE-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![LINUX](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![WINDOWS SERVER](https://img.shields.io/badge/WINDOWS%20SERVER-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![ACTIVE DIRECTORY](https://img.shields.io/badge/ACTIVE%20DIRECTORY-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![VIRTUALBOX](https://img.shields.io/badge/VIRTUALBOX-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)

---

## Projets

### 🔵 SOC Lab – Wazuh SIEM
Déploiement d'un lab SOC complet avec Wazuh : ingestion de logs multi-sources, règles de détection custom, tableaux de bord d'alertes et simulation d'attaques réelles.  
→ [Voir le repo](https://github.com/td4555/SOC-WAZUH)

---

### 🔴 Audit Active Directory & Pentest CTF
Lab Active Directory vulnérable (BadBlood), audit PingCastle (score 100/100), cartographie d'attaque BloodHound, cassage de hash NTLM avec Hashcat (`Mario1` en < 5 secondes), et résolution de 3 flags CTF.  
→ [Voir le repo](https://github.com/td4555/AD-Pentest-CTF)

---

### 🟣 DevSecOps – CI/CD Sécurisé sur Azure
Infrastructure Azure déployée via Terraform avec deux pipelines GitLab CI/CD distincts. Intègre Checkov (scan IaC), Semgrep SAST (analyse de code Python) et Conftest/Rego (blocage de déploiement non conforme). Analyse complète de 5 vulnérabilités applicatives (OWASP) et 5 risques infrastructure avec remédiation.  
→ [Voir le repo](https://github.com/td4555/DevSecOps-Azure-Terraform1)

---

## Stats GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=td4555&show_icons=true&theme=default&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=td4555&layout=compact&theme=default&hide_border=true" height="160"/>
</p>

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tony-dolingo/)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/td4555)
