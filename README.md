# Tentang
Repositori ini bertujuan untuk mempermudah dalam mempelajari struktur jadi yang terbentuk dari susunan pemahaman REST API CRUD menggunakan Node.JS, PRISMA dan PostgreSQL yang tulis menggunakan Typeskrip.

Anda dapat menguji rute dengan menggunakan:
👉 Rename file .env copy menjadi .env
```bash
npx ts-node src/index.ts
```

## Pendahuluan
Object Relational Mapper (ORM) adalah kerangka kerja yang menyediakan lapisan abstraksi di atas basis data untuk memfasilitasi interaksi dengan data yang berasal dari sumber data yang tidak kompatibel, dan mengelola kueri. Dalam pelajaran dasar ini, kita melihat cara membuat backend dengan Node.js, Prisma, dan instance docker dari database PostgreSQL.

Prisma adalah ORM sumber terbuka untuk Nodejs dan TypeScript yang ditulis dalam Rust. Ia berdiri dengan bangga di antara ORM Javascript lainnya seperti Sequelize, Bookshelf, Waterline, Objection, dan TypeORM. Ini terdiri dari 3 alat utama:

⏺ Prisma Client: Klien basis data yang dihasilkan secara otomatis dan tipe-aman.
⏺ Prisma Migrate: Pemodelan data deklaratif dan migrasi yang dapat disesuaikan.
⏺ Prisma Studio: GUI untuk melihat dan mengedit data di database Anda.

Alat-alat ini bertujuan untuk meningkatkan produktivitas pengembang aplikasi dalam alur kerja database mereka.

Prisma saat ini mendukung PostgreSQL, MySQL, SQLite, SQL Server (pratinjau) dan MongoDB (pratinjau).

## Prasyarat
Untuk mempraktikkan pelajaran ini, Anda harus memiliki yang berikut:
⏺ Node.js v10 hingga terbaru diinstal di komputer Anda.
⏺ PostgreSQL v13 atau yang terbaru sedang berjalan yang dapat dengan mudah diatur dengan Docker.
⏺ Opsional, VsCode.

## Pengaturan data di database
Anda dapat memanipulasi catatan di Database Postgres menggunakan Prisma Studio dengan menjalankan:
```bash
npx prisma studio
```






# 