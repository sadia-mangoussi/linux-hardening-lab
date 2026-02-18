# Linux Hardening Lab 🔐

Dans ce projet, je mets en place différentes mesures pour sécuriser un serveur Linux.

## Objectif

Comprendre et appliquer les bonnes pratiques de sécurisation d’un serveur.

## Mesures mises en place

- Sécurisation de SSH
- Désactivation du login root
- Configuration du firewall (UFW)
- Installation de fail2ban
- Mise à jour automatique du système

## Environnement

- Distribution : Ubuntu / Debian
- Machine virtuelle (VirtualBox)

Ce projet est réalisé dans un objectif pédagogique pour renforcer mes compétences en cybersécurité.

---

## 1. Sécurisation SSH

Édition du fichier de configuration :

```bash
sudo nano /etc/ssh/sshd_config

## Tests réalisés

Les mesures de sécurité ont été testées depuis une machine Kali Linux dans un environnement virtuel isolé.
