# -Praktikum_Search_Algorithm-Informed-Search-
Informed search adalah salah satu metode pencarian dalam kecerdasan buatan (Artificial Intelligence) yang menggunakan heuristic untuk membimbing pencarian menuju solusi dengan lebih efisien dibandingkan metode uninformed search.

Karakteristik Informed Search:
Menggunakan informasi tambahan (heuristic)
Heuristic adalah perkiraan atau estimasi yang membantu menentukan jalur terbaik menuju solusi.
Misalnya, dalam pencarian rute di peta, heuristic bisa berupa jarak garis lurus ke tujuan.
Lebih efisien dibanding uninformed search
Tidak menjelajahi seluruh ruang pencarian secara membabi buta.
Fokus ke jalur yang lebih mungkin mengarah ke solusi.
Cocok untuk masalah dengan ruang pencarian besar
Misalnya, permainan catur, navigasi robot, atau pencarian rute terpendek dalam GPS.
Contoh Algoritma Informed Search
Greedy Best-First Search (GBFS)
Memilih simpul (node) yang memiliki nilai heuristic terbaik tanpa mempertimbangkan biaya total perjalanan.
Contoh fungsi heuristic: jarak langsung dari simpul ke tujuan (straight-line distance).
Cepat tetapi bisa tersesat di jalan buntu (lokal optimum).
A Search (A-Star)*
Menggabungkan heuristic dan biaya sejauh ini untuk menemukan jalur optimal.
