# roadmap cara bikin aplikasi expressjs
## development
1. init project `pnpm init`
2. akan muncul file `package.json`
3. buat file `index.js`
4. install package `expressjs, nodemon, mysql12`
5. ubah package.json `script : {"dev" : "nodemon index.js"}`
6. ubah package.json `type : module`
7. edit file index.js dan tambahkan kode express dan tentukan portnya
8. buat folder yang dibutuhkan misalkan
          - routes
          - controllers
          - models
          - config
## design database
1. buat database 
2. menentukan field table

## configurasi
1. buat file konfigurasi database di folder config
2. tentukan usename,password dan nama database
3. jika menggunkan `.env` buat juga file `.env` nya

## mulai development 
1. mengisi file pada struktur folder yang telah dibuat misalkan isi folder routes : useRouter.js, postRouter.js
2.  ujicoba apakah route sudha berhasil dipanggil dari postman
3. buat file controller pada struktur folder controller yang telah dibuat misalnya userController.js dan lainnya
4. tambahkan kode controller ke dalam routes
5. uji coba apakah controller sudah berhasil atau bisa di akses jika memanggil router
6. buat file model yang menggunakan konfigurasi dari `config/database.js` dan buat seluruh method yang di butuhkan
7. implementasi model yang dibuat ke controller
8. ujicoba kembali secara menyeluruh
9. tambahkan middleware cors bila dibutuhkan agai API bisa diakses dari frontend
