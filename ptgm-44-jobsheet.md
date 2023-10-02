# Pemrogaman Teks, Grafis dan Multimedia

`Materi 4.4`: Rancang Kebutuhan Sistem (bagian 2) / Menerapkan Metode _System Requirement_

`Jobsheet sebelumnya`: [PTGM 6: Rancang Kebutuhan Sistem - Perpus Digital (bagian 1)](https://classroom.google.com/u/5/c/NjE3OTU4MDMwNTcz/m/NjI0MjczNDAzNDU1/details)

`Jobsheet 2`: Implementasi membuat proyek **Catatan Pengunjung Perpustakaan** dengan [Nuxt.js](https://nuxt.com)

`Capaian`: Siswa dapat melakukan Setup dan memahami struktur folder proyek

## 🤔 Apa itu Nuxt.js?

- [Nuxt.js](https://nuxt.com) adalah web framework yang dibangun diatas Vue.js. 
- Framework ini support menggunakan bahasa JavaScript dan TypeScript.

## 👨🏻‍🍳 Prasyarat

Pastikan [Node.js](https://nodejs.org) terpasang pada komputer.

## 🛠 Setup

- Buka Cmd/Terminal
- Masuk ke folder **_Kalian_** (reference: [flow.zulhilmi.id](https://flow.zulhilmi.id))
- Buat proyek dengan `nuxt` dan beri nama `perpus-digital`

```bash
npx nuxi init perpus-digital
```

- Ketik **y** dan Enter jika muncul pertanyaan

  Tunggu beberapa saat

- Masuk ke `perpus-digital`

```bash
cd perpus-digital
```

- Install dependencies

```bash
npm i
```

## 🌐 Development Server

Jalankan _development server_ di [http://localhost:3000](http://localhost:3000)

```bash
npm run dev
```

## 📂 Struktur Folder

```bash
perpus-digital/
├── README.md
├── app.vue
├── node_modules/
├── .nuxt/
├── nuxt.config.ts
├── package.json
├── public/
│   └── favicon.ico
├── server/
│   └── tsconfig.json
└── tsconfig.json
```

Keterangan:

- `app.vue`: The app.vue file is the main component in your Nuxt 3 applications.
- `nuxt-config.ts`: File yang berisi konfigurasi Nuxt.
- `package.json`: The package.json file contains all the dependencies and scripts for your application.
- `public`: The public/ directory is directly served at the server root and contains public files that have to keep their names (e.g. robots.txt) or likely won't change (e.g. favicon.ico).
- `server`: Register API and server handlers with HMR support.
- `tsconfig.json`: Konfigurasi TypeScript.
- `node_modules`: Directory to store the dependencies of your project.
- `.nuxt`: Folder/direktori untuk _generate_ aplikasi Vue.

_sumber: [Struktur Direktori/Folder](https://nuxt.com/docs/guide/directory-structure/app)_
