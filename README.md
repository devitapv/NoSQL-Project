# NoSQL-Project
1. Pada project ini akan membuat collection baru dengan nama `clean_movies_devita` menggunakan pyMongo di Python. Database yang digunakan merupakan database `sample_mflix` yang berisikan beberapa collection. <br> 
2. Pada project ini, collection yang baru berisikan collection `movies_initial` dengan format field menyesuaikan dari collection `movies` dengan melakukan connection pada cluster berikut : <br>
client = MongoClient("mongodb+srv://userstudent:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true&w=majority")
3. Kesimpulan setelah membuat collection baru :
  - Document yang ada pada `movies` dan `clean_movies_devita` memiliki perbedaan dalam segi jumlah document.
  - Format field antara kedua collection telah sama namun pada value dari masing-masing field terdapat beberapa perbedaan, hal ini dikarenakan pada `movies_initial` tidak memiliki data yang sama dengan `movies`.
