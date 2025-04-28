# Arsitektur-Multiple-Prosessor-dan-Multiprosessor-Symmetric

Nama : Inayah Humairoh Albaista

Kelas : SKU 2B

NIM : 09011382429130

Penjelasan dari gambar arsitektur 

1. Arsitektur Multiple Processor

   ![Screenshot 2025-04-28 134138](https://github.com/user-attachments/assets/48eb1718-de5b-42eb-adac-3368dc31a375)


Pada gambar pertama, terlihat arsitektur Multiple Processor. Dalam sistem ini, terdapat banyak CPU, masing-masing memiliki cache L1 sendiri untuk menyimpan data sementara. Semua CPU tersebut dihubungkan ke sebuah jalur utama atau sistem interkoneksi yang mengarah ke berbagai komponen penting seperti Shared L2 Cache, Memory Controller, Main Memory (RAM), Interrupt Controller, dan IPC (Inter-Process Communication). Di dalam arsitektur ini, setiap CPU bisa mengerjakan tugasnya sendiri-sendiri, namun tetap harus berkoordinasi satu sama lain. Untuk itu, digunakan IPC yang berfungsi membantu CPU berkomunikasi dan bertukar data dengan cepat, sehingga kerja antar CPU tetap sinkron. Interrupt Controller juga berperan penting dalam mengatur sinyal gangguan dari perangkat luar, menentukan CPU mana yang harus menangani permintaan tertentu. Arsitektur Multiple Processor biasanya digunakan pada sistem-sistem besar seperti superkomputer, server kelas berat, dan data center, di mana pekerjaan yang harus diselesaikan sangat banyak dan membutuhkan tenaga komputasi paralel yang besar. Walaupun memungkinkan banyak CPU bekerja bersama-sama, sistem ini menjadi lebih rumit karena harus mengatur komunikasi dan sinkronisasi di antara prosesor secara ketat.

2. Arsitektur Multiprocessor symmetric

   ![Screenshot 2025-04-28 134224](https://github.com/user-attachments/assets/b9d1a476-fffe-4099-a71c-1eac8fda222f)


pada gambar kedua diperlihatkan arsitektur Multiprocessor Symmetric atau biasa disingkat SMP. Pada sistem ini, beberapa CPU memiliki hak akses yang sama terhadap memori dan perangkat input-output (I/O). Dalam gambar tersebut, Processor A dan Processor B sama-sama bisa langsung menjalankan Operating System dan User Thread tanpa harus meminta izin atau bergantung pada CPU lain. Tidak ada pembagian tugas yang kaku, karena semua CPU diperlakukan sama. Ini membuat pembagian kerja menjadi fleksibel dan mempercepat proses multitasking. Karena berbagi memori dan I/O, struktur sistem menjadi lebih sederhana dibandingkan multiple processor. Arsitektur symmetric ini biasanya digunakan untuk server kecil hingga menengah, workstation untuk pekerjaan desain atau editing video, serta komputer yang membutuhkan multitasking berat. Kelebihan dari sistem ini adalah mudah diatur dan stabil. Namun, kelemahannya adalah keterbatasan dalam skalabilitas. Jika jumlah CPU terlalu banyak, bisa terjadi kemacetan karena semua prosesor menggunakan jalur memori yang sama, sehingga sistem menjadi kurang efisien.

Dengan membandingkan kedua arsitektur ini, dapat disimpulkan bahwa Multiple Processor lebih cocok digunakan untuk kebutuhan pemrosesan skala besar yang memerlukan banyak CPU bekerja secara bersamaan dengan sistem komunikasi yang kompleks. Sementara itu, Multiprocessor Symmetric lebih sesuai untuk sistem yang membutuhkan multitasking cepat dan stabil dalam skala yang lebih kecil atau menengah. Memahami perbedaan kedua arsitektur ini sangat penting agar dapat memilih jenis sistem yang paling sesuai dengan kebutuhan kerja dan karakteristik beban yang harus ditangani.



