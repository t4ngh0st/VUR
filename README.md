<p align="center">
  <img src="T4n.png" alt="T4n OS Logo" width="200"/>
</p>
<h1 align="center">Official Repository</h1>

---
## 📦 Tentang Repository
Repositori ini berisi **paket, library, dan konfigurasi** untuk digunakan dengan **T4n OS** dan **Void Linux**.  
T4n OS menyediakan pengalaman ringan, cepat, serta kemudahan penggunaan **xbps** & **xbps-src**, dengan **[T4n-Man](https://github.com/t4ngh0st/T4n-Man)** atau **[T4n-Manpy](https://github.com/t4ngh0st/T4n-Manpy)** sebagai package manager wrapper.

---

## Update repo

- Edit File
```
sudo nano /etc/xbps.d/20-repository-custom.conf
```

- Edit URL File
```
repository=<URL_REPO>
```

## Struktur
```
VUR/
├── core/
│   ├── xbps/
│   │   ├── template
│   │   ├── xbps.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── extra/
│   ├── bspwm/
│   │   ├── template
│   │   ├── bspwm.json
│   │   └── README.md
│   ├── nvidia-driver/
│   │   ├── template
│   │   ├── nvidia.json
│   │   └── README.md
│   ├── xfce/
│   │   ├── template
│   │   ├── xfce.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── developer/
│   ├── zig/
│   │   ├── template
│   │   ├── zig.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── utils/
│   ├── htop/
│   │   ├── template
│   │   ├── htop.json
│   │   └── README.md
│   ├── neofetch/
│   │   ├── template
│   │   ├── neofetch.json
│   │   └── README.md
│   ├── tmux/
│   │   ├── template
│   │   ├── tmux.json
│   │   └── README.md
│   ├── curl/
│   │   ├── template
│   │   ├── curl.json
│   │   └── README.md
│   ├── wget/
│   │   ├── template
│   │   ├── wget.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── multilib/
│   ├── 32bit/
│   │   ├── template
│   │   ├── 32.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── gaming/
│   ├── lutris/
│   │   ├── template
│   │   ├── lutris.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── security/
│   ├── metasploit/
│   │   ├── template
│   │   ├── metasploit.json
│   │   └── README.md
│   ├── nmap/
│   │   ├── template
│   │   ├── nmap.json
│   │   └── README.md
│   ├── wireshark/
│   │   ├── template
│   │   ├── wireshark.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── fonts/
│   ├── mscorefonts/
│   │   ├── template
│   │   ├── mscorefonts.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── themes/
│   ├── arc-theme/
│   │   ├── template
│   │   ├── arc-theme.json
│   │   └── README.md
│   └── other/
│       ├── template
│       ├── other.json
│       └── README.md
│
├── testing/                     # staging area untuk paket baru
│
├── scripts/                     # lint, build, index generator
│   ├── lint-template.sh
│   ├── lint-json.sh
│   └── build-index.sh
│
├── docs/                        # dokumentasi
│   ├── build.md
│   ├── metadata.md
│   └── faq.md
│
├── .github/
│   └── workflows/
│       ├── lint.yml
│       ├── build.yml
│       └── index.yml
│
├── packages.json                # auto-generated (jangan edit manual)
├── README.md
├── LICENSE
├── CONTRIBUTING.md
└── MAINTAINERS.md


```







