# Pertemuan kedua(Komputasi Awan dan Sistem Terdistribusi)

## Oracle Cloud Infrastructure (OCI) Core Services

OCI Core Services meliputi 5 hal yaitu:

1. Compute 
  - bare metal berupa blank server sehingga pengguna harus menangani virtualisasi, operating system, language runtime, app container dan code.
  - dedicated virtual host merupakan single tenant model
  - virtual machines
  - container engine 
  - function

2. Storage
Komputasi pada aplikasi membutuhkan penyimpanan dengan spesifikasi tertentu. Berikut adalah storage model OCI, yaitu:
- Mendukung persistent and non persistent storage
- Multiple format seperti data terstruktur, semi-terstruktur dan streaming
- High Performance Computing dengan biaya yang rendah
- Data dilindungi dari kerusakan perangkat keras
- Data dapat disimpan di lokal untuk keperluan sendiri atau di remote storage untuk keperluan berbagi data
- Data diakses menggunakan protokol tertentu.

layanan penyimpanan yang didukung oleh OCI yaitu block volume, local NVME, file storage, object storage dan archive storage.

3. Networking
VCN merupakan network yang dimiliki oleh VM dan juga merupakan layanan Infrastructures as a Service (IaaS).
berfungsi untuk mengatur jaringan yang ada di lingkungan cloud. 
Manfaat  Virtual Cloud Network ( VCN ) yaitu: 
- Untuk memperluas jaringan lokal ke Oracle Cloud. 
- Meningkatkan keamanan pada jaringan VM. 
- Mengatur lalu lintas data yang masuk dan juga keluar .

Beberapa komponen yang terdapat dalam VCN, yaitu Subnets, Route Table, Security List, Internet Gateway, Nat Gateway, Service Gateway, Dynamic Router Gateway.


4. Identity and Access Management (IAM)
IAM policy adalah dokumen yang menentukan siapa dan bagaimana cara yang dapat digunakan untuk mengakses sumber daya. 

5. Database Cloud Service
Oracle adalah satu-satunya cloud publik yang mendukung sistem database VM, yang menawarkan penyediaan yang sangat cepat. 
