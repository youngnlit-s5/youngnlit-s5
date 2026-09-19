<h1 align="center">DevOps Engineer</h1>
<p align="center"><b>Infrastructure & Systems Engineer</b> · Linux / Windows · Virtualization · Networking · Automation</p>

<p align="center">
<img src="https://img.shields.io/badge/Focus-Infrastructure%20%26%20Automation-1F3864?style=flat-square">
<img src="https://img.shields.io/badge/Scale-1000%2B%20users%20%2F%2089%20sites-2E7D32?style=flat-square">
<a href="mailto: ilija@youngnlits5.com"><img src="https://img.shields.io/badge/Email- ilija@youngnlits5.com-555?style=flat-square&logo=maildotru&logoColor=white"></a>
</p>

---

## About these repositories

Everything published here runs on an isolated lab bench, and that is deliberate.

My production work was delivered for a client under an IT services contract with confidentiality obligations. Client configurations, addressing, naming, topology and data cannot be published — and none of them appear in any commit here.

What these repositories contain instead is the same architecture rebuilt from zero on test hardware: the same design decisions, the same stack, the same failure modes. Every result is verified with real command output rather than screenshots of installers, so the work can be read and checked rather than taken on trust.

Not toy projects, and not copies of client systems. Reproductions of work that already ran in production, built in an environment where they can be shown.

---

## Production experience

IT services contractor delivering infrastructure support to a public-sector client — **1000+ users across 89 branch offices**.

- Planned and executed a migration from **Microsoft Active Directory** to a **FreeIPA**-based directory (ALD Pro on Astra Linux SE) for **~200 workstations with no critical downtime**: domain controllers, package repositories, OU and policy design, staged cutover
- Ran production virtual machines on **VMware ESXi, Proxmox VE, Hyper-V, oVirt/zVirt and KVM**
- Configured branch networking on **MikroTik RouterOS** — routing, NAT, VLAN segmentation, firewall policy and **WireGuard** tunnels
- Covered infrastructure health with **Zabbix**, scheduled backups with regular restore testing
- Escalation point for 1st and 2nd line support; author of the team's runbooks
- Worked to contract discipline: changes inside agreed maintenance windows, documented before execution, no unplanned downtime on the serviced estate

---

## Core skills

**Linux** — Debian, Ubuntu, RHEL-family, Astra Linux SE, Alt Linux · systemd · PAM/SSSD · LDAP · BIND9 · nginx · PostgreSQL · unattended (preseed) deployment · troubleshooting down to logs and syscalls

**Identity & directory** — FreeIPA / Red Hat Identity Management · 389 Directory Server · MIT Kerberos KDC · HBAC and sudo rules · Kerberos SSO · Active Directory, OU and GPO design · AD-to-FreeIPA migration

**Virtualization** — VMware vSphere/ESXi · Proxmox VE · Hyper-V · KVM/QEMU with libvirt · oVirt/zVirt · Brest

**Networking** — MikroTik RouterOS · WireGuard · VLAN segmentation · firewall policy · TCP/IP · DNS/DHCP

**Windows** — Windows Server, AD DS, Group Policy · Windows 10/11 fleet · Microsoft Exchange · PowerShell

**Automation** — Bash · PowerShell · Ansible · Docker and Docker Compose · Git

**Monitoring & backup** — Zabbix · Uptime Kuma · scheduled and offsite backups · restore testing

---

## Repositories

| Repository | What it reproduces | Stack |
|---|---|---|
| **aldpro-enterprise-project** | The directory migration, rebuilt end to end — 389-ds, Kerberos KDC, integrated DNS, HBAC and sudo rules; second phase models the OU tree and permission matrix for a ~200-user / ~150-machine multi-site company | FreeIPA / ALD Pro, Astra Linux SE |
| **astralinux-custom-image** | The deployment method — a fully unattended installation image (preseed + post-install hooks) rebuilt by a single Bash script using xorriso without root privileges: repository wiring, software installation and host configuration automated | Bash, xorriso, preseed |
| **mikrotik-lab** | The branch network topology as code — default-drop firewall, isolated guest VLAN, per-segment DHCP/DNS, WireGuard VPN, hardened management access; imports in one command | RouterOS, WireGuard |
| **ansible-lab** | The provisioning approach — two Docker hosts built from scratch with four idempotent roles: engine, nginx reverse proxy, private registry, scheduled backups; linted and verified idempotent | Ansible, Docker |
| **docker-lab** | The service stack — nginx reverse proxy with TLS termination, private registry with basic auth, uptime monitoring, nightly volume backups with retention pruning | Docker Compose, nginx |

<sub>**docker-lab-ru** — the same Docker lab with documentation in Russian.</sub>

---

## Currently working through

GitLab CI/CD · Kubernetes · Terraform · Prometheus and Grafana

---

## Contact

 ilija@youngnlits5.com · Belgrade, Serbia · Serbian, Russian, English (B2)
