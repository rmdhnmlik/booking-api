# booking-api
REST API BOOKING

# Notes
1. Cek application.propertis, sesuaikan databasenya
2. Buat Dockerfile untuk melakukan docker build
3. Buat docker-compose.yml untuk menjalankan aplikasi


# Menggunakan method POST pada postman
Buka postman pada tab Body, pilih opsi raw dan format JSON. kemudian masukan scrip berikut :

```bash
{
    "customerName": "John",
    "roomNumber": "100",
    "checkInDate": "2024-12-01",
    "checkOutDate": "2024-12-05"
}
```
