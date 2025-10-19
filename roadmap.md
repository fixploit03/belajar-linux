Siap Fixploit03! 🔥
Berikut ini **roadmap / playlist super lengkap** untuk **belajar perintah-perintah Linux dari 0 sampai mahir**, dirancang khusus buat kamu yang ingin benar-benar paham **cara kerja Linux di terminal (CLI)** — bukan sekadar hafal, tapi *ngerti logika dan penerapannya* 💪

---

# 🧭 **Roadmap Belajar Perintah Linux (Command Line Mastery)**

> 📍 Level: Pemula → Menengah → Mahir
> 🎯 Tujuan: Menguasai command line Linux untuk administrasi, scripting, dan security.

---

## 🧩 **BAB 1 — Fondasi Linux & Terminal (Fundamental)**

**Tujuan:** Mengenal sistem Linux dan cara kerja terminal.

### 🔹 1.1. Pengenalan Dasar

* Apa itu Linux? (Kernel vs Distro)
* Struktur sistem Linux (Root, /bin, /etc, /home, /var, /usr)
* Shell vs Terminal vs Console
* Login shell: bash, zsh, sh

### 🔹 1.2. Navigasi Dasar (Filesystem)

📘 *Tujuan:* Bisa berpindah, mencari, dan memahami struktur direktori.

* `pwd` — cek posisi saat ini
* `ls`, `ls -l`, `ls -a` — melihat isi folder
* `cd` — berpindah direktori
* `tree` — menampilkan struktur folder
* `file` — melihat tipe file
* `which`, `whereis` — mencari lokasi binary

🧠 **Praktik:**

> Buat folder `/home/fixploit/test/` dan isi dengan beberapa file dummy, lalu jelajahi menggunakan kombinasi `ls`, `cd`, `tree`.

---

## ⚙️ **BAB 2 — Manajemen File & Direktori**

**Tujuan:** Menguasai operasi file dan direktori.

### 🔹 2.1. Membuat & Menghapus

* `touch` — membuat file kosong
* `mkdir`, `mkdir -p` — membuat direktori
* `rm`, `rm -r`, `rmdir` — menghapus
* `cp`, `cp -r` — menyalin file/folder
* `mv` — memindahkan atau mengganti nama

### 🔹 2.2. Melihat & Mengedit Isi File

* `cat`, `tac`, `head`, `tail` — menampilkan isi file
* `less`, `more` — membaca file panjang
* `nano`, `vim`, `gedit` — editor teks
* `wc`, `nl` — menghitung baris/karakter

🧠 **Praktik:**

> Buat file `catatan.txt`, isi dengan beberapa baris teks, lalu tampilkan 5 baris terakhir dengan `tail -n 5 catatan.txt`.

---

## 🧰 **BAB 3 — Manajemen Pengguna & Izin (Permission)**

**Tujuan:** Mengerti sistem keamanan berbasis user.

### 🔹 3.1. User & Group

* `whoami`, `id`, `groups`
* `adduser`, `userdel`, `usermod`
* `passwd` — ubah password
* `su`, `sudo` — ganti user atau jalankan perintah sebagai root

### 🔹 3.2. Permission System

* `chmod` — ubah permission (rwx)
* `chown` — ubah kepemilikan file
* `chgrp` — ubah grup file
* `umask` — set default permission

🧠 **Praktik:**

> Buat file `confidential.txt`, ubah permission hanya agar bisa dibaca oleh owner.

---

## 🧮 **BAB 4 — Manajemen Proses & Resource**

**Tujuan:** Memahami dan mengendalikan proses sistem.

### 🔹 4.1. Monitoring Proses

* `ps`, `ps aux`, `top`, `htop`
* `pgrep`, `pidof`
* `kill`, `killall`
* `nice`, `renice`

### 🔹 4.2. Informasi Sistem

* `uptime`, `free`, `vmstat`, `df -h`, `du -sh`
* `lscpu`, `lsblk`, `uname -a`, `dmesg`, `journalctl`

🧠 **Praktik:**

> Jalankan program `ping` di background, lalu hentikan prosesnya dengan `kill`.

---

## 🌐 **BAB 5 — Networking Dasar di Linux**

**Tujuan:** Memahami perintah jaringan di Linux.

