# Progress 2 — Workflow Telegram → n8n → OpenAI

Progress ini menjelaskan pembuatan workflow Telegram Bot dengan n8n dan OpenAI.

## 1. Membuat Telegram Bot
1. Buka Telegram.
2. Cari BotFather.
3. Jalankan perintah `/newbot`.
4. Dapatkan BOT_TOKEN.

## 2. Menyiapkan Webhook URL
Gunakan URL dari ngrok: https://buford-tzaristic-elliana.ngrok-free.dev


## 3. Membuat Workflow di n8n
Node yang digunakan:
1. **Telegram Trigger**
2. **Set / Function**
3. **OpenAI**
4. **Telegram Send Message**

Alur:
Telegram → n8n → OpenAI → Telegram

## 4. Mengaktifkan Webhook Telegram
Gunakan browser:
https://api.telegram.org/bot
8473696587:AAGrPBC7SQhItgeql0aptCf0tZ_1xuu9lzs/setWebhook?url=<webhook_url_n8n>


## 5. Testing
- Kirim pesan ke bot Telegram
- Lihat execution di n8n
- Pastikan bot merespon jawaban dari OpenAI

## 6. File Workflow
File hasil export workflow disimpan di:

