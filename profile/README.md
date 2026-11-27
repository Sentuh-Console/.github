# Sentuh Console

**Internal developer platform untuk PT Sentuh Digital Teknologi.** Sentuh Console membantu tim mengelola project dan environment, serta layanan infrastruktur yang digunakan aplikasi dan perangkat.

## Repositori

| Repositori | Deskripsi | Teknologi utama |
|---|---|---|
| [console](https://github.com/Sentuh-Console/console) | Aplikasi web dan API Sentuh Console | Next.js, React, TypeScript, PostgreSQL, Drizzle ORM |
| [service](https://github.com/Sentuh-Console/service) | Layanan backend untuk broker dan messaging | Go, PostgreSQL, EMQX, RabbitMQ |

## Kapabilitas

- Organisasi, project, anggota, peran, dan environment.
- Pengelolaan layanan MQTT melalui EMQX dan messaging AMQP melalui RabbitMQ.
- Pengaturan resource dan akses per project dan environment.
- API internal yang menghubungkan console dengan layanan backend.

## Mulai berkontribusi

1. Pilih repositori sesuai area yang ingin dikerjakan dan baca README di dalamnya.
2. Gunakan issue untuk melaporkan bug atau mengusulkan perubahan.
3. Buat perubahan dalam branch terpisah dan ajukan pull request dengan ringkasan serta langkah verifikasi.
4. Jangan masukkan file `.env`, token, password, cookie sesi, atau kredensial aktif ke commit, issue, maupun pull request.

Detail cara menjalankan aplikasi, konfigurasi lokal, dan deployment tersedia di README masing-masing repositori.

---

Dibangun dan dikembangkan bersama oleh tim Sentuh.
