# ppwl3

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.3.8. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.

# Praktikum 2 #
Berdasarkan pengamatan dari `play.tailwindcss.com`, dapat ditemjkan 2 perbedaan utama antara Tailwind CSS v3 dan v4 yaitu :
1. Tailwind CSS v4 menggunakan konfigurasi berbasis CSS dengan directive
   `@theme`, sedangkan Tailwind CSS v3 menggunakan file konfigurasi
   `tailwind.config.js`.
2. Tailwind CSS v4 tidak memerlukan setup PostCSS dan konfigurasi tambahan,
   cukup menggunakan `@import "tailwindcss"`, sehingga lebih ringan dan cepat
   dibandingkan Tailwind CSS v3 yang wajib ada PostCSS, tailwind.config.js, dan autoprefixer.

# Praktikum 4 #
Komponen box model yang terpengaruh oleh background color (bg-blue-600) pada Tailwind CSS adalah content dan padding. Background color tidak mempengaruhi margin karena margin berada di luar elemen.