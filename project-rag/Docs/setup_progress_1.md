# Progress 1 — Setup Infrastruktur Dasar

Progress ini berisi langkah-langkah instalasi dan persiapan tools untuk menjalankan n8n dan RAG.

## 1. Tools yang Diinstal
- Docker Desktop
- GitHub Desktop
- ngrok for Windows
- n8n (melalui Docker Desktop)
- Browser (Chrome/Edge)

## 2. Menjalankan n8n Melalui Docker Desktop
1. Buka Docker Desktop.
2. Pergi ke menu **Images**.
3. Cari image `n8nio/n8n`.
4. Klik **Pull** untuk mendownload image.
5. Setelah selesai, klik **Run**.
6. Atur:
   - Container name: n8n
   - Port: 5678 → 5678
   - Environment Variables:
     - N8N_BASIC_AUTH_ACTIVE=true
     - N8N_BASIC_AUTH_USER=admin
     - N8N_BASIC_AUTH_PASSWORD=admin123
7. Klik **Run** dan pastikan container berjalan.

## 3. Menjalankan ngrok
1. Buka cmd Windows.
2. Jalankan:
