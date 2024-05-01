# UTS Cloud Computing
 Coding socket

code untuk mengirim ke client:
![image](https://github.com/RizkiaMeisya/UTS-Cloud-Computing/assets/132799407/10b5f123-a372-4b66-84d9-010e8f575cd3)

a) Fungsi socket.socket() digunakan untuk membuat socket
sintaks umum dari fungsi socket 
s=socket.socket(socket_family, socket_type, protocol=0)

b) s.bind() digunakan untuk mengikat alamat (nama host, nomor port)

c) s.listen() digunakan untuk mengatur dan memulai pendengar TCP

d) s.accept() digunakan untuk menerima koneksi klien TCP

**cara dalam membuat** 
1. buat socket dengan cara mengimport metode socket kelas socket (import socket)
2. Ikat socket ke port
3. Mulai menerima koneksi pada socket

**menerima paket data**
1. Pastikan python telah terinstal pada system
2. Jalankan code menerima.py dengan perintah python menerima.py 
![Alt text](/screenshoot/menjalankan_code_menerima_py.png?raw=true)
3. Lakukan request terhadap socket yang sudah diatur dengan mengakses localhost:port (localhost:10013) pada browser
4. Informasi terkait request akan muncul pada shell
![Alt text](/screenshoot/setrelah_melakukan_request.png?raw=true)
