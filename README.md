<h1>Aplikasi Akademik Unkroka</h1>
<p>Aplikasi Akademik Unkroka adalah aplikasi web yang dibangun menggunakan framework Laravel. Aplikasi ini digunakan oleh Universitas Krotek Merdeka (Unkroka) untuk mengelola data mahasiswa, data dosen, data mata kuliah, jadwal kuliah, nilai, dan absensi.</p>

<h2>Fitur</h2>
<p>Aplikasi Akademik Unkroka memiliki fitur sebagai berikut:</p> 
  <ol>
    <li>Manajemen Data Siswa: Aplikasi ini memungkinkan pengelolaan data siswa seperti data pribadi, data orang tua, riwayat kesehatan, dan catatan akademik siswa.</li>
    <li>Manajemen Data Dosen: Aplikasi ini memungkinkan pengelolaan data dosen seperti data pribadi, dan catatan akademik dosen.</li>
    <li>Manajemen Data Mata Kuliah: Aplikasi ini memungkinkan pengelolaan data Mata Kuliah.</li>
    <li>Jadwal Kuliah: Aplikasi ini menyediakan fitur untuk membuat jadwal Kuliah yang fleksibel dan mudah diakses oleh dosen dan mahasiswa.</li>
    <li>Nilai dan Absensi: Aplikasi ini memungkinkan penginputan dan pengelolaan nilai serta absensi siswa secara mudah dan teratur.</li>
    <li>Laporan Akademik: Aplikasi ini memungkinkan pembuatan laporan akademik siswa seperti rapor, transkrip nilai, dan sertifikat.</li>
  </ol>

<h2>Cara Menggunakan Aplikasi</h2>
<p>Untuk menggunakan aplikasi ini, pengguna harus terlebih dahulu mendaftar dan login ke dalam aplikasi. Setelah login, pengguna akan diarahkan ke halaman utama aplikasi yang memuat informasi dasar seperti data mahasiswa, jadwal kuliah, nilai, dan absensi. Untuk mengakses fitur lainnya, pengguna dapat memilih menu yang tersedia di bagian atas halaman.</p>

<h2>Teknologi yang Digunakan</h2>
<p>Aplikasi ini dikembangkan menggunakan teknologi sebagai berikut:</p>
<ol>
  <li>Backend: Aplikasi ini menggunakan PHP sebagai bahasa pemrograman backend dengan framework Laravel. Database yang digunakan adalah MySQL.</li>
  <li>Frontend: Aplikasi ini menggunakan Blade sebagai bahasa pemrograman frontend. UI/UX framework yang digunakan adalah Bootstrap.</li>
  <li>Authentication: Aplikasi ini menggunakan Laravel Authentication untuk melakukan otentikasi pengguna.</li>
</ol>

<h2>Instalasi</h2>
<p>Berikut adalah langkah-langkah untuk menginstal Aplikasi Akademik Unkroka:</p>

<ol>
  <li>Clone repository ini <a href="https://github.com/aldistate/akademik-kroka.git">https://github.com/aldistate/akademik-kroka.git</a> atau download repository ini dan extract ke dalam folder yang diinginkan.</li>
  <li>Jalankan perintah 'composer install' pada terminal di folder aplikasi.</li>
  <li>Salin file .env.example menjadi .env , jalankan perintah 'cp .env.example .env' pada terminal</li>
  <li>Buat key baru untuk aplikasi, jalankan perintah 'php artisan key:generate' pada terminal</li>
  <li>Buatlah sebuah database baru di MySQL dengan nama '2023_unkroka'.</li>
  <li>Buka file .env dan ubah konfigurasi database sesuai dengan database yang sudah dibuat.</li>
  <li>Jalankan migrasi database, dengan perintah 'php artisan migrate'</li>
  <li>Jalankan server development, dengan perintah 'php artisan serve'</li>
  <li>Buka web browser dan akses http://localhost:8000 untuk membuka aplikasi.</li>
</ol>


<!-- <h2>Penggunaan</h2>
<p>Untuk menggunakan aplikasi Pembayaran Air, ikuti langkah-langkah berikut:</p>

<ol>
  <li>Buka aplikasi melalui web browser dengan mengakses http://localhost:8000.</li>
  <li>Pada halaman utama, akan terdapat tabel daftar pelanggan yang sudah terdaftar.</li>
  <li>Untuk menambahkan data pelanggan baru, klik tombol "Tambah Pembayaran Air" pada bagian atas tabel.</li>
  <li>Isikan data pelanggan pada form yang muncul dan klik tombol "Create Tagihan".</li>
  <li>Data pelanggan baru akan muncul pada tabel di halaman utama.</li>
  <li>Untuk melihat detail tagihan pelanggan, klik tombol bergambar mata pada kolom aksi pada tabel pelanggan.</li>
  <li>Pada halaman detail tagihan, akan ditampilkan informasi detail tagihan pelanggan.</li>
  <li>Untuk mengedit data pelanggan, klik tombol bergambar pensil pada kolom aksi pada tabel pelanggan di halaman utama.</li>
  <li>Pada halaman edit pelanggan, ubah data pelanggan dan klik tombol "Update Tagihan".</li>
  <li>Data pelanggan akan terupdate pada tabel di halaman utama.</li>
  <li>Untuk menghapus data pelanggan, klik tombol bergambar tong sampah pada kolom aksi pada tabel pelanggan di halaman utama.</li>
</ol> -->
<br>
<p>Demikianlah README.md untuk Aplikasi Akademik Unkroka menggunakan Laravel versi 9 dan MySQL. Semoga tutorial ini bisa membantu teman-teman yang ingin belajar bagaimana membuat Aplikasi Akademik Unkroka sederhana dengan Laravel dan MySQL, serta bagaimana membuat API dan mengintegrasikannya dengan UI Bootstrap. Jangan ragu untuk mengembangkan aplikasi ini lebih jauh, menambahkan fitur baru, atau memperbaiki kode yang ada untuk meningkatkan performa dan fungsionalitasnya. Terima kasih telah membaca, semoga bermanfaat!</p>