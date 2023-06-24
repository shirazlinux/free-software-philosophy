---
title: Penggunaan ulang Free Software
weight: 90
---

Salat satu keuntungan dari Free Software adalah potensi yang tinggi dari
penggunaan ulang.
Anda dapat menggabungkan kode dari proyek Free Software lain ke dalam proyek
yang baru, menghemat waktu.
Tentu saja Anda harus menghargai hasil kerja dari proyek yang asli, dan ini
berarti tunduk dengan syarat-syarat dari lisensi Free Software yang mereka
gunakan.

{{< tip "warning" >}}
Selalu baca lisensi dengan teliti saat menggabungkan hasil kerja orang lain ke
dalam perangkat lunak Anda.
{{< /tip >}}

## Menggabungkan perangkat lunak permisif

Daya tarik utama dari lisensi perangkat lunak yang permisif yaitu kita bisa
menggabungkan-nya ke dalam kerja apa pun dengan sedikit kewajiban terhadap
pemegang hak cipta yang aslinya.
Kebanyakan lisensi permisif membutuhkan Anda hanya mencantumkan teks lisensi,
atau cuma pernyataan hak cipta, dalam produk Anda.
Bagi proyek Free Software yang menggabungkan kode dengan lisensi permisif ke
dalam hasil kerja mereka, memenuhi kewajiban ini biasanya semudah menambahkan
berkas lisensi tambahan ke dalam sumber kode Anda.

Saat menggabungkan perangkat lunak dengan lisensi permisif ke dalam hasil
kerja yang tidak-bebas, Anda harus mendistribusikan lisensi Free Software
dan/atau atribusi hak cipta bersama dengan perangkat lunak Anda.
Kebanyakan penggunaan komersil dari perangkat lunak permisif menambahkan
sebuah menu ke dalam produk mereka yang menampilkan semua lisensi perangkat
lunak, atau mengikutkan versi cetak lisensi dari produk.
Anda bisa menggunakan pendekatan yang sama untuk tetap mengikuti syarat dari
lisensi-lisensi tersebut.


## Menggabungkan perangkat lunak _copyleft_

{{< tip "warning" >}}
Perangkat lunak _copyleft_ **tidak bisa** digabungkan ke dalam perangkat lunak
yang tidak-bebas.
{{< /tip >}}

Kebanyakan Free Software dapat digabungkan ke dalam perangkat lunak
_copyleft_, dan sebaliknya, jika lisensi mereka **kompatibel**.
Umumnya, lisensi-lisensi permisif yang terkenal -- tapi tidak semua --
kompatibel dengan kebanyakan lisensi _copyleft_ yang terkenal.
*Beberapa* lisensi _copyleft_ kompatibel dengan lisensi _copyleft_ yang lain
(misalnya, Mozilla Public License 2.0 kompatibel dengan lisensi-lisensi di
dalam keluarga GNU), tapi kebanyakan juga tidak kompatibel.
Bila dua proyek menggunakan lisensi _copyleft_ yang *sama* maka mereka
kompatibel satu dengan yang lain dan bisa berbagi kode dengan bebas.

{{< tip >}}
GNU memiliki [daftar lisensi][0] yang kompatibel dan tidak kompatibel dengan
lisensi-lisensi _copyleft_ dalam keluarga GPL.

[0]: https://www.gnu.org/licenses/license-list.html
{{< /tip >}}

Menggabungkan kode permisif ke dalam sebuah proyek _copyleft_ sangat mudah
bila lisensi-nya kompatibel: lihat bagian sebelumnya.

{{< tip "warning" >}}
Sebaliknya, menggabungkan perangkat lunak _copyleft_ ke dalam proyek perangkat
lunak permisif, tidak mudah.
Pada kasus ini, gabungan hasil kerja harus memenuhi syarat-syarat dari lisensi
_copyleft_.
Mengatur kumpulan lisensi yang permisif dan _copyleft_ dalam satu hasil kerja
memungkinkan, namun ada implikasi-nya bagi proyek Anda.
Hal ini sangat tidak disarankan bagi yang tidak berpengalaman: jangan
campurkan kode _copyleft_ ke dalam proyek permisif Anda kecuali bila Anda
mempersiapkan proyek tersebut untuk
[pindah ke lisensi _copyleft_](/id/learn/participate/copyright-ownership/#changing-a-projects-license).
{{< /tip >}}

## Mengatur banyak lisensi dan hak cipta dalam satu proyek.

Proyek yang kompleks dan besar biasanya menggabungkan perangkat lunak dari
banyak sumber kode dengan beragam lisensi dan pemegang hak cipta.
Jika proyek Anda seperti ini, kami rekomendasi kan untuk menerapkan
spesifikasi
[REUSE](https://reuse.software/)
ke dalam kerja Anda.
