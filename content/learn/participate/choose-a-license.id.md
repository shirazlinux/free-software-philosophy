---
title: Memilih lisensi
weight: 3
---

Memilih sebuah lisensi adalah bagian penting dalam merilis proyek Free
Software Anda.
Ada banyak pilihan, dan setiap-nya memiliki kekurangan dan implikasi bagi
proyek Anda di masa depan.
Akan sangat sukar untuk [mengubah lisensi nantinya], jadi Anda harus
memperhatikan secara teliti dari awal.

[mengubah lisensi nantinya]: /id/learn/participate/copyright-ownership/

Berikut beberapa lisensi Free Software yang kami rekomendasikan, dan kenapa
Anda harus memilihnya.

{{< tip >}}
Setelah Anda memilih lisensi, masukan ke dalam perangkat lunak Anda.
Cara paling mudah yaitu menyalin versi teks ke dalam berkas "COPYING" dalam
repositori sumber kode Anda.
Untuk skenario yang lebih komples, kami merekomendasikan pendekatan
[REUSE][0].

[0]: https://reuse.software/
{{< /tip >}}

## Lisensi-lisensi copyleft

Lisensi _copyleft_ berguna untuk memastikan bahwa perangkat lunak Anda tetap
bebas.
Penggunaan _copyleft_ mengharuskan setiap orang yang melakukan peningkatan
terhadap perangkat lunak Anda merilis-nya di bawah lisensi _copyleft_ yang
sama, yang mana memastikan bahwa Anda dapat menggabungkan peningkatan mereka
ke dalam versi Anda lagi.
Untuk lebih rinci, lihat
[Apa itu copyleft?](/id/learn/copyleft/)

{{< block "grid-2" >}}

{{< column "pros" >}}

### Kelebihan

* Memastikan perangkat lunak tetap bebas
* Mendorong kontribusi dari komunitas
* Mempromosikan Free Software secara umum

{{< /column >}}

{{< column "cons" >}}

### Kekurangan

* Kurang atraktif dari sisi bisnis
* Harus mempertimbangkan kompatibilitas lisensi untuk penggunaan ulang

{{< /column >}}

{{< /block >}}

### Lisensi _copyleft_ yang direkomendasikan

| Lisensi | Digunakan untuk ... | Pendekatan copyleft |
| --- | --- | --- |
| [Mozilla Public License 2.0] | Pustaka (membolehkan <abbr title="Cara menyalin pustaka ke dalam proyek Anda, bukan mengaitkan">vendor</abbr>) | Berbasis-berkas |
| [GNU Lesser General Public License] | Pustaka (tidak membolehkan vendor) | Berbasis-objek |
| [GNU General Public License] | Program | Berbasis-program |
| [GNU Affero General Public License] | Layanan jaringan | Berbasis-jaringan |

[Mozilla Public License 2.0]: https://www.mozilla.org/en-US/MPL/2.0/
[GNU Lesser General Public License]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[GNU General Public License]: https://www.gnu.org/licenses/gpl-3.0.html
[GNU Affero General Public License]: https://www.gnu.org/licenses/agpl-3.0.html

## Lisensi permisif

Lisensi permisif secara relatif memiliki sedikit kewajiban dari sisi penerima
perangkat lunak Anda.
Lisensi ini membolehkan perangkat lunak bebas digunakan ulang dan
diintegrasikan ke dalam proyek perangkat lunak mana pun, termasuk yang
tidak-bebas.
Lisensi ini berguna untuk proyek yang menargetkan penggunaan komersil atau
adopsi yang luas.

{{< block "grid-2" >}}

{{< column "pros" >}}

### Kelebihan

* Membolehkan penggunaan ulang yang mudah
* Mendorong adopsi lebih luas
* Menarik pengguna dari sisi bisnis

{{< /column >}}

{{< column "cons" >}}

### Kekurangan

* Dapat digabungkan ke dalam kerja tidak-bebas
* Kurang mendorong kontribusi dari komunitas

{{< /column >}}

{{< /block >}}

### Lisensi permisif yang direkomendasikan

Kami merekomendasikan lisensi permisif berikut:

* [MIT license](https://mit-license.org/)
* [BSD 3-clause license](https://opensource.org/license/bsd-3-clause/)

## Rekomendasi untuk bisnis

Bagi perusahaan yang merilis Free Software, menginginkan penggunaan lisensi
yang permisif yang mengikutkan hak dagang dan hak patent.
Untuk tujuan ini kami merekomendasikan 
[Apache 2.0 license].

[Apache 2.0 license]: https://www.apache.org/licenses/LICENSE-2.0.html

## Domain publik

Penerbit yang menginginkan perangkat lunak mereka masuk ke domain publik
haruslah ingat bahwa domain publik itu sendiri tidak cukup bagi penggunaan
secara internasional.
Kami merekomendasikan lisensi berikut, yang menyediakan hak legal yang sama
dengan domain publik dengan cara yang kompatibel dengan hukum-hukum
internasional:

* [Creative Commons 0](https://creativecommons.org/share-your-work/public-domain/cc0/)
* [Unlicense](https://unlicense.org/)

## Lisensi untuk situasi lain

Kami memiliki halaman terpisah untuk rekomendasi lisensi bagi aset yang bukan
perangkat lunak, seperti multimedia:

[Lisensi aset yang bukan perangkat lunak](/id/learn/participate/assets/)
