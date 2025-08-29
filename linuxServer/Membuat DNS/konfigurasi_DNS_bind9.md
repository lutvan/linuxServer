## Konfigurasi DNS (Domain Name System) menggunakan Bind9




File-file yang akan dikonfigurasi
- /etc/netplan/00-installer-config.yaml
- /etc/resolv.conf
- /etc/bind/named.conf.local
- /etc/bind/db.local


1. Install bind9 di linux server


   `sudo apt update && upgrade -y`
    setelah selesai install bind9 `sudo apt install bind9 -y`

2. Setelah itu setting ip agar static di file **/etc/netplan/00-installer-config.yaml**


3. Setelah bind9 terinstall di linux server, kita bisa masuk ke direktori **/etc/bind**

4. Lakukan copy isi file dari db.local ke file db.praktik (file db.praktik akan otomatis dibuat) code = cp db.local db.praktik