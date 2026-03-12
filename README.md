# firebase_tutorial_auth

## 1. Langkah-langkah

**1. Login ke Firebase Console Dan Create Project**
- Buka [firebase.google.com](https://firebase.google.com/)
- Klik **"Go to console"** (pojok kanan atas)
- Pilih akun Google Anda
- Create New Project
<img width="1919" height="886" alt="image" src="https://github.com/user-attachments/assets/e797208f-8c16-4499-bcb4-457f651cca3e" />

**2. Menambahkan Web Di Bagian Project Setings Dan Mendapatkan API KEY**
- Klik Setings
- General
- Klik ADD WEB
- Mengisi Nama Project
- CARI API KEY
<img width="1920" height="900" alt="image" src="https://github.com/user-attachments/assets/cf6b5e87-5999-4918-961d-4668638df525" />

**3. Menambahkan Envirotment Di ApK POSTMAN**
- Buka Aplikasi Postman
- Add Environtment Baru
- Beri Nama Di Environtment
<img width="402" height="210" alt="image" src="https://github.com/user-attachments/assets/aabf4d19-1103-4afd-9d1d-e28622ec6e23" />

**4. Mengisi Envirotment**
- Tambahkan variable berikut:

| Variable | Value | Keterangan |
|----------|-------|------------|
| `FIREBASE_API_KEY` | `AIzaSyB_xxx...` | Web API Key dari Firebase Console |
| `FIREBASE_ID_TOKEN` | (diisi otomatis) | Diisi otomatis setelah login (via Test script) |
| `BACKEND_BASE_URL` | `http://localhost:8080/v1` | Base URL backend kamu |
| `BACKEND_TOKEN` | (diisi setelah verify) | Token JWT dari backend |
| `USER_EMAIL` | `test@example.com` | Email untuk testing |
| `USER_PASSWORD` | `Test@12345` | Password untuk testing |

<img width="1195" height="455" alt="image" src="https://github.com/user-attachments/assets/6a089b17-f28d-41d2-a92d-67745c55458f" />

**5. Konfigurasi Request**
- Endpoint
<img width="1191" height="117" alt="image" src="https://github.com/user-attachments/assets/318ef474-589a-4af9-b58f-e1ff0cdc747b" />

- Headers
<img width="1190" height="220" alt="image" src="https://github.com/user-attachments/assets/8dc1298c-1e00-489c-858a-e296c9c0d97b" />

- Request Body RAW
<img width="1189" height="240" alt="image" src="https://github.com/user-attachments/assets/1ec8f44a-b53c-4a77-85be-866e47dd9549" />

- Add Script Auto Save Token
<img width="1195" height="356" alt="image" src="https://github.com/user-attachments/assets/90087ae9-10e8-49d9-b068-1a983b4341e7" />

- 200 Endpoints
<img width="1083" height="311" alt="image" src="https://github.com/user-attachments/assets/bf58ea72-e792-4786-ac4d-af9f53e813fe" />

**6. ADD VERIVICATION REQUEST**
- Endpoint
<img width="1188" height="156" alt="image" src="https://github.com/user-attachments/assets/537a9170-d31b-4b01-913f-480ff067d75b" />

- Headers
<img width="1174" height="291" alt="image" src="https://github.com/user-attachments/assets/1cf24084-93ce-4f65-9d3c-4047fc013c03" />

- Request Body RAW
<img width="450" height="160" alt="image" src="https://github.com/user-attachments/assets/5d773b41-f91e-4d94-b751-e801ad446863" />

- Body jSON
<img width="884" height="197" alt="image" src="https://github.com/user-attachments/assets/935a679d-4d62-497b-a870-1c61ffefcdb1" />

**HASIL EMAIL VERIVICATION**
<img width="1910" height="975" alt="image" src="https://github.com/user-attachments/assets/2bbc354d-9b46-478a-898f-cda7bb9202c4" />
