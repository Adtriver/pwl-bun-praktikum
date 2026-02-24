# ppwl3

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.3.9. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.

Sintaks Import CSS. Di v3 editor menggunakan tiga direktif terpisah (@tailwind base, @tailwind components, @tailwind utilities), sedangkan v4 cukup satu baris: @import "tailwindcss".

Konfigurasi Tema. Di v3 ada tab Config dengan tailwind.config.js berbasis JavaScript. Di v4, tab Config digantikan oleh pendekatan CSS-first menggunakan direktif @theme { } langsung di CSS editor — tidak perlu file JS config lagi.

Jika memberi warna pada latar belakang elemen, cth. bg-blue-600, maka Komponen box model yang terpengaruh warna latar adalah content dan padding.

https://drive.google.com/file/d/1Vlvoz-cWAo-96kk_S_ZIQXDVUf21p4Gd/view?usp=drive_link