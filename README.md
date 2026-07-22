<h1 align="center">Ilija Sredojevic</h1>
<p align="center"><b>Infrastructure & Systems Engineer</b> · Linux / Windows · Virtualization · Networking · Automation</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Infrastructure%20%26%20Automation-1F3864?style=flat-square">
  <img src="https://img.shields.io/badge/Scale-1000%2B%20users%20%2F%2089%20sites-2E7D32?style=flat-square">
  <a href="mailto:sredoevich.ilya@icloud.com"><img src="https://img.shields.io/badge/Email-sredoevich.ilya@icloud.com-555?style=flat-square&logo=maildotru&logoColor=white"></a>
</p>

---

I build and run corporate IT infrastructure — domain services, virtualization, networking and monitoring — across mixed **Linux and Windows** environments, with a strong bias toward **import-independent (Russian) stacks**: Astra Linux, ALD Pro, Alt, zVirt/oVirt, Brest.

Most of my work is **3rd-line engineering and rollouts**: standing up domain controllers and repositories, planning and executing migrations, wiring up virtualization and networks, and making the whole thing observable and backed up. My current project spans **1000+ users across 89 branch offices** country-wide. I care about doing changes without downtime, documenting them, and automating anything that gets repeated.

Lately I've been moving that same mindset toward **DevOps** — containers, declarative provisioning, and everything-as-code.

## What I work with

**Directory & migration** — Designing OU/GPO structures, DNS/DHCP, and running **Active Directory → ALD Pro / FreeIPA** migrations (~200 workstations, no critical downtime): domain controller + repository prep, software-install policies, staged cutover, incident handling.

**Virtualization** — Building and operating VMs in production on **VMware/ESXi, Proxmox VE, Hyper-V, zVirt/oVirt, Brest and Alt Virtualization** — networking, snapshots, and backup strategy included.

**Networking** — **MikroTik / RouterOS** as the backbone: routing, NAT, VLANs, firewall, bridges, and **WireGuard** for secure remote access; DNS/DHCP and ISP uplinks.

**Monitoring & services** — **Zabbix** for infrastructure health, scheduled backups, plus **PostgreSQL**, Microsoft Exchange and mail services (install, tuning, diagnostics).

**Automation** — **Bash** and **PowerShell** for day-to-day operations; **Ansible** and **Docker Compose** for reproducible lab and service stacks; **Git** for keeping configs versioned.

## Lab & homelab

I keep a homelab where I prototype before touching production. These repos hold the configs and playbooks behind it:

| Repo | Stack | What it demonstrates |
|---|---|---|
| **docker-lab** | Docker Compose · Nginx · Uptime Kuma | Reverse proxy, private registry, healthchecks and automated backups on a single host |
| **ansible-lab** | Ansible · YAML | Control node + two Docker hosts provisioned from scratch: roles for Docker, reverse proxy, registry and backup |
| **mikrotik-lab** | RouterOS · WireGuard | Full home network: routing, NAT, DHCP/DNS, firewall rules and a WireGuard VPN, with a topology diagram |

## Toolbox

![Astra Linux](https://img.shields.io/badge/Astra%20Linux-FF0000?style=flat-square&logo=linux&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![ALD Pro / AD](https://img.shields.io/badge/ALD%20Pro%20%2F%20Active%20Directory-1F3864?style=flat-square&logo=microsoft&logoColor=white)
<br>
![VMware](https://img.shields.io/badge/VMware%20ESXi-607078?style=flat-square&logo=vmware&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox%20VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Hyper-V](https://img.shields.io/badge/Hyper--V-0078D6?style=flat-square&logo=windows&logoColor=white)
![KVM](https://img.shields.io/badge/KVM%20%2F%20QEMU-CC0000?style=flat-square&logo=qemu&logoColor=white)
![oVirt](https://img.shields.io/badge/zVirt%20%2F%20oVirt%20%2F%20Brest-5A2D82?style=flat-square&logo=redhat&logoColor=white)
<br>
![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=flat-square&logo=mikrotik&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
<br>
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Currently exploring

CI/CD with GitLab CI · Kubernetes · Terraform — extending the automation habit from single hosts to full pipelines and clusters.

---

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=youngnlit-s5&show_icons=true&hide_border=true&title_color=1F3864&icon_color=1F3864" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=youngnlit-s5&layout=compact&hide_border=true&title_color=1F3864" />
</p>
