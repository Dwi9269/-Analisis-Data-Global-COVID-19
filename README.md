# -Analisis-Data-Global-COVID-19
Proyek ini mengeksplorasi data COVID-19 dari Januari 2020 hingga Februari 2024, menganalisis lebih dari 380.000 records di berbagai negara dan benua. Analisis fokus pada metrik utama termasuk tingkat infeksi, statistik kematian, dan progress vaksinasi.

Sumber Dataset: https://www.kaggle.com/datasets/ujjwalinsights/covid-19-data-analysis-with-sql

📈 Temuan Utama
Statistik Global
Total Kasus: 774,8 Juta
Total Kematian: 7,0 Juta
Tingkat Kematian Global: 0,90%

Insights Khusus Indonesia
Total Kasus: 6,83 Juta (2,48% dari populasi terinfeksi)
Total Kematian: 162.050 kasus
Tingkat Kematian: 2,37% (jauh lebih tinggi dari rata-rata global)
Puncak Tingkat Kematian: Mencapai sekitar 3,5% pada pertengahan 2021 sebelum menurun
​
Analisis Regional
Tingkat Infeksi Tertinggi: Brunei (76,44% dari populasi)​
Kematian Terbanyak: Amerika Serikat (1,18 juta), diikuti Brazil (702K) dan India (533K)​
Benua Paling Terdampak: Amerika Utara dan Eropa menunjukkan jumlah kematian tertinggi​

Progress Vaksinasi
Vaksinasi Indonesia: Mencapai cakupan 119,98% (termasuk dosis booster) pada Mei 2022
​Kampanye vaksinasi berhasil dilaksanakan di seluruh benua mulai awal 2021

🛠️ Bahasa yang Digunakan
Database: SQLite (in-memory)
Bahasa: Python, SQL

Libraries:
pandas - Manipulasi data
sqlite3 - Operasi database SQL
matplotlib - Visualisasi data
Platform: Kaggle Notebook

🔍 Breakdown Analisis
1. Analisis Tingkat Kematian (Death Rate)
Insight Utama: Tingkat kematian Indonesia (2,37%) adalah 2,6x lebih tinggi dari rata-rata global (0,90%), mengindikasikan potensi tantangan sistem kesehatan atau perbedaan metode pelaporan.

2. Analisis Tingkat Infeksi (Infection Rate)
Insight Utama: Negara kepulauan kecil (Brunei, Cyprus, San Marino) menunjukkan tingkat infeksi tertinggi (>70%), sementara Indonesia menunjukkan tingkat infeksi 2,48%.
​
3. Kematian Berdasarkan Negara
Insight Utama: Top 3 negara berdasarkan kematian: Amerika Serikat (1,18 juta), Brazil (702K), India (533K). Indonesia berada di peringkat 11 dengan 162K kematian.
​

4. Analisis Progress Vaksinasi
Insight Utama: Indonesia mencapai cakupan vaksinasi >100% dengan memasukkan dosis booster, mendemonstrasikan kesuksesan kampanye vaksinasi nasional.
​

📊 Visualisasi
Proyek ini mencakup 5 visualisasi utama:
Persentase Kematian Indonesia dari Waktu ke Waktu - Menunjukkan penurunan dari puncak 3,5% ke 2,37%​
Top 20 Negara Berdasarkan Tingkat Infeksi - Bar chart yang menyoroti tingkat tinggi negara-negara kecil​
Top 20 Negara Berdasarkan Jumlah Kematian - Horizontal bar chart kematian absolut​
Jumlah Kematian Berdasarkan Benua - Perbandingan antar benua​
Progress Vaksinasi Indonesia - Timeline rollout vaksinasi mencapai 120%​

💡 Teknik SQL yang Didemonstrasikan
Operasi JOIN kompleks antara tabel deaths dan vaccination
Window functions (PARTITION BY, ORDER BY) untuk rolling calculations
Aggregate functions (SUM, MAX, COUNT, AVG)
Type casting (CAST) untuk kalkulasi akurat
Filtering dan grouping data
CTEs (Common Table Expressions) untuk organisasi query
Handling NULL values dan data cleaning

📝 Insights & Kesimpulan
Variabilitas Dampak Pandemi: Tingkat kematian bervariasi signifikan antar negara (0,90% global vs 2,37% Indonesia), mengindikasikan perbedaan infrastruktur kesehatan, standar pelaporan, atau demografi.
Negara Kecil Paling Terdampak: Negara kepulauan dengan kepadatan populasi tinggi (Brunei, Cyprus) mengalami tingkat infeksi tertinggi (>70% populasi).
Kesuksesan Vaksinasi: Kampanye vaksinasi global berhasil dilaksanakan, dengan banyak negara termasuk Indonesia mencapai cakupan >100% melalui program booster.
Tren Temporal: Tingkat kematian mencapai puncak pada pertengahan 2021 dan menurun secara bertahap, kemungkinan karena upaya vaksinasi dan protokol perawatan yang lebih baik.
Disparitas Benua: Amerika Utara dan Eropa menanggung beban kematian absolut tertinggi, sementara Asia menunjukkan mortalitas per-kapita yang lebih rendah meskipun kepadatan populasi tinggi.
​

Implikasi Bisnis/Kebijakan
Sistem kesehatan di negara dengan tingkat kematian lebih tinggi mungkin memerlukan peningkatan infrastruktur
Wilayah kecil dengan populasi padat memerlukan strategi intervensi yang ditargetkan
Program vaksinasi terbukti efektif mengurangi outcome yang parah
Kerja sama internasional dan sharing data tetap krusial untuk respons pandemi

​





