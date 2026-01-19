---
layout: ../../layouts/LayoutBlog.astro
title: "Astro Untuk Blog"
date: "2025-12-26"
image: "https://images.unsplash.com/photo-1504691342899-4d92b50853e1?q=80&w=1170&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
description: "Mempelajari  Astro untuk membangun blog yang lebih performan."
---
# Kenapa Astro?
Astro adalah framework web modern yang dirancang khusus untuk membangun situs web yang berfokus pada konten dengan kecepatan yang luar biasa. Astro sangat cepat karena tidak ada JavaScript yang tidak perlu. Ini adalah pilihan tepat untuk blog pribadi.
Astro tidak memaksa kamu menggunakan satu library saja. Kamu bisa menggunakan komponen dari berbagai framework populer seperti :
React,Vue,Svelte,SolidJS atau hanya komponen .astro standar.

#
Membuat blog modern dengan Astro, Decap CMS, GitHub, dan Cloudflare Pages adalah kombinasi yang sangat kuat.
Karena Decap CMS butuh izin untuk menulis ke GitHub, kamu perlu  OAuth.
Buka GitHub Settings > Developer Settings > OAuth Apps > New OAuth App.
Isi Homepage URL dengan URL blog kamu.
Isi Authorization callback URL (biasanya kamu butuh bantuan backend kecil seperti decap-cms-cloudflare-oauth atau menggunakan layanan pihak ketiga).
Masukkan Client ID dan Client Secret tersebut ke dalam Environment Variables di Cloudflare Pages.

#
Keuntungan Setup Ini adalah Astro menghasilkan  HTML statis yang sangat cepat dan tanpa Database. Semua konten tersimpan sebagai file .md atau .mdx di GitHub