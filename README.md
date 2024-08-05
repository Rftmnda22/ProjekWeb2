<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="news.css">
</head>
<body>
    <h1 class="news">Berita Acara Kampus</h1>
    <div class="gallery">
        <div class="photo-item">
            <img src="pkm-kc.jpg" alt="Deskripsi Foto 1">
            <p class="caption">Program Kreativitas Mahasiswa (PKM) merupakan program yang dirancang untuk mendorong mahasiswa mengembangkan ide-ide kreatif dan inovatif mereka dalam bentuk proyek nyata.
                Program ini bertujuan untuk meningkatkan kualitas dan kapasitas mahasiswa dalam berkontribusi kepada masyarakat melalui karya-karya inovatif. Salah satu sub-programnya adalah PKM-KC (Program Kreativitas Mahasiswa Karya Cipta), yang fokus pada penciptaan produk atau inovasi baru yang bermanfaat.</p>
        </div>
        <div class="photo-item">
            <img src="pkm-ki.jpg" alt="Deskripsi Foto 2">
            <p class="caption">Penilaian Kemajuan Pelaksanaan PKM (PKP2) yang dilaksanakan secara online melalui platform Zoom, merupakan forum tingkat nasional yang dikelola oleh Direktorat Jenderal Pembelajaran dan Kemahasiswaan (BELMAWA) yang berada di bawah Kementerian Riset, Teknologi, dan Pendidikan Tinggi Republik Indonesia.Kegiatan ini ditujukan untuk mengevaluasi ketercapaian pelaksanaan kegiatan oleh setiap tim PKM yang lolos pendanaan Tahun 2024.</p>
        </div>
        <div class="photo-item">
            <img src="penelitian.jpg" alt="Deskripsi Foto 3">
            <p class="caption">Lokarya penyusunan Roadmap penelitian oleh prodi sistem Informasi digelar di Grand Dmaleo Hotel 25 juli 2024. Hadir dalam kegiatan ini jajaran pimpinan dan kaprodi dari UHM beserta para peserta yaitu dosen sistem informasi dan tambahan peserta dosen tamu dari Undipa.</p>
        </div>
        
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}
.news{
    text-align: center;
    color: rgb(6, 103, 103);
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}

.photo-item {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    margin: 10px;
    overflow: hidden;
    width: 300px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.photo-item img {
    width: 100%;
    height: auto;
    display: block;
}

.caption {
    padding: 10px;
    text-align: center;
    color: #333;
    font-size: 16px;
}
