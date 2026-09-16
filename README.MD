# HELLO

## Module

Backend 1 - Data & Database: cari, bersihin, dan strukturin dataset (dari OWID/Poore & Nemecek), desain skema tabel (foods, categories, emission values), bikin seeder/migration. Deliverable: database siap pake + dokumentasi skema field.

Backend 2 - Core API: bikin endpoint utama - GET /foods (list + pagination), GET /foods/:id (detail), search, filter by kategori, sort by nilai emisi. Deliverable: REST API dengan dokumentasi (Postman collection atau Swagger).

Backend 3 - Fitur ekstensi & logic: endpoint comparison (compare beberapa makanan sekaligus), validasi input, error handling, dan kalau tim mutusin ada fitur kalkulator/admin, ini yang megang. Kalau fitur ekstensi itu di-skip, orang ini bisa dobel bantu di Backend 2 atau megang testing API.

Frontend 1 - List & search view: halaman utama, grid/list makanan, search bar, filter kategori, sorting, pagination. Fokus di data fetching dari endpoint list.

Frontend 2 - Detail & comparison view: halaman detail per makanan (breakdown emisi kalau ada), fitur comparison side-by-side, plus visualisasi (bar chart atau color scale hijau-merah).

Frontend 3 - Layout, styling & halaman pendukung: navigasi, responsive design, shared component (biar Frontend 1 & 2 konsisten visualnya), plus halaman tambahan kayak landing page atau metodologi data.
