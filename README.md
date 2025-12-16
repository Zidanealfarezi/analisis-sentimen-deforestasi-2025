Partai Deforestasi: Analisis Sentimen Publik & Akuntabilitas Politik
Latar Belakang

Di penghujung tahun 2025, Indonesia menghadapi krisis ekologis serius berupa banjir besar yang melanda Sumatra dan Aceh. Pada saat yang sama, narasi kebijakan kontroversial "Sawit Juga Pohon" memicu perdebatan hangat mengenai legalitas deforestasi dan perubahan tutupan hutan alam. Proyek ini menganalisis bagaimana publik di media sosial merespons krisis tersebut melalui label "Partai Deforestasi". Istilah tersebut muncul sebagai narasi kritik yang membenturkan janji politik saat ini dengan rekam jejak pemberian izin lahan berskala besar di masa lalu.

Temuan Kunci (Key Insights)

Sentimen negatif mendominasi (67,3%) – Mayoritas publik menolak pembenaran deforestasi dan menuntut tanggung jawab atas banjir yang terjadi. Sentimen negatif terhadap isu ini mencapai 67,3% dari percakapan yang dianalisis.

Target akuntabilitas politik – Nama-nama seperti AHY (181 sebutan) dan SBY (107 sebutan) muncul dominan dalam percakapan bernada negatif. Hal ini menunjukkan publik masih mengingat sejarah pemberian izin lahan skala besar di era mereka sebagai penyebab bencana ekologis saat ini.

Korelasi izin dan bencana – Kata kunci “izin” (378 kali) dan “bencana” (236 kali) kerap muncul bersamaan. Pola ini menandakan bahwa publik tidak lagi menganggap banjir sebagai fenomena alam semata, melainkan terkait erat dengan kebijakan perizinan lahan.

Resistensi terhadap sawit – Meskipun muncul narasi “sawit juga pohon”, sektor kelapa sawit (116 sebutan) tetap dipandang sebagai kontributor utama menurunnya daya dukung lingkungan. Publik masih menyoroti ekspansi sawit sebagai faktor penyebab hilangnya tutupan hutan yang memperparah bencana.

Metodologi

Analisis dilakukan menggunakan Python dengan alur kerja sebagai berikut:

Pengumpulan Data (Data Acquisition) – Menggunakan 560 cuitan Twitter publik dari Desember 2025 sebagai dataset utama untuk analisis.

Pra-pemrosesan Teks (Text Preprocessing) – Membersihkan teks dengan Regex untuk menghapus mention, hashtag, dan URL, serta normalisasi kata untuk meningkatkan akurasi analisis.

Analisis Sentimen Berbasis Leksikon (Lexicon-Based Sentiment Analysis) – Menerapkan kamus sentimen yang disesuaikan, termasuk kata-kata bernuansa politik seperti "pencitraan", "ironi", dan "eksploitasi", guna mengidentifikasi polaritas sentimen setiap cuitan.

Visualisasi Data (Data Visualization) – Menggunakan WordCloud untuk menampilkan kata kunci dominan, serta countplot Seaborn dan grafik bar untuk memetakan frekuensi penyebutan aktor politik dan istilah kunci terkait deforestasi.

Struktur File

Analisis_Deforestasi.ipynb – Notebook Jupyter utama yang memuat seluruh langkah pemrosesan data, analisis, dan visualisasi.

penggundulanhutan.csv – Dataset mentah (data cuitan Twitter) yang digunakan dalam analisis.

hasil_analisis_deforestasi_2025.csv – Dataset hasil yang berisi klasifikasi sentimen dan metrik keterkaitan kata kunci pasca-analisis.

Kesimpulan

Studi ini menunjukkan bahwa masyarakat digital di tahun 2025 telah bertransformasi menjadi pengawas berbasis data. Publik memanfaatkan rekam jejak kebijakan masa lalu untuk menilai aksi pemerintah saat ini, sehingga isu deforestasi berubah menjadi beban politik nyata bagi para aktor yang terlibat. Dengan kata lain, memori digital kolektif membuat para pengambil kebijakan harus lebih berhati-hati: kebijakan lingkungan yang buruk di masa lalu kini langsung ditagihkan pertanggungjawabannya ketika bencana ekologis melanda.
