# self-payrol-question


## Latar Belakang Tugas
Pada task 5, peserta akan diuji menggunakan proyek asli. salah satu tanggung jawab BE Developer yaitu membentuk sebuah API dengan baik dan benar.


## Tahapan Pengerjaan
Fitur yang harus dikerjakan adalah sebagai berikut: 

- Melakukan manage data jabatan berupa operasi CRUD (create, read, update, delete)
- Melakukan manage data employee berupa operasi CRUD (Create, Read, Update, Delete)
- Admin dapat melakukan topup balance perusahaan
- Melakukan penarikan sallary dengan menyertakan employee ID dan secret ID, besaran salary berdasarkan jabatan yang dimiliki oleh tiap employee
- Terdapat riwayat topup dan pengurangan balance perusahaan 

Untuk memudahkan dalam perancangan database silahkan menggunakan [rancangan database](https://drive.google.com/file/d/1N7R7u229GBKsmS3D_SfvJGGS36Q6kQi4/view?usp=sharing) yang telah disediakan, semua endpoint dan response harus sesuai dengan link dokumentasi yang ada pada [postman documenter](https://documenter.getpostman.com/view/4080490/2s83Ychhk4)

Web service kali ini dibuat dengan bahasa GO dan menggunakan database PostgreSQL, sangat disarakan untuk melakukan implementasi clean code sehingga mudahkan dalam pengembangan selanjutnya dan dapat mempermudah pekerjaan secara berkelompok. 

Jangan lupa untuk :

- Menginstall PostGreSQL ke sistem operasi kalian melalui [link ini](https://www.postgresql.org/download/) 
- Menginstall bahasa GoLang terbaru melalui [link ini](https://github.com/bxcodec/go-clean-arch) 
- Menginstall code editor seperti Visual Studio Code. IntelliJ, atau code editor lainnya.

## Hints

- Gunakan GO versi terbaru atau lainnya
- Sangat direkomendasikan melakukan implementasi [clean architecture](https://github.com/bxcodec/go-clean-arch)
- Gunakan framework pendukung untuk membuat RestFull API, sangat direkomendasikan menggunakan [Echo](https://github.com/labstack/echo) 
- Gunakan ORM untuk melakukan konseksi ke database, sangat direkomendasikan menggunakan [Gorm](https://gorm.io/)
- Untuk terkoneksi dengan PostgreSQL dapat menggunakan menuju [dokumentasi](https://gorm.io/docs/connecting_to_the_database.html#PostgreSQL) 
- Logging sangat berguna dalam pembuatan web service, kamu bisa menggunakan default logging dari Echo atau menggunakan [Logrus](https://github.com/sirupsen/logrus)
- Gunakan RDBMS client unutuk mempermudah melihat data, sangat direkomendasikan menggunakan TablePlus 
- Buat database sesuai dengan diagram yang telah disertakan, file diagram dapat di unduh melalui link [berikut ini](https://drive.google.com/file/d/1N7R7u229GBKsmS3D_SfvJGGS36Q6kQi4/view?usp=sharing)
- Gunakan sumber daya yang telah di sediakan pada assignment ini seperti format pengerjaan dan study case se maksimal mungkin!