* `ip addr`, `ifconfig` — melihat IP address
* `ping`, `traceroute`, `nslookup`, `dig`
* `netstat`, `ss`, `lsof -i` — cek port dan koneksi
* `scp`, `rsync` — transfer file antar host
* `curl`, `wget` — unduh file dari internet

🧠 **Praktik:**

> Coba `ping google.com` dan analisa TTL, waktu respons, dan IP tujuan.

---

## 📦 **BAB 6 — Manajemen Paket**

**Tujuan:** Menguasai instalasi & update software di Linux.

### 🔹 6.1. Debian/Ubuntu

* `apt update`, `apt upgrade`
* `apt install`, `apt remove`, `apt purge`
* `dpkg -l`, `dpkg -i`

### 🔹 6.2. RHEL/Fedora

* `dnf`, `yum` — command dasar mirip `apt`

🧠 **Praktik:**

> Install package `nmap` dan jalankan `nmap localhost`.

---

## 🧾 **BAB 7 — Searching & Filtering**

**Tujuan:** Mampu mencari data secara efisien.

* `find`, `locate` — mencari file
* `grep`, `egrep`, `fgrep` — mencari teks dalam file
* `awk`, `sed` — manipulasi teks
* `sort`, `uniq`, `cut`, `tr` — pemrosesan data teks

🧠 **Praktik:**

> Cari semua baris dalam file `/etc/passwd` yang mengandung kata `root`.

---

## ⚡ **BAB 8 — Redirection, Pipe, & Job Control**

**Tujuan:** Memahami alur input/output di shell.

* `>` redirect output ke file
* `>>` append ke file
* `<` ambil input dari file
* `|` pipe antar perintah
* `&`, `jobs`, `bg`, `fg` — kontrol background process

🧠 **Praktik:**

> Gabungkan output `ls` dan `grep` untuk mencari file tertentu dalam satu baris command.

---

## 🧑‍💻 **BAB 9 — Automasi & Scripting Dasar**

**Tujuan:** Membuat script sederhana untuk mengotomasi tugas.

* Struktur script bash (`#!/bin/bash`)
* Variabel (`$var`)
* Kondisi (`if`, `else`, `elif`)
* Perulangan (`for`, `while`)
* Fungsi
* Argument script (`$1`, `$2`, `$@`)

🧠 **Praktik:**

> Buat script yang menampilkan “Halo, Fixploit03!” dan waktu saat ini.

---

## 🧱 **BAB 10 — Level Mahir & Praktik Real**

**Tujuan:** Penerapan nyata di dunia admin & security.

### 🔹 10.1. Manajemen Sistem Lanjut

* `systemctl`, `service`, `journalctl`
* `cron`, `at` — penjadwalan tugas
* `tar`, `gzip`, `zip`, `unzip` — kompresi data

### 🔹 10.2. Keamanan Dasar

* `chmod`, `chattr`, `sudoers`, `ufw`
* `iptables`, `fail2ban`

### 🔹 10.3. Networking Real Case

* Membuat server SSH, FTP, HTTP
* Monitoring trafik dengan `tcpdump`, `iftop`, `nload`

---

## 🏁 **BAB 11 — Tantangan & Latihan Akhir**

**Tujuan:** Melatih kemampuan real-world.

🔸 Challenge:

* Buat backup otomatis setiap jam menggunakan cron
* Filter log error dari `/var/log/syslog`
* Buat script monitoring CPU dan memory real-time
* Cari file >100MB di `/home` dan kirim laporannya via email

---

## 🧠 Tips Belajar Efektif:

1. Gunakan distro Linux (Ubuntu, Kali, atau Debian) di VM/WSL.
2. Ketik manual setiap command (bukan copy-paste).
3. Catat setiap perintah yang kamu pelajari di “Linux Journal” pribadi.
4. Gunakan `man <command>` untuk baca dokumentasi.
5. Lakukan 1 bab per hari dan ulangi bab sebelumnya 3x seminggu.

---

Kalau kamu mau, aku bisa bantu buatkan versi **PDF + latihan soal + kuis praktikum** untuk setiap bab biar bisa kamu jadikan bahan ajar atau portofolio latihan Linux.
Apakah kamu mau aku lanjutkan buat versi PDF-nya juga, Fixploit03?
