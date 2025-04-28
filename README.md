# Arsitektur-Multiple-Prosessor-dan-Multiprosessor-Symmetric

Nama : Inayah Humairoh Albaista

Kelas : SKU 2B

NIM : 09011382429130

Penjelasan dari gambar arsitektur 

1. Arsitektur Multiple Processor

Pada gambar pertama, ditunjukkan arsitektur Multiple Processor. Dalam sistem ini, terdapat banyak CPU yang masing-masing memiliki cache L1 sendiri. Semua CPU tersebut dihubungkan melalui sebuah jalur utama atau sistem interkoneksi. Jalur ini menghubungkan CPU ke berbagai komponen penting seperti Shared L2 Cache, Memory Controller, Main Memory (RAM), Interrupt Controller, dan IPC (Inter-Process Communication).

Di arsitektur Multiple Processor, setiap CPU dapat mengerjakan tugasnya masing-masing. Namun, mereka perlu berkomunikasi melalui jalur bersama agar tidak terjadi tabrakan atau kekacauan dalam penggunaan memori. Karena itu, ada IPC yang membantu mengatur komunikasi antar CPU, serta Interrupt Controller yang mengatur sinyal gangguan dari perangkat luar. Model ini biasanya digunakan untuk sistem yang sangat besar, seperti server besar, superkomputer, atau pusat data. Sistem ini memungkinkan banyak pekerjaan berat bisa diselesaikan secara paralel, meskipun butuh pengaturan komunikasi yang cukup rumit antar CPU.

2. Arsitektur Multiprocessor symmetric

pada gambar kedua, diperlihatkan arsitektur Multiprocessor Symmetric (SMP). Di sini terdapat dua CPU, yaitu Processor A dan Processor B, yang bekerja dengan status yang sama. Keduanya bisa langsung mengakses memori utama dan perangkat I/O tanpa harus ada pembagian peran khusus. Baik Processor A maupun Processor B dapat menjalankan Operating System dan User Thread secara mandiri.

Sistem Multiprocessor Symmetric ini jauh lebih sederhana dibandingkan Multiple Processor. Karena semua CPU memiliki hak akses yang sama, pembagian tugas menjadi lebih fleksibel dan mudah. Sistem ini cocok digunakan pada server kecil hingga menengah, komputer multitasking, atau workstation untuk pekerjaan grafis, editing video, dan sejenisnya. Keuntungan utamanya adalah kemudahan pengelolaan dan stabilitas sistem, meskipun kemampuan untuk menambah jumlah CPU di sistem ini biasanya lebih terbatas dibandingkan multiple processor.


Dari kedua gambar tersebut, bisa disimpulkan bahwa Multiple Processor digunakan ketika beban kerja sangat besar dan membutuhkan banyak CPU yang bekerja secara bersamaan dengan koordinasi khusus, sedangkan Multiprocessor Symmetric lebih cocok untuk penggunaan umum yang membutuhkan kecepatan multitasking tanpa pengelolaan CPU yang rumit.

