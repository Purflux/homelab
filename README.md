# Homelab

## EN 🇬🇧

My current homelab setup is designed as a simple but effective environment for self-hosting and experimentation with a variety of services.  
At the core of the network is a basic infrastructure that starts with my ISP-provided router, which is directly connected to an **8-port Zyxel unmanaged switch**. This allows multiple devices to connect and communicate within the network.

### Connected Devices
- **Desktop PC** – used for day-to-day tasks, monitoring, and management.
- **Laptop as a server** – currently serving as the main hub for self-hosted services.

### Services Hosted on UmbrelOS
> Configured with **Google Authenticator 2FA** for secure access.

- **Tailscale** – secure remote access via mesh VPN.
- **Nextcloud** – personal cloud storage and file sync.
- **Wazuh** – open-source SIEM for monitoring and logging.
- **Portainer** – container management via a web UI.

### Future Plans
In the near future, I plan to migrate everything to a dedicated server running **Proxmox VE**, where each service will run in its own **virtual machine (VM)** for improved security, scalability, and management.

This upgrade will provide a solid foundation for more advanced experiments in networking, virtualization, and cybersecurity.

---

## LT 🇱🇹

Mano dabartinė homelabo konfigūracija yra paprasta, bet efektyvi – ji leidžia savarankiškai talpinti paslaugas ir eksperimentuoti su įvairiomis technologijomis.  
Pagrindą sudaro **interneto tiekėjo (ISP) maršrutizatorius**, prijungtas prie **8 prievadų „Zyxel“ nevaldomo komutatoriaus**, leidžiančio keliems įrenginiams tarpusavyje komunikuoti tinkle.

### Prijungti įrenginiai
- **Stacionarus kompiuteris** – naudojamas kasdienėms užduotims ir valdymui.
- **Nešiojamas kompiuteris (serveris)** – pagrindinė savarankiškai talpinamų paslaugų platforma.

### UmbrelOS Talpinamos Paslaugos
> Suaktyvinta **Google Authenticator 2FA** apsauga.

- **Tailscale** – saugus nuotolinis prisijungimas per VPN.
- **Nextcloud** – debesijos saugykla ir failų sinchronizavimas.
- **Wazuh** – SIEM stebėsenai ir žurnalavimui.
- **Portainer** – konteinerių valdymas per naršyklę.

### Ateities Planai
Artimiausiu metu planuoju viską perkelti į atskirą serverį su **Proxmox VE**, kur kiekviena paslauga veiks atskiroje **virtualioje mašinoje (VM)**.  
Tai leis pagerinti lankstumą, saugumą ir sudarys sąlygas gilintis į sudėtingesnius tinklų bei virtualizacijos sprendimus.

---
