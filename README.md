ANALISIS HASIL

	Waktu Eksekusi untuk Pendekatan Rekursif:
o	Nilai n=10 dan n=30: Waktu eksekusi tercatat sebagai 0 mikrodetik. Ini mungkin terjadi karena nilai n yang relatif kecil atau karena waktu yang dibutuhkan sangat kecil sehingga tidak terukur oleh alat pengukur waktu yang digunakan.
o	Nilai n=25,   dan n=40 : Terdapat peningkatan signifikan dalam waktu eksekusi, terutama pada n=40 dengan waktu eksekusi mencapai 1.142.641 mikrodetik (sekitar 1,14 detik). Ini menunjukkan kompleksitas eksponensial dari pendekatan rekursif.
o	Nilai n=50 : Data diwakili sebagai none karena waktu eksekusi terlalu lama untuk dihitung secara praktis. Ini mengindikasikan bahwa pendekatan rekursif tidak efisien untuk nilai n yang besar.

	Waktu Eksekusi untuk Pendekatan DP:
Untuk semua nilai n yang diuji (10, 25, 30, 40, dan 50), waktu eksekusi tercatat sebagai 0 mikrodetik. Ini menunjukkan efisiensi tinggi dari pendekatan DP, di mana waktu yang diperlukan untuk menghitung nilai Fibonacci hampir konstan dan sangat kecil sehingga alat pengukur waktu mungkin tidak mampu mendeteksinya.
	Perbandingan Kinerja
Dari hasil diatas, kita dapat melihat bahwa pendekatan rekursif menjadi sangat lambat untuk nilai 𝑛 yang besar. Ini disebabkan oleh sifat rekursif yang melakukan banyak perhitungan berulang, menghasilkan kompleksitas waktu eksponensial. Sebaliknya, pendekatan DP sangat efisien karena menggunakan tabel untuk menyimpan hasil perhitungan sebelumnya, menghasilkan kompleksitas waktu linear.

	Penyebab Perbedaan Waktu Eksekusi
Pendekatan rekursif untuk menghitung Fibonacci mengharuskan perhitungan ulang untuk setiap sub-masalah, yang menyebabkan jumlah operasi yang dilakukan tumbuh secara eksponensial. Misalnya, untuk 𝑛 = 50, algoritma rekursif melakukan perhitungan ulang yang sangat banyak, menyebabkan waktu eksekusi yang sangat lama. Pendekatan DP menghindari perhitungan ulang ini dengan menyimpan hasil setiap sub-masalah dalam tabel dan menggunakan kembali hasil ini, yang membuatnya jauh lebih cepat dan efisien.
![image](https://github.com/Innulaa/Analisis-Deret-Fibonanci/assets/149084934/f389a926-894f-4b9a-b4eb-2654a64cc6be)
