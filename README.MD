# Website tracker carbon footprint dari makanan

Web application untuk tracking carbon footprint dari makanan yang kita konsumsi sehari-hari..

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

## 📖 Terminologi
- **Carbon Footprint (Jejak Karbon):** Jumlah total gas rumah kaca (khususnya CO2) yang dihasilkan dari seluruh proses produksi, distribusi, dan konsumsi suatu makanan.
- **Daily Intake (Asupan Harian):** Daftar total makanan dan minuman yang dikonsumsi oleh seorang pengguna dalam satu hari.
- **Carbon Goals:** Target personal yang diatur oleh pengguna untuk membatasi jumlah maksimal emisi karbon dari makanan mereka.
- **Eco-Alternatives:** Saran makanan pengganti yang memiliki fungsi/rasa serupa namun menghasilkan jejak karbon yang secara signifikan lebih rendah.


## Modul

Status | Modul | Deskripsi | Penanggung jawab
-------|-------------------------------------|-------------------------------------------------------------------------------------------|-------------------------------------------------------
TODO   | Food Catalog & API                  | CRUD master data makanan (FoodItem), integrasi API/mock API, search/filter (AJAX)         | Regina Dibrya (https://github.com/reginadibryakerinne)
TODO   | Daily Intake Tracker                | CRUD catatan makan harian user (ConsumptionLog), filter per user, kalkulasi emisi         | William Orlando (https://github.com/williamorln)
TODO   | Carbon Goals & Targets              | CRUD target batas emisi karbon (CarbonGoal), progress bar tracker, filter per user        | Ilham Firmansyah (https://github.com/RedStone576)
TODO   | Custom Meals / Recipes              | CRUD paket makanan (CustomMeal), gabungan beberapa food item, kalkulasi total emisi       | Arsya Khairunissa (https://github.com/syakhrnss)
TODO   | Eco-Alternatives Forum / Tips       | CRUD forum saran makanan alternatif rendah karbon (FoodAlternative), public access        | Rafif Ananta (https://github.com/parmaung)


## Public API/mock API yang akan dipakai

TBA; Akan membuat sendiri dengan _scope_ emisi karbon di Jakarta/bahkan Indonesia.
