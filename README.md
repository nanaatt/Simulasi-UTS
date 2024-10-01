Berikut adalah laporan latihan UTS Pemrograman Berorientasi Objek

# LAPORAN LATIHAN UTS PEMROGRAMAN BERORIENTASI OBJEK

👨‍🏫 **Dosen Pembimbing**: Bayu Adi Nugroho, Ph.D  
🎓 **Program Studi**: Sistem Informasi

Laporan ini dibuat guna melengkapi tugas latihan UTS pada nomor 6 mengenai CRUD dengan Java Swing dan menggunakan Database buku yang memiliki atribut 📚 **ISBN**, 📖 **Judul Buku**, 🗓️ **Tahun Terbit**, dan 🏢 **Penerbit**.

---

## A. Penjelasan Materi Secara Singkat

🔄 **CRUD** merupakan operasi query untuk melakukan relasional pada database serta perubahan data atau tampilan suatu informasi. CRUD adalah singkatan dari **Create**, **Read**, **Update**, dan **Delete**. Berikut penjelasan singkatnya:

- **Create (📝)**: Proses pembuatan data baru.
- **Read (🔍)**: Proses pengambilan data atau melakukan verifikasi dari data yang sudah diinputkan.
- **Update (✏️)**: Proses perubahan atau modifikasi data yang sudah ada.
- **Delete (🗑️)**: Proses penghapusan data yang sudah ada.

---

## B. Langkah-langkah

1. **Membuat Frame**  
   Membuat Class DbUtils dan frame form dengan nama sesuai kebutuhan, di sini saya menggunakan nama **Buku**. Kemudian GUI dapat didesain sesuai keinginan. Untuk pembuatan tulisan data buku, ISBN, judul buku, tahun terbit, dan penerbit menggunakan **Swing Control Label** 🏷️. Untuk pembuatan kotak putih dibagian depan atau setelah ISBN, judul buku, tahun terbit, dan penerbit dibuat dengan **Swing Control Text Field** 📄. Untuk pembuatan tombol **Insert**, **Update**, dan **Delete** dibuat dengan **Swing Control Button** 🔘. Untuk pembuatan tabel bisa langsung menggunakan **Swing Control Tabel** 📊.
   
   ![Screenshot (263)](https://github.com/user-attachments/assets/d27b435d-efaa-4c3e-8fe0-cfd640c7deeb)
   ![Screenshot (262)](https://github.com/user-attachments/assets/01d67fca-2723-47bf-a7e2-0d85aaad8e7c)

3. **Penambahan Data (Insert)**  
   Setelah membuat desain kita dapat pergi ke source dengan menginputkan code pada GitHub yang bernama **Buku.java** sesuai tata letaknya di source code. Setelah itu dapat dilakukan operasi yang pertama yaitu **Insert** (penambahan data) 📝. Disini saya melakukan penambahan buku yang berjudul Hujan.
   
   ![Screenshot 2024-10-02 050242](https://github.com/user-attachments/assets/10ed2d92-5b6e-45f9-8d47-66b1d615fd04)
   ![Screenshot 2024-10-02 050438](https://github.com/user-attachments/assets/65452bd6-92d8-49eb-a9d7-367f3494b36b)
   ![Screenshot 2024-10-02 050459](https://github.com/user-attachments/assets/d66899e1-d291-4974-89fe-e436288a45e9)
   ![Screenshot 2024-10-02 050507](https://github.com/user-attachments/assets/d6489f42-4775-4296-bbb4-9e345623162f)

5. **Perubahan Data (Update)**  
   Operasi kedua adalah melakukan **Update** (perubahan data) yang sudah ada ✏️. Disini saya melakukan update pada buku yang berjudul Algoritme Rasa dan mengubah tahun terbitnya saja yang semula 2019 menjadi 2020.
   
   ![Screenshot 2024-10-02 050559](https://github.com/user-attachments/assets/5da4ba9f-03e7-4b49-b963-b8a08f7c52a7)
   ![Screenshot 2024-10-02 050614](https://github.com/user-attachments/assets/be297bdb-b046-4349-8c08-cfe1312e0353)
   ![Screenshot 2024-10-02 050630](https://github.com/user-attachments/assets/cbf4009c-1b45-4d0d-af87-a268962d84a0)
   ![Screenshot 2024-10-02 050640](https://github.com/user-attachments/assets/e54ee830-9451-4c1a-add2-1abda6180d96)

7. **Penghapusan Data (Delete)**  
   Operasi ketiga adalah **Delete** (penghapusan data) yang sudah ada 🗑️. Dalam operasi ini bisa melakukan delete hanya dengan menginputkan **ISBN** saja agar mempermudah saat memiliki data yang banyak. Disini saya melakukan delete pada buku yang berjudul Laut Bercerita.
   
   ![Screenshot 2024-10-02 050747](https://github.com/user-attachments/assets/351c3dcc-c9d6-46de-ae96-f909f6f958cd)
   ![Screenshot 2024-10-02 050803](https://github.com/user-attachments/assets/2abb6959-8950-4315-a916-23fa4456562f)
   ![Screenshot 2024-10-02 050811](https://github.com/user-attachments/assets/af040aa7-fb6a-4462-b001-d14b313b898c)
