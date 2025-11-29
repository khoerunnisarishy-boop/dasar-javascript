Siap! Aku bikinkan README yang **lebih rapi, profesional, dan enak dibaca** untuk project JavaScript kamu ini ✨
Langsung bisa kamu taruh sebagai **README.md** di dalam repo.

---

## 📌 README.md — Program Biodata & Saldo (JavaScript)

```markdown
# 💻 Program Biodata & Perhitungan Saldo (JavaScript)

Program ini dibuat untuk menampilkan informasi biodata seorang user dan melakukan perhitungan sederhana mengenai saldo keuangan.

Program menggunakan beberapa tipe data JavaScript seperti:
- **String**
- **Number**
- **Null**
- **Undefined**
- **Const & Let**
- **Template Literal**
- **Percabangan (if-else)**

---

## 🧠 Penjelasan Singkat Program

1. Menyimpan data diri seperti:
   - Nama
   - Usia
   - Tinggi badan
   - Makanan favorit (belum diisi → akan menjadi `undefined`)
   - Status pacar (`null` yang kemudian dicek dengan `if-else`)

2. Menghitung jumlah saldo akhir dengan operasi matematika:
```

saldoAkhir = saldoAwal + saldoTambahan

````

3. Menampilkan seluruh informasi menggunakan `alert()` dalam bentuk template string.

---

## 🧑‍💻 Kode Program

```javascript
let nama = 'Rishy Khoerunnisa' // tipe string
let usia = 18 //tipe integer number
let tinggiBadan = 154 // tipe double float
let makananFavorit 
let pacar = null

if (pacar == null) {
 pacar = 'belum punya'
} else {
 pacar = 'udah punya'
}

let saldoAwal = 10000
let saldoTambahan = 50000
const saldoAkhir = saldoAwal + saldoTambahan

alert(
 `hai, namaku ${nama} aku berusia ${usia} tinggi badanku sekitar ${tinggiBadan}, lalu makanan favoritku ${makananFavorit} dan pacarku ${pacar}, `
)

alert(
 `aku punya saldo sebesar Rp.${saldoAwal} lalu ayahku mengirim Rp.${saldoTambahan}, jadi jumlah semua uangku adalah Rp.${saldoAkhir}`
)
````

---

## 📌 Output Program

```
hai, namaku Rishy Khoerunnisa aku berusia 18 tinggi badanku sekitar 154, lalu makanan favoritku undefined dan pacarku belum punya,
aku punya saldo sebesar Rp.10000 lalu ayahku mengirim Rp.50000, jadi jumlah semua uangku adalah Rp.60000
```

---

## 🔧 Cara Menjalankan Program

1. Buat file HTML dan hubungkan dengan file JavaScript ini
   atau buka lewat **browser console** Developer Tools
2. Jalankan file HTML di browser
3. Akan muncul **alert pop-up** sebagai output

---

## 📝 Catatan

Variabel `makananFavorit` belum diberi nilai,
sehingga output menampilkan **undefined**.
Jika ingin lebih bagus, bisa diisi contohnya:

```javascript
let makananFavorit = 'Mie Ayam'
```

---

## 👩‍💻 Pembuat

* **Nama** : Rishy Khoerunnisa
* **Project** : Dasar JavaScript (Variabel & Percabangan)

---

> ✨ Program sederhana ini cocok untuk pemula JavaScript dalam memahami tipe data, logika dasar, dan template literal.

```

ct lain juga? 😊
```
