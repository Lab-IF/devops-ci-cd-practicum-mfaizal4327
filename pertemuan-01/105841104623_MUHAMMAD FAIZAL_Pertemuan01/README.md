# 📘 LAPORAN PRAKTIKUM DEVOPS

**Nama:** Muhammad Faizal\
**NIM:** (105841104623)\
**Mata Kuliah:** DevOps\
**Pertemuan:** 01

------------------------------------------------------------------------

# 📝 Task 1 -- Instalasi Development Environment

## 1.1 Instalasi Git

### Instalasi (Windows)

    winget install Git.Git

Download alternatif: https://git-scm.com/download/win

### Verifikasi

    git --version

Screenshot simpan sebagai: `screenshots/01-git-version.png`

------------------------------------------------------------------------

## 1.2 Konfigurasi Git

    git config --global user.name "Muhammad Faizal"
    git config --global user.email "email@student.unismuh.ac.id"
    git config --global init.defaultBranch main
    git config --global core.editor "code --wait"
    git config --list

Screenshot simpan sebagai: `screenshots/02-git-config.png`

------------------------------------------------------------------------

## 1.3 Instalasi Docker

Download dari: https://www.docker.com/products/docker-desktop

Verifikasi:

    docker --version
    docker run hello-world

Screenshot: - `screenshots/03-docker-version.png` -
`screenshots/04-docker-hello-world.png`

------------------------------------------------------------------------

## 1.4 Instalasi Visual Studio Code

Download: https://code.visualstudio.com

Install extensions:

    code --install-extension ms-azuretools.vscode-docker
    code --install-extension eamodio.gitlens
    code --install-extension redhat.vscode-yaml
    code --install-extension ms-vscode-remote.remote-containers

Screenshot: `screenshots/05-vscode-extensions.png`

------------------------------------------------------------------------

# 🧠 Pemahaman DevOps

DevOps adalah pendekatan dalam pengembangan perangkat lunak yang
menggabungkan tim Development dan Operations untuk meningkatkan
kolaborasi serta mempercepat proses delivery aplikasi. DevOps bertujuan
untuk menghilangkan sekat antara pengembang dan tim operasional sehingga
proses build, testing, dan deployment dapat dilakukan secara otomatis
dan berkelanjutan.

Dalam industri modern, DevOps menjadi sangat penting karena perusahaan
dituntut untuk merilis fitur baru dengan cepat tanpa mengorbankan
kualitas sistem. Dengan bantuan tools seperti Git dan Docker, proses
integrasi dan deployment dapat dilakukan secara efisien. Perusahaan
besar seperti Netflix dan Amazon telah berhasil menerapkan DevOps untuk
memastikan layanan mereka tetap stabil meskipun melayani jutaan pengguna
setiap hari.

------------------------------------------------------------------------

# 📁 Struktur Folder Submission

    NIM_Nama_Pertemuan01/
    │
    ├── README.md
    │
    ├── screenshots/
    │   ├── 01-git-version.png
    │   ├── 02-git-config.png
    │   ├── 03-docker-version.png
    │   ├── 04-docker-hello-world.png
    │   └── 05-vscode-extensions.png
    │
    └── refleksi.md

------------------------------------------------------------------------

# 📄 Refleksi Singkat

Praktikum DevOps ini memberikan saya pemahaman awal mengenai pentingnya
lingkungan pengembangan yang terstandarisasi. Saya berharap di akhir
semester mampu memahami CI/CD, containerization, serta deployment
aplikasi secara otomatis dan profesional.
