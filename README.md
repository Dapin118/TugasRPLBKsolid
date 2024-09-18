# TugasRPLBKsolid

Prinsip Dependency Inversion Principle (DIP) merupakan salah satu dari lima prinsip SOLID dalam desain perangkat lunak. DIP menekankan bahwa modul tingkat tinggi (yang berisi logika utama aplikasi) tidak boleh bergantung langsung pada modul tingkat rendah (seperti layanan spesifik). Keduanya harus bergantung pada abstraksi (misalnya, antarmuka), yang memberikan fleksibilitas dan meningkatkan skalabilitas sistem.
Dalam contoh berikut, kita akan melihat bagaimana DIP diterapkan dalam konteks pemesanan sederhana, di mana pesanan pelanggan dikirimkan ke kasir melalui email. Program ini memproses pemesanan dan menggunakan layanan email untuk mengirim notifikasi kepada kasir, mencatat semua detail pesanan yang diterima.
