# Website tracker carbon footprint dari makanan

Web application untuk tracking carbon footprint dari makanan yang kita konsumsi sehari-hari.

## Deskripsi Aplikasi

Kita tidak bisa hidup tanpa makanan. Setiap hari, kita perlu memilih dan mengonsumsi makanan untuk memenuhi kebutuhan tubuh. Namun, pernahkah kita berpikir bahwa makanan yang kita konsumsi sehari-hari juga memiliki dampak terhadap lingkungan?

Setiap jenis makanan memiliki carbon footprint yang berbeda. Emisi karbon dapat dihasilkan dari berbagai tahapan dalam rantai makanan, mulai dari produksi bahan makanan hingga proses pengolahan dan distribusinya. Sayangnya, informasi mengenai carbon footprint makanan belum selalu mudah ditemukan atau digunakan dalam kehidupan sehari-hari. Padahal, memahami dampak dari makanan yang kita konsumsi dapat menjadi langkah awal untuk membangun pola konsumsi yang lebih sadar lingkungan. Oleh karena itu, aplikasi ini dikembangkan sebagai web application untuk membantu pengguna melacak dan memahami carbon footprint dari makanan yang mereka konsumsi sehari-hari.

Aplikasi ini menyediakan berbagai fitur yang membantu pengguna mulai dari mengenali makanan yang dikonsumsi hingga mengevaluasi pola konsumsi mereka. Melalui Food Catalog, pengguna dapat mengeksplorasi berbagai jenis makanan beserta informasi emisinya. Pengguna yang telah login dapat mencatat konsumsi sehari-hari melalui Daily Tracker, menyimpan riwayat konsumsi, serta menetapkan target emisi melalui Carbon Goals. Pengguna juga dapat meracik resep atau kombinasi makanan melalui Custom Meals dan berbagi maupun menemukan saran alternatif makanan melalui forum Eco-Alternatives.

## Peran pengguna

- User: 
    - login untuk menyimpan history dan goals mereka
    - Pengguna umum yang dapat mengeksplorasi katalog makanan
    - mencatat daftar konsumsi harian (*Daily Tracker*)
    - mengatur target emisi (*Carbon Goals*)
    - meracik resep/paket makanan (*Custom Meals*) 
    - berinteraksi di forum saran (*Eco-Alternatives*). 
- Admin: 
    - mengelola master data makanan di dalam *Food Catalog*
    - mengelola data emisi karbon 
    - mememoderasi forum.

## Terminologi
- **Carbon Footprint (Jejak Karbon):** Jumlah total gas rumah kaca (khususnya CO2) yang dihasilkan dari seluruh proses produksi, distribusi, dan konsumsi suatu makanan.
- **Daily Intake (Asupan Harian):** Daftar total makanan dan minuman yang dikonsumsi oleh seorang pengguna dalam satu hari.
- **Carbon Goals:** Target personal yang diatur oleh pengguna untuk membatasi jumlah maksimal emisi karbon dari makanan mereka.
- **Eco-Alternatives:** Saran makanan pengganti yang memiliki fungsi/rasa serupa namun menghasilkan jejak karbon yang secara signifikan lebih rendah.


## Modul

Status | Modul | Deskripsi | Penanggung jawab
-------|-------------------------------------|-------------------------------------------------------------------------------------------|-------------------------------------------------------
TODO   | Food Catalog & API                  | CRUD master data makanan (FoodItem), integrasi API/mock API, search/filter (AJAX)         | Regina Dibrya Kerinne Br Purba - 2506657296 (https://github.com/reginadibryakerinne)
TODO   | Daily Intake Tracker                | CRUD catatan makan harian user (ConsumptionLog), filter per user, kalkulasi emisi         | William Orlando - 2506657390 (https://github.com/williamorln)
TODO   | Carbon Goals & Targets              | CRUD target batas emisi karbon (CarbonGoal), progress bar tracker, filter per user        | Ilham Naufal Firmansyah - 2506532643 (https://github.com/RedStone576)
TODO   | Custom Meals / Recipes              | CRUD paket makanan (CustomMeal), gabungan beberapa food item, kalkulasi total emisi       | Arsya Khairunissa Budiman - 2506544076 (https://github.com/syakhrnss)
TODO   | Eco-Alternatives Forum / Tips       | CRUD forum saran makanan alternatif rendah karbon (FoodAlternative), public access        | Muhammad Rafif Ananta Marpaung - 2506585151 (https://github.com/parmaung)


## Public API/mock API yang akan dipakai

TBA; Akan membuat sendiri dengan _scope_ emisi karbon di Jakarta/bahkan Indonesia.

## Deployment

https://pws.cs.ui.ac.id/web/project/ilham.naufal/foodprint  
(foodprint == food carbon footprint xixixi)

## Link Figma

[Link Figma](https://www.figma.com/design/JzwVtphEMM1R7hcIT7Le1B/PTS?t=PJLSwtUSlqEdyDIW-1)
