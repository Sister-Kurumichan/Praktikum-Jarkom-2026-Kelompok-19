# Tugas Modul 4

## 1. Topologi Jaringan

![Topologi](images/topologi.png)

## 2. Tabel IP Address

| Perangkat | Interface | IP Address | Keterangan |
|------------|------------|------------|------------|
| MikroTik | ether1 | DHCP Client | Terhubung ke Cloud |
| MikroTik | ether2 | 10.10.10.1/30 | Ke FortiGate |
| MikroTik | ether3 | 172.16.100.1/24 | Ke WAN Client |
| FortiGate | port1 | 10.10.10.2/30 | WAN |
| FortiGate | port2 | 10.20.20.1/30 | INSIDE |
| FortiGate | port3 | 192.168.20.1/24 | DMZ |
| Cisco Router | Gi0/0 | 10.20.20.2/30 | Ke FortiGate |
| Cisco Router | Gi0/1 | 192.168.10.1/24 | LAN Gateway |
| Client LAN | eth0 | 192.168.10.10/24 | Host LAN |
| Server DMZ | eth0 | 192.168.20.10/24 | Web Server |
| Client WAN | eth0 | 172.16.100.10/24 | Host WAN |

## Konfigurasi Tiap Perangkat

### 1. Mikrotik

### 2 Fortigate

### 3. Cisco

### 4. Client LAN

### 5. Client WAN

## 3. Hasil Pengujian

### 1. Pengujian client lan ke gateway cisco

![Image](images/lankecisco.png)

### 2. Pengujian client lan ke fortigate

![Image](images/lankefortigate.png)

### 3. Pengujian client lan ke DMZ

![Image](images/lankedmz.png)

### 4. Pengujian client lan akses ip dmz

![Image](images/lankeweb.jpg)

### 5. Pengujian client wan ping ke isp mikrotik

![Image](images/wankemikrotik.jpg)

### 6. Penujian client wan ping ke fortigate

![Image](images/wankefortigate.jpg)

### 7. Pengujian client wan akses http://10.10.10.2

![Image](images/wankeweb.jpg)

### 8. Pengujian client wan ping client lan

![Image](images/wankelan.jpg)

### 9. Pengujian client wan ping IP asli DMZ

![Image](images/wankeipaslidmz.jpg)

### 10. Pengujian server dmz ping lan

![Image](images/dmzkelan.png)
