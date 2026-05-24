# ✦ AI Chat

Chatbot sederhana berbasis Groq API. Dibangun dengan HTML, CSS, dan JavaScript murni — tanpa framework.

## Fitur

- Pilihan model: Llama 3.3 70B, Llama 3.1 8B, Gemma 2, Mixtral
- Chat multi-turn (ingat konteks percakapan)
- Render markdown & kode
- UI dark mode

## Cara setup

1. Buka file `index.html`
2. Cari baris berikut di bagian `<script>`:
   ```js
   let apiKey = 'ISI_API_KEY_GROQ_LO_DISINI';
   ```
3. Ganti dengan API key Groq lo dari [console.groq.com/keys](https://console.groq.com/keys)
4. Simpan

## Deploy ke Vercel

1. Push repo ini ke GitHub
2. Buka [vercel.com](https://vercel.com) → New Project → import repo ini
3. Klik Deploy — selesai

> **Catatan:** Jangan pernah commit API key ke GitHub. Kalau mau aman, gunakan environment variable atau taruh key di Vercel Environment Variables dan fetch via serverless function.
