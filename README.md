Pemrograman Berbasis Jaringan Menggunakan Node.JS: Langkah-langkah Kerja
A. Persiapan:

Instalasi Git:

Unduh dan instal Git dari https://git-scm.com/.
Inisialisasi Repositori Git:

Buka terminal di Visual Studio Code.
Pindah ke direktori proyek dengan perintah cd path/to/your/project.
Jalankan git init untuk menginisialisasi repositori Git.
Menambah dan Melacak Berkas:

Buat file .gitignore dan masukkan node_modules/.
Jalankan git add . untuk menambahkan perubahan.
Jalankan git commit -m "Init commit" untuk menyimpan perubahan awal.
Menggunakan Branch:

Gunakan git branch untuk melihat daftar branch.
Buat branch baru dengan git checkout -b nama-branch.
Lakukan perubahan pada branch dan commit.
Merge dan Conflict Resolution:

Kembali ke branch utama (main) dengan git checkout main.
Gunakan git merge nama-branch untuk menggabungkan perubahan.
Selesaikan konflik jika diperlukan.
Remote Repository (GitHub):

Buat repository baru di GitHub.
Hubungkan repository lokal dengan GitHub: git remote add origin https://github.com/username/repository.git.
Push ke GitHub: git push -u origin main.
B. Proses Deployment:

Perubahan pada Kode Aplikasi:

Pastikan aplikasi Node.JS dapat berjalan di lingkungan production.
Sesuaikan konfigurasi port agar sesuai dengan lingkungan produksi.
Continuous Deployment dengan GitHub Actions:

Buat file konfigurasi GitHub Actions (.github/workflows/main.yml) untuk otomatisasi deployment.
Definisikan langkah-langkah deployment dan tes.
Hosting dengan Cyclic:

Registrasi di https://www.cyclic.sh/.
Sambungkan akun GitHub dengan Cyclic.
Pilih proyek aplikasi dan sambungkan dengan Cyclic.
Update Aplikasi ke Cyclic:

Buka file package.json dan atur script start dan port.
Tes aplikasi secara lokal dengan npm run start.
Tambahkan port dan script pada app.js dan app.js sesuai kebutuhan.
Git Commit dan Push:

Lakukan commit dan push perubahan ke GitHub.
Periksa GitHub Actions untuk memastikan proses CI/CD berjalan dengan baik.
Cek Aplikasi di Cyclic:

Cek status deployment di Cyclic dan pastikan aplikasi berjalan dengan baik di URL yang diberikan.
