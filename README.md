# Mekanbul Backend

🔗 **Demo:** [https://mekanbul-backend-bice.vercel.app/](https://mekanbul-backend-kohl.vercel.app/)

Bu depo, **mekanbul-backend** uygulamasının basit bir **Node.js**, **Express** ve **Mongoose** kullanılarak geliştirilmiş arka yüz (backend) uygulamasıdır.

---

## Kısa Açıklama

Bu backend API'sinin temel özellikleri şunlardır:

* **Mekan (Venue) Verileri Yönetimi:** API, mekan verileri üzerinde **listeleme**, **ekleme**, **görüntüleme**, **güncelleme** ve **silme** (CRUD) işlemlerini gerçekleştirir.
* **Veritabanı:** **MongoDB Cloud** (Atlas) servisini kullanır. Veritabanı bağlantı bilgileri ve şema detayları için: (`app_api/models/db.js`).

---

## Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin.

1. Projenin bulunduğu dizine gidin:

```bash
cd /path/to/backend 
# Veya projenizin yerel yolu
```

2. Gerekli tüm Node.js bağımlılıklarını (dependencies) yükleyin:

```bash
npm install
```

---

## Uygulamayı Çalıştırma

Bağımlılıklar yüklendikten sonra, uygulamayı başlatmak için aşağıdaki komutu kullanın:

```bash
npm start
```

---

## API Endpoints

Uygulama aşağıdaki rota (route) ve HTTP metotlarını destekler:

* **Tüm mekanları listele:** `GET /api/venues`
* **Yeni mekan ekle:** `POST /api/venues`
* **Mekan detayını getir:** `GET /api/venues/:venueid`
* **Mekanı güncelle:** `PUT /api/venues/:venueid`
* **Mekanı sil:** `DELETE /api/venues/:venueid`
* **Yorum ekle (mekana):** `POST /api/venues/:venueid/comments`
* **Yorum getir:** `GET /api/venues/:venueid/comments/:commentid`
* **Yorum güncelle:** `PUT /api/venues/:venueid/comments/:commentid`
* **Yorum sil:** `DELETE /api/venues/:venueid/comments/:commentid`

---

## Postman Test Sonucu

Aşağıda Postman ile alınmış test sonuçlarının ekran görüntüsü bulunmaktadır:

<img width="2177" height="1306" alt="AddVenue" src="https://github.com/user-attachments/assets/3137b2e2-409d-4df8-90d8-d30d76553150" />

<img width="2176" height="1344" alt="AddComment" src="https://github.com/user-attachments/assets/c64e03ee-c27c-49f4-8e28-287609c3f994" />

<img width="2179" height="1342" alt="UpdateVenue" src="https://github.com/user-attachments/assets/7b166223-8734-4f78-ad0e-2e63a53ea1b0" />

<img width="2178" height="1345" alt="UpdateComment" src="https://github.com/user-attachments/assets/66750531-f039-48db-85c2-ba6cbbc23ed0" />

<img width="2177" height="1343" alt="GetVenue" src="https://github.com/user-attachments/assets/bc764bbd-b7be-4d8b-a4f9-a85a245f6e11" />

<img width="2175" height="1342" alt="GetComment" src="https://github.com/user-attachments/assets/8793c148-92dc-4a1e-b5e0-5a51272851d9" />

<img width="2173" height="1345" alt="ListNearlyVenues" src="https://github.com/user-attachments/assets/46991d15-9498-41f4-a4c9-3db276af8079" />

<img width="2176" height="1343" alt="DeleteComment" src="https://github.com/user-attachments/assets/99a58bdf-dff6-4631-b8d7-73b198eb7501" />

<img width="2177" height="1340" alt="DeleteVenue" src="https://github.com/user-attachments/assets/fc2a0496-bb86-45ef-92f2-b41d542b47e9" />

