---
title: Lisensi Free Software
weight: -9
---

Ke [empat prinsip kebebasan](/id/learn/four-freedoms/) secara umum dijamin
lewat penggunaan sebuah **lisensi Free Software**.
Ada banyak macam lisensi dengan kelebihan dan kekurangan masing-masing,
menyesuaikan dengan situasi unik dari proyek perangkat lunak.

## Bagaimana cara kerja lisensi dari Free Software

Lisensi dari Free Software memberikan hak-hak yang diperlukan, mungkin dengan
beberapa kondisi (seperti atribusi), untuk membentuk empat prinsip kebebasan
bagi penerima perangkat lunak.
Setiap lisensi perangkat lunak bisa saja lisensi buat Free Software jika
ia memegang empat prinsip kebebasan, namun secara praktis kebanyakan proyek
memilih salah satu dari sekian banyak lisensi yang terkenal.
Informasi tentang lisensi perangkat lunak ini dan bagaimana cara memilih di
antara mereka untuk proyek Anda dijelaskan dalam
[memilih lisensi](/id/learn/participate/choose-a-license/).

Terkadang Anda akan menemukan lisensi Free Software dalam berkas "LICENSE"
atau "COPYING" yang ada di dalam sumber kode perangkat lunak.
Proyek lainnya, khususnya yang menggabungkan perangkat lunak dari beragam
sumber, memiliki cara yang kompleks dalam penggunaan lisensi.
Pendekatan umum untuk kasus seperti ini ada di
[spesifikasi REUSE][0].

[0]: https://reuse.software/

Jika Anda ingin mengetahui lebih lanjut tentang bagaimana lisensi bekerja
lebih rinci, tetap baca artikel ini.
Jika tidak:

{{< button "/id/learn/participate" "Lanjut: Ikut serta" "next-button" >}}

## Sifat umum dari lisensi Free Software

Untuk memahami kewajiban Anda di bawah lisensi mana pun, Anda harus membacanya
(dan mungkin konsultasi dengan pengacara, khususnya bila Anda
merepresentasikan entitas bisnis).
Namun, kebanyakan lisensi Free Software memiliki beberapa sifat yang mirip
satu dengan yang lain, dan Anda bisa memahami semuanya dengan mempelajari
tentang beberapa sifat tersebut.
Berikut beberapa sifat umum dari lisensi Free Software:


### Atribusi

Klausa atribusi membutuhkan Anda untuk **mencantumkan** penulis, dari hasil
kerja, saat mendistribusikan atau menggunakan perangkat lunak yang menggunakan
lisensi dengan klausa tersebut.
Hal ini biasanya dilakukan dengan mencantumkan seluruh lisensi, atau terkadang
cukup dengan mencantumkan hak cipta, saat Anda mendistribusikan, memodifikasi,
atau menggabungkan sebagian atau keseluruhan perangkat lunak.

Berikut contoh atribusi dari [lisensi MIT]:

> Permission is hereby granted, free of charge, to any person obtaining a copy of
> this software and associated documentation files (the “Software”), to deal in
> the Software without restriction, including without limitation the rights to
> use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
> the Software, and to permit persons to whom the Software is furnished to do so,
> subject to the following conditions:
> 
> <strong style="color: var(--theme)">The above copyright notice and this permission
> notice shall be included in all copies or substantial portions of the
> Software.</strong>

[lisensi MIT]: https://mit-license.org

### Peringatan garansi

Free Software sering kali dilihat sebagai hadiah.
Sebagai pertukaran dari hadiah ini, Anda akan diminta untuk menerima perangkat
lunak tersebut seadanya, tanpa ada ekspektasi dukungan atau garansi dari
penerbit.
**Peringatan garansi** ini digunakan untuk mencegah penulis bertanggung jawab
dari penggunaan Free Software yang mereka rilis, jadi penerima-lah yang
bertanggung jawab sepenuhnya dengan apa yang mereka lakukan dengan perangkat
lunak tersebut.

Berikut contoh peringatan garansi pada [lisensi MIT]:

> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.

### _Copyleft_

Beberapa lisensi tidak hanya *membolehkan* Anda membagikan peningkatan, tapi
*mengharuskan* Anda membagikan perangkat lunak atau turunan dari perangkat
lunak tersebut dengan menggunakan lisensi yang sama.
Bentuk seperti ini adalah lisensi **_copyleft_**: sebuah perangkat untuk
melindungi Free Software dari tercampur dengan hasil kerja yang tidak-bebas.

Berikut contoh _copyleft_ dari [Mozilla Public License 2.0]:

> All distribution of Covered Software in Source Code Form, including any
> Modifications that You create or to which You contribute, must be under the
> terms of this License. You must inform recipients that the Source Code Form of
> the Covered Software is governed by the terms of this License, and how they
> can obtain a copy of this License. You may not attempt to alter or restrict
> the recipients’ rights in the Source Code Form.

[Mozilla Public License 2.0]: https://www.mozilla.org/en-US/MPL/2.0/

{{< tip >}}
Lisensi _copyleft_ dijelaskan lebih detil dalam
[Apa itu Copyleft?](/id/learn/copyleft)
{{< /tip >}}

### Kompatibilitas lisensi dan sub-lisensi

Kemampuan untuk menggabungkan hasil kerja secara bersama adalah sifat esensial
dari ekosistem Free Software, namun penggunaan beberapa lisensi dengan hak
cipta yang berbeda kadang membuat pekerjaan menjadi sukar.
Maka **sub-lisensi** dan **kompatibilitas lisensi** membantu: banyak lisensi
Free Software membuat ketentuan bagaimana mereka dapat dikembangkan dengan
mengikuti syarat-syarat dari lisensi lainnya.
Hal ini membolehkan kita menggabungkan perangkat lunak dengan dua atau lebih
lisensi yang kompatibel untuk menghasilkan perangkat lunak baru dengan tetap
memenuhi syarat lisensi dari semuanya.

Tidak semua lisensi memiliki syarat yang kompatibel satu dengan yang lain;
khususnya lisensi _copyleft_ condong kurang kompatibel dengan yang lain.
Perangkat lunak dengan lisensi yang tidak kompatibel tidak bisa digabungkan
dengan hasil kerja yang lain.

{{< tip >}}
Anda dapat mempelajari tentang kompatibilitas lisensi dalam
[Penggunaan ulang Free Software](/id/learn/participate/derived-works/).
{{< /tip >}}

### Penggunaan merek dagang dan hak paten

Lisensi perangkat lunak umumnya berurusan dengan hak cipta, namun penerbit
perangkat lunak komersil memegang jenis properti intelektual yang lain,
seperti hak dagang dan paten.
Beberapa lisensi Free Software memiliki klausa yang menangani hubungan antara
hak cipta dan properti intelektual yang lain, misalnya menyetujui bahwa
penggunaan perangkat lunak tidak akan melanggar paten dari pemegang hak cipta,
atau melarang penggunaan hak dagang dari pemegang hak cipta.

Berikut contohnya dari [Apache 2.0 license]:

> 3. **Grant of Patent License.** Subject to the terms and conditions of this
>    License, each Contributor hereby grants to You a perpetual, worldwide,
>    non-exclusive, no-charge, royalty-free, irrevocable (except as stated in
>    this section) patent license to make, have made, use, offer to sell, sell,
>    import, and otherwise transfer the Work, where such license applies only to
>    those patent claims licensable by such Contributor that are necessarily
>    infringed by their Contribution(s) alone or by combination of their
>    Contribution(s) with the Work to which such Contribution(s) was submitted.
>    If You institute patent litigation against any entity (including a
>    cross-claim or counterclaim in a lawsuit) alleging that the Work or a
>    Contribution incorporated within the Work constitutes direct or
>    contributory patent infringement, then any patent licenses granted to You
>    under this License for that Work shall terminate as of the date such
>    litigation is filed.

[Apache 2.0 license]: https://www.apache.org/licenses/LICENSE-2.0.html
